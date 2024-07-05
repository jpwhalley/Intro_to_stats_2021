These sessions provide an introduction to practical statistical methods
applied to genomics data, including data handling and quality control,
 dimension reduction, hypothesis testing and estimation, understanding
confidence intervals and dealing with multiple testing.

Learning Objectives
-------------------

-   Those who have less experience in Statistics, become confident in
    developing a hypothesis, choosing a test and implementing it to
    their data to find if significant or not.
-   Those who have less experience in working with biological datasets,
    get experience working with genotype data, gene expression data and
    raw experimental data from qPCR experiments.
-   Use of confidence intervals, what to use and how to assess them in
    reported research.
-   How to use dimension reduction methods to get an initial first look
    at the data
-   The perils of multiple testing and the methods to test significance
    when doing lots of tests.

Prerequisites
-------------

Please install the following suggested software:
------------------------------------------------

1.  [Anaconda3 (for python3
    notebooks)](https://www.anaconda.com/download/) with the following
    packages:
    -   adjusttext - can install using `pip install adjusttext`

2.  [R](https://www.r-project.org/) with the following packages:
    -   FactoMineR - `install.packages("FactoMineR")` and factoextra -
        `install.packages("factoextra")`
    -   pwr - `install.packages("pwr")`
    -   XGR:

<!-- -->

    if(!("BiocManager" %in% rownames(installed.packages()))) install.packages("BiocManager")BiocManager::install("remotes", dependencies=T)BiocManager::install("hfang-bristol/XGR", dependencies=T)

Data
----

-   Please contact me for the data used in e3\_dim\_reduction exercises.

Papers
------

-   P-values and the use of statistics:
    -   Comment: [Scientists rise up against statistical
        significance](https://www.nature.com/articles/d41586-019-00857-9)
    -   Editorial: [Moving to a World Beyond
        “p \< 0.05”](https://www.tandfonline.com/doi/full/10.1080/00031305.2019.1583913)
    -   Historical Commentary: [The Religion of Statistics as Practiced
        in Medical
        Journals](https://www.tandfonline.com/doi/abs/10.1080/00031305.1985.10479435)
-   Scientific fraud:
    -   Summary in press: [Surgisphere: governments and WHO changed
        Covid-19 policy based on suspect data from tiny US
        company](https://www.theguardian.com/world/2020/jun/03/covid-19-surgisphere-who-world-health-organization-hydroxychloroquine)
    -   Retracted NEJM article: [Cardiovascular Disease, Drug Therapy,
        and Mortality in
        Covid-19](https://www.nejm.org/doi/full/10.1056/NEJMoa2007621)
    -   Retracted Lancet article: [Hydroxychloroquine or chloroquine
        with or without a macrolide for treatment of COVID-19: a
        multinational registry
        analysis](https://doi.org/10.1016/S0140-6736(20)31180-6)
    -   Fraud in lower impact journals: [The Real Scandal About Ivermectin](https://www.theatlantic.com/science/archive/2021/10/ivermectin-research-problems/620473/)

[](https://github.com/jpwhalley/GMS_Stats_Course/tree/master/1_Introduction_to_Statistics#blocks)Blocks
-------------------------------------------------------------------------------------------------------

1 & 2: 22nd October 9.30am - 4pm,

3 & 4: 25th October November 10.30am - 4pm

1.  Tests of significance and correlations
2.  Dealing with uncertainty from raw experimental data and linear
    regression
3.  Big data sets and dimension reduction methods, multiple testing and
    power calculations
4.  Discussion of p-values, scientific fraud and misuse of methods.

 

[](https://github.com/jpwhalley/GMS_Stats_Course/tree/master/1_Introduction_to_Statistics#online-resources)Online Resources
---------------------------------------------------------------------------------------------------------------------------

-   [Python Tutorial](https://www.learnpython.org/)
-   [10 Minutes to
    Pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)
-   [Nature Methods Points of Significance
    Column](https://www.nature.com/collections/qghhqm/pointsofsignificance)
-   [Principal Component Methods in R: Practical
    Guide](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/112-pca-principal-component-analysis-essentials/#biplot)
-   [Power analysis in R](https://www.statmethods.net/stats/power.html)
