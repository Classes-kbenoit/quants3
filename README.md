-   [Quantitative Methods 3: Data Mining and Statistical Learning](#quantitative-methods-3-data-mining-and-statistical-learning)
    -   [Overview](#overview)
    -   [Objectives](#objectives)
    -   [Important Specifics](#important-specifics)
        -   [Computer Software](#computer-software)
        -   [Main Texts](#main-texts)
        -   [Instructions for Submitting Homeworks](#instructions-for-submitting-homeworks)
        -   [Instructions for use of course materials](#instructions-for-use-of-course-materials)
    -   [Course Schedule](#course-schedule)
        -   [***Monday, 23 January: Introduction to the data science approach***](#monday-23-january-introduction-to-the-data-science-approach)
        -   [***Monday, 6 February: Rethinking regression as a predictive tool***](#monday-6-february-rethinking-regression-as-a-predictive-tool)
        -   [***Monday, 20 February: Introduction to machine learning***](#monday-20-february-introduction-to-machine-learning)
        -   [***Monday, 6 March: Unsupervised learning and dimensional reduction***](#monday-6-march-unsupervised-learning-and-dimensional-reduction)
        -   [***Monday, 20 March: Text analysis***](#monday-20-march-text-analysis)
    -   [Assessment](#assessment)
        -   [TBA](#tba)

Quantitative Methods 3: Data Mining and Statistical Learning
============================================================

**Department of Political Science, Trinity College Dublin, HT 2017**

[Kenneth Benoit](kbenoit@tcd.ie)

This repository contains the class materials for Quantitative Methods 3: Data Mining and Statistical Learning taught in Hillary Term 2017 by Kenneth Benoit.

The class meets Mondays for five sessions, every other Monday, starting 23 January 2017. Times: 12:00 - 15:00.

Overview
--------

Data Mining and Statistical Learning are exciting new areas that combine scientific inquiry, statistical knowledge, substantive expertise, and computer programming. Good data science requires experts that combine substantive knowledge with data analytical skills, which makes it a prime area for social scientists with an interest in quantitative methods. This course integrates prior training in quantitative methods (statistics) and coding with substantive expertise and introduces the fundamental concepts and techniques of data mining and statistical learning. Examples focus on political science and methods are tailored to areas that are useful for political science research.

Objectives
----------

This course aims to provide an introduction to the data science approach to the quantitative analysis of data using the methods of statistical learning, an approach blending classical statistical methods with recent advances in computational and machine learning. We will cover the main analytical methods from this field with hands-on applications using example datasets, so that students gain experience with and confidence in using the methods we cover. We also cover data preparation and processing, including working with structured databases, key-value formatted data (JSON), and unstructured textual data. At the end of this course students will have a sound understanding of the field of data science, the ability to analyse data using some of its main methods, and a solid foundation for more advanced or more specialised study.
The course will be delivered through a combination of lectures and guided learning through detailed weekly assignments to be completed outside of class.

Important Specifics
-------------------

### Computer Software

Computer-based exercises will feature prominently in the course, especially in the lab sessions. The use of all software tools will be explained in the sessions, including how to download and install them. All of the class work will be done using R, using publicly available packages.

### Main Texts

The primary texts are:

-   James et al. (2013) *An Introduction to Statistical Learning: With applications in R*, Springer. Note: The book is available from the authors' page [here](http://www-bcf.usc.edu/~gareth/ISL/).
-   Garrett Grolemund and Hadley Wickham (2016) *R for Data Science*, O'Reilly Media. Note: Online version is available from the authors' page [here](http://r4ds.had.co.nz/index.html).
-   Zumel, N. and Mount, J. (2014). *Practical Data Science with R*. Manning Publications.

The following are supplemental texts which you may also find useful:

-   Lantz, B. (2013). *Machine Learning with R*. Packt Publishing.
-   Lesmeister, C. (2015). *Mastering Machine Learning with R*. Packt Publishing.
-   Conway, D. and White, J. (2012) *Machine Learning for Hackers*. O'Reilly Media.
-   Leskovec, J., Rajaraman, A. and Ullman, J. (2011). *Mining of Massive Datasets*. Cambridge University Press.
-   Zafarani, R., Abbasi, M. A. and Liu, H. (2014) *Social Media Mining: An introduction*. Cambridge University Press.
-   Hastie et al. (2009) *The Elements of Statistical Learning: Data mining, inference, and prediction*. Springer. Note: The book is available from the authors' page [here](http://statweb.stanford.edu/~tibs/ElemStatLearn/).
-   Garrett Grolemund and Hadley Wickham (2016) *R for Data Science*, O'Reilly Media, Chapters 1-3. Note: Online version is available from the authors' page [here](http://r4ds.had.co.nz/index.html).

### Instructions for Submitting Homeworks

Each homework will be a single file in the [RMarkdown](http://rmarkdown.rstudio.com) format. The files linked below are *named very carefully*, to make it easy for us to identify your completed lab assignments.

1.  Obtaining the starter files.

    Each day below will link the name of a starter file for you to download and work with. These are in the RMarkdown format. You should embed your answers, with code, into your version of the instruction files.

    To help learn this, I suggest you look at the following resources:

    -   Downloading and installing [RStudio](http://www.rstudio.com) and [R](https://cran.r-project.org) on your computer.
    -   Data Camp [R Markdown tutorials](https://www.datacamp.com/courses/reporting-with-r-markdown), first chapter.

2.  Renaming the starter files.

    For example, the first assignment file is named `quant3_assignment1_LASTNAME_FIRSTNAME.Rmd`, which you will need to rename by replacing the uppercase terms with your own last and first names, e.g. `quant3_assignment1_Bloggs_Joe.Rmd`.

3.  From RStudio, you can create an HTML output file with your evaluated code, figure, and text answers by clicking the "Knit HTML" button in the top of the editor pane in RStudio. The resulting HTML file will be saved in your working directory.

4.  You will need to email the completed file to me at <kbenoit@tcd.ie>.

Don't worry if it seems complicated the first time. This sort of careful workflow process and file management is part of learning practical data science too.

### Instructions for use of course materials

You have three options for downloading the course material found on this page:

1.  You can download the materials by clicking on each link.

2.  You can "clone" repository, using the buttons found to the right side of your browser window as you view this repository. This is the button labelled "Clone in Desktop". If you do not have a git client installed on your system, you will need to [get one here](https://git-scm.com/download/gui) and also to make sure that [git is installed](https://git-scm.com/downloads). This is preferred, since you can refresh your clone as new content gets pushed to the course repository. (And new material will get actively pushed to the course repository at least once per day as this course takes place.)

3.  Statically, you can choose the button on the right marked "Download zip" which will download the entire repository as a zip file.

You can also subscribe to the repository if you have [a GitHub account](https://github.com), which will send you updates each time new changes are pushed to the repository.

Course Schedule
---------------

------------------------------------------------------------------------

### ***Monday, 23 January: Introduction to the data science approach***

We will use this session to get to know the range of interests and experience students bring to the class, as well as to survey the machine learning approaches to be covered. We will also discuss and demonstrate the R software.

##### Resources

-   [Lecture Notes](day1/quant3_day1.pdf)
-   [Assignment 1 as R markdown](day1/quant3_assignment1_LASTNAME_FIRSTNAME.Rmd)

##### Reading:

-   James et al (2013), Chapters 1--2. Note: The book is available from the authors' page [here](http://www-bcf.usc.edu/~gareth/ISL/).
-   Grolemund and Wickham, Chapters 4, 8-10.
-   Zumel and Mount, Chapters 2-4.

##### Recommended Reading:

-   Patrick Burns, 2011. *The R Inferno*. Available [here](http://www.burns-stat.com/pages/Tutor/R_inferno.pdf).
-   Lantz, Ch. 2, 12.

##### Data Science quiz

From class - find it [here](day1/data_science_quiz.md).

##### Exercise

[Exercise 1](day1/quant3_assignment1_LASTNAME_FIRSTNAME.Rmd)

------------------------------------------------------------------------

### ***Monday, 6 February: Rethinking regression as a predictive tool***

Linear regression model and supervised learning. Revisiting prediction for the classical regression model, including logistic regression. Prediction v. association and causation.

##### Resources

-   [Lecture Notes](day3/quant3_day3.pdf)

##### Required reading:

-   James et al., Chapters 3-4.
-   Lantz, Chapter 6

##### Recommended Reading:

-   Zumel and Mount, Chapter 7.1.
-   Conway, Drew, and John White. 2012. *Machine Learning for Hackers*. O’Reilly. Chapter 5, “Regression: Predicting Page Views”.

##### Exercise

-   [Exercise 2](day2/quant3_assignment2_LASTNAME_FIRSTNAME.Rmd)
-   [Exercise 2 solution](day2/quant3_assignment2_solution.Rmd)

------------------------------------------------------------------------

### ***Monday, 20 February: Introduction to machine learning***

Naive Bayes classifier, k-Nearest Neighbour, Support Vector Machines, evaluating model performance.

##### Resources

-   [Lecture Notes](day4/quant3_day4.pdf)

##### Required reading:

-   James et al., Chapter 4.
-   Lantz, Chapters 3-4, 10.

##### Recommended Reading:

-   Lesmeister, Chapter 3.
-   Zumel and Mount, Chapters 5, 6, 7.2.

##### Exercise

-   [Exercise 3](day3/quant3_assignment3_LASTNAME_FIRSTNAME.Rmd)
-   [Exercise 3 solution](day3/quant3_assignment3_solution.Rmd)

------------------------------------------------------------------------

### ***Monday, 6 March: Unsupervised learning and dimensional reduction***

Cluster analysis, PCA, correspondence analysis, association rules.

##### Resources

-   [Lecture Notes](day4/quant3_day4.pdf)
-   [Assignment 4 as R markdown](day4/quant3_assignment4_LASTNAME_FIRSTNAME.Rmd)
-   Association rule mining code example
    -   [R code](day4/apriori_example.R)
    -   [book dataset for example](https://github.com/WinVector/zmPDSwR/raw/master/Bookdata/bookdata.tsv.gz)

##### Required reading:

-   James et al., Chapter 10.

##### Recommended Reading:

-   Lesmeister, Chapter 5, 8-9.
-   Zumel and Mount, Chapter 8.
-   Lantz, Chapters 8-9
-   Leskovec et al., Chapter 11.

##### Exercise

-   [Exercise 4](day3/quant3_assignment4_LASTNAME_FIRSTNAME.Rmd)

------------------------------------------------------------------------

### ***Monday, 20 March: Text analysis***

Working with text in R, sentiment analysis, dictionary methods.

##### Resources

-   [Lecture Notes](day8/quant3_day8.pdf)
-   [Assignment 8 as R markdown](day8/quant3_assignment8_LASTNAME_FIRSTNAME.Rmd) or [html](http://htmlpreview.github.io/?https://github.com/kbenoit/quant3/blob/master/day8/quant3_assignment8_LASTNAME_FIRSTNAME.html)
    -   sample zip file [`UKimmigTexts.zip`](day8/UKimmigTexts.zip) of texts for building a corpus
-   Assignment 8 **solution** as [R markdown](day8/quant3_assignment8_solution.Rmd)

##### Required reading:

-   Grimmer, J, and B M Stewart (2013), \`\`Text as Data: the Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.'' *Political Analysis*.
-   Benoit, Kenneth and Alexander Herzog. In press. [\`\`Text Analysis: Estimating Policy Preferences From Written and Spoken Words.''](http://www.kenbenoit.net/pdfs/HerzogBenoit_bookchapter.pdf).'' In *Analytics, Policy and Governance*, eds. Jennifer Bachner, Kathyrn Wagner Hill, and Benjamin Ginsberg.

##### Recommended Reading:

-   Spirling, A. (2012), \`\`U.S. Treaty Making with American Indians: Institutional Change and Relative Power, 1784–1911.'' *American Journal of Political Science*, 56: 84--97.
-   Herzog, A. and K. Benoit (2015), \`\`The most unkindest cuts: Speaker selection and expressed government dissent during economic crisis.'' *Journal of Politics*, 77(4):1157--1175.

Assessment
----------

#### TBA
