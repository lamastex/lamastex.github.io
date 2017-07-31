# Changes to Minimal Mistakes for LaMaStEx
I did the following changes to [https://github.com/mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) displayed at [https://mmistakes.github.io/minimal-mistakes/](https://mmistakes.github.io/minimal-mistakes/) 
in my fork at [https://github.com/lamastex/lamastex.github.io](https://github.com/lamastex/lamastex.github.io) displayed at [https://lamastex.github.io/](https://lamastex.github.io/).

### To allows logo to be displayed with site-title
0. used inkscape to make a SVG image for te logo - make it square with width=height
1. renamed '.site-title' to '.site-title-old' in '_sass/minimal-mistakes/_masthead.scss' in case you need it later.
2. copied the '.site-title' and '.site-logo' containing file: 
```
https://github.com/mmistakes/jekyll-theme-basically-basic/blob/master/docs/_sass/basically-basic/_global.scss
```
to '_sass/minimal-mistakes/_global.scss'
3. added these variable to _variables.scss
```
$site-image-width: 50px !default;
$site-image-height: 50px !default;
```
4. replace with
```
{% if site.logo contains '://' %}
  {% assign site_logo = site.logo %}
{% else %}
  {% assign site_logo = site.logo | relative_url %}
{% endif %}

<div class="masthead">
  <div class="masthead__inner-wrap">
    <div class="masthead__menu">
      <nav id="site-nav" class="greedy-nav">
        <a class="site-title" href="{{ '/' | absolute_url }}">
          {% if site.logo %}<img src="{{ site_logo }}" alt="" class="site-logo">{% endif %}
          <span>{{ site.title }}</span>
        </a>
        <ul class="visible-links">
          {% for link in site.data.navigation.main %}
            {% if link.url contains 'http' %}
              {% assign domain = '' %}
            {% else %}
              {% assign domain = site.url | append: site.baseurl %}
            {% endif %}
            <li class="masthead__menu-item"><a href="{{ domain }}{{ link.url }}">{{ link.title }}</a></li>
          {% endfor %}
        </ul>
        <button><div class="navicon"></div></button>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>
```
5. add the following line to '_config.yml'
```
logo                     : "/assets/images/site-logo01BallOnly40x40.svg"
```

If you find a better way please communicate it by twitter to '@raazozone'.

