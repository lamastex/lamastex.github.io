---
layout: single
title: Research and Available Student Projects
permalink: /research/
author_profile: true
sidebar:
  nav: "lMenu"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/DISP-research-1600x524.jpg
  caption: 
excerpt: 'At the interface of computing, mathematics and statistics.<br /><br /><br />'
---
{% include toc %}

# Research Overview 

Research at LaMaStEx is at the interdisciplinary interface of computing, mathematics and statistics. 
We use computer arithmetic and combinatorial data-structures through custom-built mathematical and statistical models to rigorously solve numerical optimization and simulation problems that arise in statistical decision-making from real-world data.

* [Curriculum Vitae](/cv/) for a field-specific picture
* [The full list of peer-reviewed publications](/publications/)
* [Research students supervised at LaMaStEx](/students/)
* [Mathematical Statistical Software](/software/)

# Available Student Projects

Current student research projects involve a mixture of skills from mathematics, computer science, statistics, data engineering and data science.
Therefore, finding a suitable project of mutual interest given the acquirable skillset requires some discussions. 

Here is a list of student project proposals of current interest.
It is meant as a guide for a student or a small group of students who are interested in being guided by Raazesh Sainudiin for their individual or group project in a course of study or research at Uppsala University. 
These projects may help student(s) decide if they would like to do a Bachelor's thesis, Masters thesis (exjobb), or pursue other research and development possibilities with Raazesh Sainudiin at the Department of Mathematics, Uppsala University.

The exact nature and pathway towards a project will depend on your current knowledge and skills and your willingness to acquire them. A *subset* of the following skills is needed for each project. We can make a self-study pathway specifically for you and the project.

1. **Software Skills:** docker, docker-compose, git, sbt, maven, c/g/make, etc.
2. **Programming Languages:** Python, Scala, Haskell, C, C++, R, Rust, Javascript,   
3. **Mathematical and Statistical Background:** Probability, Graphs, Algebra, Analysis, Optimization, ML models, etc.
4. **Computing Skills:** system administration, distibuted computing, high-performance computing, etc.

## GDELT Project

The [GDELT project](https://www.gdeltproject.org/) has many possibilities depending on your interests and abilities.

- Applied Digital Humanities: Learn basic SQL and GQL to be able to work in a delta lake house with GDELT data with the aim of providing useful insights to researchers in [digital humanities](https://www.abm.uu.se/cdhu-eng). See the following libraries to appreciate some of the possibilities:
  - First familiarize with [spark-gdelt](https://github.com/lamastex/spark-gdelt) and see some [example analytics](https://github.com/lamastex/spark-gdelt-examples).
  - **GDELT PSL project:** Learn [PSL](https://psl.linqs.org/) and apply it to GDELT data extract.
  - **GDELT GQL project:** Learn Graph Query Language and apply it to GDELT data to provide insights for digital humanities researchers (may want to work closely with such researchers).
  - **GDELT Interact project:** Develop an interactive UX for an analyst interested in interacting with details of SQL and GQL queries. This project requires experience in full-stack development in a team of 3 to 4 students.
  - Other projects based on the GDELT data.

## Financial Streams Project

Using multiple time series of financial stock market data, 
develop further from [trend-calculus](https://github.com/lamastex/spark-trend-calculus) streams of them. The development can be along predictive fronts using appropriate ML models or involve estimators by extending [these examples](https://github.com/lamastex/spark-trend-calculus-examples). 
The general idea would be to identify recurrent multivariate signals of interest in the trends of historical financial data. 

## Meme Evolution in Twitterverse Project

Using twitter experiments with [Project MEP](https://github.com/lamastex/mep) there are many posibilities here. The projects can focus 

- purely on the data engineering side involving [terraform.io](https://www.terraform.io/) by extending the infrastructure as code work started [here](https://github.com/lamastex/mep/tree/main/infra/tf), or 
- on analytic and mathematical modeling side comparing the [polarised state of the Swedish political twitterverse](http://lamastex.org/preprints/20190830_PolarisedMEPSverige.pdf) from last Swedish election to a new collection that can be started this Semester, or
- refine and extend the interactive visual investigations developed in [twitterVisualizations](https://github.com/lamastex/twitterVisualizations) or 
- extend distributed algorithms to characterize the evolution of ideological networks in the Twitterverse (see [this statistical application](https://doi.org/10.1007/s13278-019-0567-9) for example).

## Scalable Density Estimators Project

This project is suitable for a student of mathematics with skills in functional programming over a distributed computing architecture (or one who can self-learn such skills). To appreciate the starting point of this advanced project read [this paper](https://arxiv.org/abs/2012.14847) and try out [this Scala Spark library](https://gitlab.com/tilowiklund/distributed-histogram-trees) with a view towards implementing the algorithms in [this paper](http://interval.louisiana.edu/reliable-computing-journal/volume-16/reliable-computing-16-pp-252-282.pdf) using the Scala Spark library.

## Notebook-Format-Agnostic Data Engineering Science Project

This is for a small group of 2-4 engineering students who collectively have skills spanning Haskell to be able to use [pinot](https://gitlab.com/tilowiklund/pinot/), docker-compose or Kubernetes to provision [Apache Spark](https://spark.apache.org/) clusters in its modern ecosystem with [zeppelin](https://zeppelin.apache.org/) and [jupyter](https://jupyterhub.readthedocs.io/en/stable/index.html) notebooks servers. The objective of this project is to allow for *notebook-format-agnostic* data science and analytics. Cloud computing across onpremise and public clouds is a pre-requiste.

## Other Projects

There are several other project possibilities. However, this depends on current research interests and coming up with a reasonable plan. Please go through [Selected Publications by Field](https://lamastex.github.io/cv/#selected-publications-by-field) to propose other project ideas spanning across population genetics, computer-aided proofs, mobility science, etc.

<!--
* [Project MEP: Meme Evolution Programme](https://lamastex.github.io/scalable-data-science/sds/research/mep/)

* [Project SAHDE: Scalable Adaptive Histogram Density Estimation](https://lamastex.github.io/scalable-data-science/sds/research/densityEstimation/sahde/)


# Research Vision and Grants

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


## Most Important Contributions to Research & Current Directions

### Mathematical Statistical Combinatorial Stochastic Processes & Data Science

- Ancestries of a Recombining Diploid Population, Raazesh Sainudiin, Bhalchandra Thatte, and Amandine V&eacute;ber, Journal of Mathematical Biology, Volume 72, Issue 1, pp 363-408, 2016 (preprint <a class="linkitem" href="http://lamastex.org/preprints/20150322_combinedARG_JMB.pdf">PDF</a> 436KB). The final publication is available at Springer via <a class="linkitem" href="http://dx.doi.org/10.1007/s00285-015-0886-z">10.1007/s00285-015-0886-z</a>
  - *Towards unifying behavioural ecology and population genetics* (started collaboration with <a href="https://katalog.uu.se/profile/?id=N13-1883">Elisabeth Bolund</a>, Assistant Professor at <a href="https://katalog.uu.se/organisation/?orgId=X137:5">Department of Ecology and Genetics, Animal Ecology</a>, Uppsala University, *on sexually dimorphic nematodes under selection*)
- Experiments with the Site Frequency Spectrum, Raazesh Sainudiin, Kevin Thornton, Jennifer Harlow, James Booth, Michael Stillman, Ruriko Yoshida, Robert Griffiths, Gilean McVean and Peter Donnelly, <a class="linkitem" href="http://www.springerlink.com/content/0748966716753484/">Inaugural Issue in Algebraic Biology, Bulletin of Mathematical Biology, Volume 73, Number 4, 829-872</a>, 2011 (<a class="linkitem" href="http://lamastex.org/preprints/AMSReviewOfSFSExperiments2011.pdf">AMS review</a>)
  - *Towards general lumped controlled Markov processes* (basis for privacy-preserving decision procedures with social-media and geospatial trajectory data with others at UU as explained below)
  - *Towards distributed computing algorithms for Population Genomic Inference* with Veber (Paris) and EEB-based Pop-gen group (early stages; journal-clubs, 360-in-525-05 population genomics and big data course, etc.)
- The Transmission Process: A Combinatorial Stochastic Process for the Evolution of Transmission Trees over Networks, Raazesh Sainudiin and David Welch, Journal of Theoretical Biology, Volume 410, Pages 137–170, <a class="linkitem" href="http://dx.doi.org/10.1016/j.jtbi.2016.07.038">10.1016/j.jtbi.2016.07.038</a>, 2016. See research project: <a class="linkitem" href="https://lamastex.github.io/scalable-data-science/sds/research/mep/">Meme Evolution Programme</a>
  - *Towards SIR/SIS models, Population Ideological Forests in Twitter, and their Dynamic models* (much harder problems; joint work with Veber and Gaiffas in Paris) 

### Computer Arithmetic & Data Science

- Mapped Regular Pavings, Jennifer Harlow, Raazesh Sainudiin and Warwick Tucker, <a class="linkitem" href="http://interval.louisiana.edu/reliable-computing-journal/volume-16/reliable-computing-16-pp-252-282.pdf">Reliable Computing, vol. 16, pp. 252-282</a>, 2012 (<a class="linkitem" href="http://lamastex.org/preprints/MappedRegularPaving.pdf">PDF</a> 972KB)
- Minimum distance estimation with universal performance guarantees over statistical regular pavings, Raazesh Sainudiin and Gloria Teng, 17 pages, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180405_MDEYatracosThis.pdf">PDF</a> 708KB)
  - *Towards Scalable (big data friendly) variants that can be used in real-world industry-scale problems (Anamoly Detection, Predictive Maintenance, etc.)* (working with Tilo Wiklund, Maths@UU and Warwick Tucker on arithmetical aspects; got three submissions of applications relevant to Combient AB, Stockholm)
  - *Towards Privacy-Preserving Tree Arithmetics for geospatial trajectories*

## Grants and Research Collaborators - Next 5-6 years

### Research Grants Concluded in 2017

- 245Kkr/2.95Mkr: EU Marie Curie Actions People (Co-applicant with countepart funding from Royal Society of NZ) on Project CORCON: Correctness by Construction (30% rsrch)
  - main output: 
    - MRS 2.0: A C++ Class Library for Statistical Set Processing and Computer-Aided Proofs in Statistics (Version 2.0) [Software], Available from <a class="linkitem" href="https://github.com/lamastex/mrs2">https://github.com/lamastex/mrs2</a>, 2017

### Research Grants Won in 2017-2018 for 2018-2025

- 27Kkr: AWS Cloud Computing Credits for Research for *Ethnographically-designed Experiments to Monitor SE 2018 Election in Twitter*
  - Main Applicant with primary co-applicant:
    - <a href="http://katalog.uu.se/profile/?id=N96-202_1">Mattias Gardell</a>, Professor at <a href="http://katalog.uu.se/organisation/?orgId=X256">Centre for Multidisciplinary Studies on Racism</a> and <a href="http://katalog.uu.se/organisation/?orgId=RF1:6">Department of Theology, History of Religions and The Social Sciences of Religion; History of Religions</a>, Faculty of Theology, Uppsala University

- 2.2Mkr: databricks Academic Research Partnership for effectively unlimited professional databricks computing units for data science and engineering research (including *Monitoring and Analysis of SE 2018 Election in Twitter against GDELT project*)
  - Main Applicant (projected for Meme Evolution Programme research and PhD student training until 2025)
  - Allowed my past and current MSc and candidate thesis/research students to do big data research at zero cost
    - (main output submitted to <a href="http://asonam.cpsc.ucalgary.ca/2018/index.php">The 2018 IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining, Barcelona Spain, Aug 28-31, 2018</a>) Rejecting the Null Hypothesis of Apathetic Retweeting of US politicians and SPLC-defined Hate Groups in the 2016 US Presidential Election, Raazesh Sainudiin, Kumar Yogeeswaran, Kyle Nash and Rania Sahioun, 8 pages, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180423_NullApatheticRetweetOfUSPolitsHategrps.pdf">PDF</a> 448KB)

- 26Kkr: Esseen Research Grant for Nonparametric Density Estimators with Universal Performance Guarantees
  - Main Applicant for research visits/presentations (100% rsrch 3-4 weeks in term 1 2018)
    - (submitted to <a href="http://scan2018.oishi.info.waseda.ac.jp/">The 18th International Symposium on Scientific Computing, Computer Arithmetic, and Verified Numerical Computations, Sep 10-15, 2018, Tokyo</a>) *Exact Bayesian A/B testing using distributed fault-tolerant Moore rejection sampler*, Benny Avelin and Raazesh Sainudiin, Extended Abstract, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180507_ABTestingViaDistributedMRS.pdf">PDF</a> 104KB)
    - (submitted to <a href="http://www.ir.disco.unimib.it/sum2018/">The 12th International Conference on Scalable Uncertainty Management – Milan, Italy, Oct 3-5, 2018</a>) *Scalable Multivariate Histograms*, Raazesh Sainudiin and Tilo Wiklund, 14 pages, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180506_SparkDensityTree.pdf">PDF</a> 800KB) -- *industry-scale big data ready!*
    - (submitted to ACM Transactions) *Minimum distance estimation with universal performance guarantees over statistical regular pavings*, Raazesh Sainudiin and Gloria Teng, 17 pages, 2018 (<a class="linkitem" href="http://lamastex.org/preprints/20180405_MDEYatracosThis.pdf">PDF</a> 708KB)
    - (new direction): *Extending arithmetic to hyper-plane split trees for nonparametric density estimators with L1 and L2 losses* with <a href="http://luc.devroye.org/">Professor Luc Devroye</a>,  School of Computer Science, McGill University, Montreal, Canada (also the primitive operation underlying Neural Networks) 

### Research-led Teaching Grants Won in 2017-2018

- 80Kkr: <a href="https://lamastex.github.io/scalable-data-science/sds/2/2/">Inter-Faculty Courses in Data Sciences for PhD students across TekNat Faculty (Fall 2017)</a>
- 60Kkr: <a href="https://lamastex.github.io/scalable-data-science/360-in-525/2018/">CIM Sponsored Courses in Data Sciences (Spring 2018; Total of 10 full-day Bootcamp-Style Courses)</a>
- 20Kkr: Combinet AB and SEB - fika support for the above courses
- Uppsala University is an AWS Academy Partner Institution (Main Applicant and UU's Main PoC): Allows each student and each faculty to spend 200-500 USD of cloud computing credits for free on AWS per year
- databricks academic partnership grant has been used to develop course content and for student research projects 

### Research Grants Applied for in 2018-2024 (waiting on decision)

- 14.9Mkr: VR Research Environment Grant (Migration and Integration); *Integration in a mobile society, modelling and analysing how everyday mobility is shaping the potential for integration*
  - Co-Applicant with main applicant <a href="http://www.kultgeog.uu.se/kontakt/personal/John_Osth/">John Östh, Department of Cultural and Economic Geography, Uppsala University</a> (20% rsrch + 1 PhD)
- 29Mkr: VR Research Environment Grant (Interdisciplinary Research); *Privacy-preserving Decisions from Social Media Communications and Geo-spatial Movements of a Sovereign European Population*
  - Main Applicant with some of the key participating researchers (40% rsrch + 4 PhDs):
    - <a href="https://katalog.uu.se/profile/?id=N3-955">Anna Sara-Lind</a>, Professor of Public Law at the Faculty of Law, Uppsala University
    - <a href="http://www.kultgeog.uu.se/kontakt/personal/John_Osth/">John Östh</a>, Associate Professor, Department of Cultural and Economic Geography, Uppsala University
    - <a href="http://www.cmap.polytechnique.fr/~gaiffas/">Stéphane Gaïffas</a>, Professeur, Laboratoire de Probabilités et Modèles Aléatoires, Université Paris Diderot, Paris, France 
    - <a href="http://www.cmap.polytechnique.fr/~veber/">Amandine Veber</a>, CNRS Researcher, Centre de Mathématiques Appliquées, École Polytechnique, Palaiseau, France
- 4.8Mkr: Twitter Health Metrics Research; *Scalable Markov Kernels from Twitterverse to the GDELT Project*
  - Main Applicant (20% rsrch + 1 PhD)
- 2.9Mkr: Research grant jointly with Blavtnik Interdisciplinary Cyber Research Center, a Telecom Company and Tel Aviv University, Israel *Mobile Phone Data for Society and Privacy for the Individual: From the Conflict to a Synergy in Transport Flows Analysis*
  - Co-PIs with Professors Itzhak Benenson and Itzhak Omer, Porter School of Environment and Geoscience, Faculty of Exact Sciences, Tel Aviv University (10% rsrch + 1 PhD co-supervision)
-->
