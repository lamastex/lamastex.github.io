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
          [ 'Data-Engineering', '<a href="https://www.meetup.com/Uppsala-Big-Data-Meetup/events/ckfktmywhbxb/">working with AS</a>', 'Alexey Siretskiy, Data Engineer from Combient AB (https://combient.com/) will be showing us how to build a small private bare-metal cluster on intel NUCs (http://www.intel.com/content/www/us/en/products/boards-kits/nuc.html) with Cobbler (http://cobbler.github.io/) automatically See the Meetup: https://www.meetup.com/Uppsala-Big-Data-Meetup/events/ckfktmywhbxb/', new Date(2017, 3, 1), new Date(2017, 6, 1) ],
          [ 'IN', 'Chennai', '',  new Date(2017, 6, 1), new Date(2017, 9, 1) ],
          [ 'AIM-Day Prep', 'working with JEG and HP', '',  new Date(2017, 6, 1), new Date(2017, 9, 1) ],

          [ 'Proposal April-June 2018', 'Engineering Mathematics Assistants', 'Support for 2 X 10% of 30k sek / month for Engineering Mathematics Assistants Dan Lilija and Tilo Wiklund', new Date(2018, 4, 1), new Date(2018, 6, 1) ]
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

* **Data Engineering Science** Exchangees between Combient's ACE Data Engineering and Technology Teams and Department of Mathematics, Uppsala University
  - tested HDP, local onpremise clusters 
  - studied and experimented with various public/private cloud-agnostic code as service solutions
  - industry-academia know-how exchange via:
    - <a href="https://www.meetup.com/Uppsala-Big-Data-Meetup/events/237468053/">Launching Uppsala Big Data Meetup</a> 
      - jointly sponsored by Department of Mathematics, Uppsala University (meeting space) and Combient AB (AV equipment and fika support)
      - at present (March 2018) there are 3 organizers, 261 Members and 43 Past Meetups
    - <a href="https://www.meetup.com/Uppsala-Big-Data-Meetup/events/ckfktmywhbxb/">Industry to Academia: Uppsala Big Data Meetup, May 18, 2017, 6:15 PM to 9:15 PM</a> (<a href="https://www.meetup.com/Uppsala-Big-Data-Meetup/photos/27880958/">photos</a>)
    - <a href="https://www.meetup.com/Uppsala-Big-Data-Meetup/events/246990409/">Academia to Industry: Uppsala Big Data Meetup, Friday, January 26, 2018, 4:00 PM to 10:00 PM</a> (<a href="https://www.meetup.com/Uppsala-Big-Data-Meetup/photos/28160675/#468523477">photos</a>)
  - <a href="https://lamastex.github.io/scalable-data-science/sds/basics/infrastructure/onpremise/">Concrete *solutions* for data science prototyping environment</a> that directly leads to a *productizable data science process*
    - <a href="https://lamastex.github.io/scalable-data-science/sds/basics/infrastructure/onpremise/NUCcluster/">Building NUC Cluster, by Alexey Siretskiy, Data Engineer, Combient AB</a>
    - <a href="https://lamastex.github.io/scalable-data-science/sds/basics/infrastructure/onpremise/rootless/">Installing Spark-Hadoop-Yarn-Hive-Zeppelin without Root Access, by Dan Lilja, PhD Student, Department of Mathematics, Uppsala University</a>
    - <a href="https://lamastex.github.io/scalable-data-science/sds/basics/infrastructure/onpremise/setups/">Networking/OS Setups for your On-Premise Cluster of Computers by Tilo Wiklund, PhD Student, Department of Mathematics, Uppsala University</a>
    - <a href="PhD Student in Mathematics, Uppsala University">How to BASH your own Spark-Yarn-HDFS cluster? by Benny Avelin, Data Scientist, Combient AB</a>
  - learnt about coding, software and research habits of data scientists and its possible effects on the rate of prototypung 
    - devised an inter-notebook babling *solution* via Tilo Wiklund's [pinot](https://github.com/TiloWiklund/pinot)

* 
