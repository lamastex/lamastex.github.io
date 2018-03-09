---
layout: single
title: Consulting for Combinet AB from Department of Mathematics, Uppsala University - 03/2017 - 2018
permalink: /consulting/industry/SE/CombientAB/CombientAB-MathsATUppsala
author_profile: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/DISP-research-1600x524.jpg
  caption: 
excerpt: 'At the interface of computing, mathematics and statistics.<br /><br /><br />'
---

# Brief Record of Indistrial Consulting 
### Industrially-aligned training and research

by Raazesh Sainudiin 

on Fri Mar  9 11:04:56 CET 2018, Stockholm, Sweden

supplements folder
* [supplements](/consulting/industry/SE/CombientAB/CombientAB-MathsATUppsala/)


# Abstract

This is a brief record of industrial consulting done by Raazesh Sainudiin for COmbient AB from the Department of Mathematics, Uppsala University. 

---
---

<html>
  <head>
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
      google.charts.load('current', {'packages':['timeline']});
      google.charts.setOnLoadCallback(drawChart);
      function drawChart() {
        var container = document.getElementById('timelineCountries');
        var chart = new google.visualization.Timeline(container);
        var dataTable = new google.visualization.DataTable();

        dataTable.addColumn({ type: 'string', id: 'rowID' });
        dataTable.addColumn({ type: 'string', id: 'annotation' });
        dataTable.addColumn({type:'string', role:'tooltip'}); 
        dataTable.addColumn({ type: 'date', id: 'Start' });
        dataTable.addColumn({ type: 'date', id: 'End' });
        dataTable.addRows([
          [ 'Data-Engineering', 'working with Alexey S', 'Alexey Siretskiy, Data Engineer from Combient AB (https://combient.com/) will be showing us how to build a small private bare-metal cluster on intel NUCs (http://www.intel.com/content/www/us/en/products/boards-kits/nuc.html) with Cobbler (http://cobbler.github.io/) automatically See the Meetup: https://www.meetup.com/Uppsala-Big-Data-Meetup/events/ckfktmywhbxb/', new Date(2017, 3, 1), new Date(2017, 6, 1) ],
          [ 'IN', 'Chennai', '',  new Date(1988, 8, 1), new Date(1991, 9, 1) ],

          [ 'Proposal April-June', 'Engineering Mathematics Assistants', 'Support for 2 X 10% of 30k sek / month for Engineering Mathematics Assistants Dan Lilija and Tilo Wiklund', new Date(1984, 8, 1), new Date(2018, 12, 31) ]
]);

    var options = {
        timeline: { colorByRowLabel: true, 
                    showRowLabels: true, groupByRowLabel: false, 
                    rowLabelStyle: {fontName: 'Arial', fontSize: 12 },
                     barLabelStyle: { fontName: 'Arial', fontSize: 10 } },
        avoidOverlappingGridLines: false
      };

      chart.draw(dataTable, options);
      }
    </script>
  </head>
  <body>
    <div id="timelineCountries" style="height: 1800px; width: 1000px;"></div>
  </body>
</html>

* **Data Engineering** lessons from Combient's ACE Data Engineering and Technology Teams 
  - tested HDP, local onpremise clusters
  - studied and experimented with various public/private cloud-agnostic code as service solutions
  - learnt about coding, software and research habits of data scientists and its possible effects on the rate of prototypung (devised a babling solution via Tilo Wiklund's [pinot](https://github.com/TiloWiklund/pinot))

* 
