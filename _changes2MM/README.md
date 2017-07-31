# Changes to Minimal Mistakes for LaMaStEx
I did the following changes to [https://github.com/mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes) displayed at [https://mmistakes.github.io/minimal-mistakes/](https://mmistakes.github.io/minimal-mistakes/) 
in my fork at [https://github.com/lamastex/lamastex.github.io](https://github.com/lamastex/lamastex.github.io) displayed at [https://lamastex.github.io/](https://lamastex.github.io/).

### To allow logo to be displayed with site-title

0. used inkscape to make a SVG image for te logo - make it square with width=height

1. add the following to '_sass/minimal-mistakes/_masthead.scss' after the '.site.title{...}' 
```
.site-logo {
  width: $site-image-width;
  height: $site-image-height;
  margin-right: 0.5rem;
  border-radius: 50%;
}

```

2. added these variable to _variables.scss (make this 30px or smaller depending on your log SVG or PNG image for site.logo you will add in step 4 below):
```
$site-image-width: 50px !default;
$site-image-height: 50px !default;
```

3. replace '_includes/masthead.html' with
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

4. add the following line to '_config.yml'
```
logo                     : "/assets/images/site-logo01BallOnly40x40.svg"
```

If you find a better way please communicate it by twitter to '@raazozone'.

### Make index.md at root level 
But with home layout that is actually splash. 
This is to get around pagination issues

```
$ pwd
PATH_TO_LOCAL_GIT_REPO/lamastex.github.io

$ cp _layouts/home.html _layouts/old-home.html

$ cp _layouts/splash.html _layouts/home.html 

$ head index.md 
---
layout: home
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/DISP-lamastex-1600x524.jpg
  caption: 
excerpt: 'Welcome to LaMaStEx, a laboratory for mathematical statistical experiments.<br /><br /><br />'
feature_row:
  - image_path: /assets/images/DISP-research-500x300.jpg
...
...
...
```

