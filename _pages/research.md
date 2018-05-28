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

          [9, 'MRS2 Stat. Set Proc.', 3, 3, 0],
          [10, 'Tree Arithmetic', 3, 3, 0],
          [11, 'Geospatial Traj. Arith.', 10, 3, 2],

          [23, 'g+EU-MarieCurieAct:2.9Mkr', 3, 3, 2],


          [15, 'Scalable Tree Arith', 2, 5, 0],
          [13, 'SDS-2-2 Book', 2, 5, 0],
          [14, 'Consult. Combient', 2, 3, 0],

          [12, 'Open Meme Evol. Prog.', 2, 4, 3],
          [16, 'Scalable Multiv Hists', 2, 3, 0],

          [17, 'g+databricks:2.2Mkr', 12, 5, 10],
          [18, 'g+AWS:30Kkr 18', 12, 5, 10],
          [19, 'g-VR: Privacy Pres. Decs', 12, 5, 10],
          [20, 'g-VR: CALISTA', 11, 5, 10],
          [21, 'g-IL: TelAviv', 11, 5, 10],
          [22, 'g-Tw Health Metrics', 12, 2, 10],


          [23, 'JohnÖsth@kultgeog.uu', 20, 5, 10],
          [24, '', 20, 5, 10],
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

## Grants and research Collaborators

### Research Grants Won for in 2018-2025

- 27Kkr: AWS Cloud Computing Credits for Research for Monitoring SE 2018 Election
  - Main Applicant with primary co-applicant:
    - <a href="http://katalog.uu.se/profile/?id=N96-202_1">Mattias Gardell</a>, Professor at <a href="http://katalog.uu.se/organisation/?orgId=X256">Centre for Multidisciplinary Studies on Racism</a> and <a href="http://katalog.uu.se/organisation/?orgId=RF1:6">Department of Theology, History of Religions and The Social Sciences of Religion; History of Religions</a>, Faculty of Theology, Uppsala University

- 2.2Mkr: databricks Academic Research Partnership for effectively unlimited professional databricks computing units for data science and engineering research 
  - Main Applicant (projected for Meme Evolution Programme research and PhD student training until 2025)
  - Allowed my past and current MSc and candidate thesis/research students to do big data research at zero cost
    - (main output submitted to <a href=""></a>) Rejecting the Null Hypothesis of Apathetic Retweeting of US politicians and SPLC-defined Hate Groups in the 2016 US Presidential Election, Raazesh Sainudiin, Kumar Yogeeswaran, Kyle Nash and Rania Sahioun, 8 pages, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180423_NullApatheticRetweetOfUSPolitsHategrps.pdf">PDF</a> 448KB)

- 26Kkr: Esseen Research Grant for Nonparametric Density Estimators with Universal Performance Guarantees
  - Main Applicant for research visits/presentations
    - (submitted to <a href="http://scan2018.oishi.info.waseda.ac.jp/">The 18th International Symposium on Scientific Computing, Computer Arithmetic, and Verified Numerical Computations, Sep 10-15, 2018, Tokyo</a>) *Exact Bayesian A/B testing using distributed fault-tolerant Moore rejection sampler*, Benny Avelin and Raazesh Sainudiin, Extended Abstract, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180507_ABTestingViaDistributedMRS.pdf">PDF</a> 104KB)
    - (submitted to <a href="http://www.ir.disco.unimib.it/sum2018/">The 12th International Conference on Scalable Uncertainty Management – Milan, Italy, Oct 3-5, 2018</a>) *Scalable Multivariate Histograms*, Raazesh Sainudiin and Tilo Wiklund, 14 pages, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180506_SparkDensityTree.pdf">PDF</a> 800KB)
    - (submitted to ACM Transactions) *Minimum distance estimation with universal performance guarantees over statistical regular pavings*, Raazesh Sainudiin and Gloria Teng, 17 pages, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180405_MDEYatracosThis.pdf">PDF</a> 708KB)
    - *Extending arithmetic to hyper-plane split trees for nonparametric density estimators with L1 and L2 losses* with <a href="http://luc.devroye.org/">Professor Luc Devroye</a>,  School of Computer Science, McGill University, Montreal, Canada (also the primitive operation underlying Neural Networks) 


### Research Grants Applied for in 2018-2024

- 14.9Mkr: VR Research Environment Grant (Migration and Integration); Integration in a mobile society, modelling and analysing how everyday mobility is shaping the potential for integration
  - Co-Applicant with main applicant <a href="http://www.kultgeog.uu.se/kontakt/personal/John_Osth/">John Östh, Department of Cultural and Economic Geography, Uppsala University</a>
- 29Mkr: VR Research Environment Grant (Interdisciplinary Research);
  - Main Applicant with some of the following participating researchers:
    - <a href="https://katalog.uu.se/profile/?id=N3-955">Anna Sara-Lind</a>, Professor of Public Law at the Faculty of Law, Uppsala University
    - <a href="http://www.kultgeog.uu.se/kontakt/personal/John_Osth/">John Östh</a>, Associate Professor, Department of Cultural and Economic Geography, Uppsala University
    - <a href="http://www.cmap.polytechnique.fr/~gaiffas/">Stéphane Gaïffas</a>, Professeur, Laboratoire de Probabilités et Modèles Aléatoires, Université Paris Diderot, Paris, France 
    - <a href="http://www.cmap.polytechnique.fr/~veber/">Amandine Veber</a>, CNRS Researcher, Centre de Mathématiques Appliquées, École Polytechnique, Palaiseau, France
- 4.8Mkr: Twitter Health Metrics Research; *Scalable Markov Kernels from Twitterverse to the GDELT Project*
  - Main Applicant (20% + 1 PhD student for 5 years)
