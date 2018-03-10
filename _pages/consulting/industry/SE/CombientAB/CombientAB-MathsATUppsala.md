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

# Brief Record of Industrial Consulting 
## Emphasizing Industrially-aligned training and research

by Raazesh Sainudiin 

on Fri Mar  9 11:04:56 CET 2018, Stockholm, Sweden


# Abstract

This is a brief record of industrial consulting done by Raazesh Sainudiin for Combient AB from the Department of Mathematics, Uppsala University. 

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
          [ 'Data Engineering Science', 'working with data scientists and engineers in academia and industry','', new Date(2017, 3, 1), new Date(2018, 4, 1) ],
          [ 'Data Science', 'working with Combient data scientists and creating course content', '',  new Date(2017, 6, 1), new Date(2018, 4, 1) ],
          [ 'Various Other Activities', 'working on various technical and non-technical aspects of the data science process', 'AIM Day with HP and JEG, BA and HP on data science publicly knwon algorithms, etc',  new Date(2017, 6, 1), new Date(2018, 4, 1) ],

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
    <div id="timelineCountries" style="width: 1000px;"></div>
  </body>
</html>

# Data Engineering Science
## Academia-Industry Cooperation and Feedback Loops 
Exchanges between Combient's ACE Data Engineering and Technology Teams and Department of Mathematics, Uppsala University
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
    - <a href="https://lamastex.github.io/scalable-data-science/sds/basics/infrastructure/onpremise/bashSparkCluster/">How to BASH your own Spark-Yarn-HDFS cluster? by Benny Avelin, Data Scientist, Combient AB</a>
  - learnt about coding, software and research habits of data scientists and its possible effects on the rate of prototypung 
    - devised an inter-notebook babling *solution* via Tilo Wiklund's [pinot](https://github.com/TiloWiklund/pinot)

* Public Cloud Integration Efforts and Continuous Training
  - Uppsala University succeessfully accepted as an [AWS Educate](https://aws.amazon.com/education/awseducate/) Partner Institution ([list of AWS Educate Partner Institutions](https://s3.amazonaws.com/awseducate-list/AWS_Educate_Institutions.pdf))
    - this allows aws-spinnable clusters for **any** Uppsala University student or faculty - ideal for labs in the public cloud
  - Databricks Academic Partnership allows couses in data science in a cloud-free manner
  - Close ties and complementary efforts with Uppsala's Applied Cloud Computing Group (to minimize course overlap and maximize complementation)
  - Maths Dept at UU and Combient AB jointly sponsored training 
    - AWS Certified Instructor for Cloud Architecture Course in Dublin, 2017  
    - DL/AI Workshop by Databricks at EU Spark Summit in Dublin, 2017

# Data Science
## Inter-Faculty Course in data Sciences
  - Application succeeds with 80,000 sek from Division of Technical and Natural Sciences at UU plus support from: 
    - Department of Mathematics, Uppsala University
    - Combient AB, for technical feedback and fika support for students 
  - This leads to the development of two data science courses amicably called [Scalable Data Science from Atlantis, A Big Data Course in Apache Spark 2.2](https://lamastex.github.io/scalable-data-science/sds/2/2/) 
    - see the [github repository](https://github.com/lamastex/scalable-data-science/) (43 stars, 38 forks and 15 contributors by March 2018)
    - see the [gitbook of a subset of the content](https://www.gitbook.com/book/lamastex/sds-2-2/details) 
  - [See](https://youtu.be/zloLA6AyNqk?list=PL_I1mOIPmfpawQcs9l1vYfh50RhK_UJfY&t=2530) Combient Data Engineer introducing Combient to students on the first day
  - The syllabus is interactively designed with weekly input from Combient AB'a current data science needs, examples include: 
    - Deep Learning and AI (after being trained at EU Spark Summit in Dublin - jointly sponsored by Combient and Maths Dept at UU), 
    - Structured Streaming for Anomaly Detection via t-digest sketching, etc.
    - Scalable Geopspatial Analytics for spatio-temporal trajectory analytics
  - GOAL: Train students for immediate summer intership placements; see example student projects at the end of course
    - [Network anomaly detection: Student Project by Victor Ingman and Kasper Ramström](https://lamastex.github.io/scalable-data-science/sds/2/2/db/999_01_StudentProject_NetworkAnomalyDetection/)    - five projects were done in areas including power forecasting, twitter experimantal designs and NLP, population genomics on the 1000 human genomes project, etc. 

# Proposal

Pitch - minimal funding to quickly roll out *Full-day Workshops in Data Science and Engineering by Combient AB and Department of Mathematics, Uppsala University* (after June 2 2018).

- Build from [360-in-525 Minutes Course Set in Data Sciences, Spring 2018 - starting **April 20 2018**](https://lamastex.github.io/360-in-525/) - jointly sponsored by Centre for Interdisciplinary Mathematics and Department of Mathematics, Uppsala University -- scalable geospatial analytics, digital humanities and global news feed processing, population genomics towards personalized medicine, etc. 

### Request
By supporting two secifically skilled Engineering Mathematics Assistants (Dan Lilja and Tilo Wiklund) at 10% of their PhD student salary from **April 1 - June 1 2018** one can generate content for training data scientists for specific needs of various Swedish industries. 

Need support from industry to take advantage of the momentum we have built up since March 2017!

**Deliverable:** Full-day Workshop Packages that can be remotely or directly done by those at Maths Department or data scientists at Combient for **continual training of data scientists in the co-owner circle**.

## supplements folder

* [supplements](/consulting/industry/SE/CombientAB/CombientAB-MathsATUppsala/)

