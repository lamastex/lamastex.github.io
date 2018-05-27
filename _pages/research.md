---
layout: single
title: Research
permalink: /research/
author_profile: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/DISP-research-1600x524.jpg
  caption: 
excerpt: 'At the interface of computing, mathematics and statistics.<br /><br /><br />'
---

Research at LaMaStEx is at the interdisciplinary interface of computing, mathematics and statistics. 
We use computer arithmetic and combinatorial data-structures through custom-built mathematical and statistical models to rigorously solve numerical optimization and simulation problems that arise in statistical decision-making from real-world data.

### Details of research: 

* [Curriculum Vitae](/cv/) for a field-specific picture
* [The full list of peer-reviewed publications](/publications/)
* [Research students supervised at LaMaStEx](/students/)
* [Mathematical Statistical Software](/software/)
* [Research Vision](/research_vision/)

### Current research projects in scalable data science

* [Project MEP: Meme Evolution Programme](https://lamastex.github.io/scalable-data-science/sds/research/mep/)

* [Project SAHDE: Scalable Adaptive Histogram Density Estimation](https://lamastex.github.io/scalable-data-science/sds/research/densityEstimation/sahde/)

<html>
  <head>
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
      google.charts.load('current', {packages:['wordtree']});
      google.charts.setOnLoadCallback(drawSimpleNodeChart);
      function drawSimpleNodeChart() {
        var nodeListData = new google.visualization.arrayToDataTable([
          ['id', 'childLabel', 'parent', 'size', 'weight'],
          [0, 'research', -1, 1, 0],
          [1, 'Comb. Stoch. Proc.', 0, 1, 1],
          [2, 'Data Sci.', 0, 5, 2],
          [3, 'Comp. Arith.', 0, 5, 3],

          [4, 'Behavioral Pedigree Proc.', 1, 3, 3],
          [5, 'Popn. Genomic Inference', 1, 3, 3],
          [6, 'Models of Meme evol.', 1, 3, 3],
          [7, 'Geospatial Lumped MC', 1, 3, 3],
          [8, 'Privacy-Preserv. Decisions', 1, 3, 3],

          [9, 'Nonparametric Stats', 3, 3, 0],
          [10, 'Tree Arithmetic', 3, 3, 0],
          [11, 'Geospatial Traj. Arith.', 3, 3, 2],

          [15, 'Scalable Tree Arith', 2, 5, 0],
          [13, 'SDS-2-2 Book', 2, 5, 0],
          [14, 'Consult. Combient', 2, 3, 0],

          [12, 'Open Meme Evol. Prog.', 2, 4, 3],
          [16, 'Scalable Multiv Hists', 2, 3, 0],

          [17, 'g+databricks:2.8Mkr', 12, 5, 10],
          [18, 'g+AWS:30Kkr 18', 12, 5, 10],
          [19, 'g-VR: Privacy Pres. Decs', 12, 5, 10],
          [20, 'g-VR: CALISTA', 11, 5, 10],
          [21, 'g-IL: TelAviv', 11, 5, 10],
          [22, 'g-Tw Health Metrics', 12, 2, 10]
]);

        var options = {
          maxFontSize: 14,
          wordtree: {
            format: 'explicit',
            type: 'suffix'
          }
        };

        var wordtree = new google.visualization.WordTree(
          document.getElementById('wordtree_explicit_maxfontsize'));
        wordtree.draw(nodeListData, options);
      }
    </script>
  </head>
  <body>
    <div id="wordtree_explicit_maxfontsize" style="width: 900px; height: 500px;"></div>
  </body>
</html>
