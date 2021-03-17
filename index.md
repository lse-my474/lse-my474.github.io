---
papersize: a4
documentclass: scrartcl
classoption: DIV=14
colorlinks: true
---

![LSE](images/lse-logo.jpg)
# MY474 - Applied Machine Learning for Social Science

### Lent Term 2021

### Instructors

* [Blake Miller](mailto:b.a.miller@lse.ac.uk), Department of Methodology.  *Office hours*: Mondays 9:00-11:00 (held on Zoom, book via Student Hub)
* [Friedrich Geiecke](mailto:f.c.geiecke@lse.ac.uk), Department of Methodology.  *Office hours*: Tuesdays 16:00-18:00 (held on Zoom, book via Student Hub)
* [Siân Brooke](mailto:s.j.brooke@lse.ac.uk), Department of Methodology.  *Office hours*: Fridays 15:00-17:00 (held on Zoom, book via Student Hub)
* [Sarah Jewett](mailto:s.jewett1@lse.ac.uk), Department of Government.

### Course Information

* Lectures Prerecorded ([View on Echo360](https://echo360.org.uk/section/dd29c349-9eba-4028-bf7b-999ed047f4b5/public))
* Q&A Sessions Wednesdays 09:00-10:00 (Zoom link on Moodle)
* Classes (weeks 2, 4, 7, 9, 11):
   * Wed 16:00-17:30 (SB)
   * Thu 09:00-10:30 (SB)
   * Thu 17:00-18:30 (SJ)

No lectures or classes will take place during School Reading Week 6.

| **Week** | **Topic**                                                                                                             | **Instructor** |
|:--------:|:----------------------------------------------------------------------------------------------------------------------|:---------------|
| 1        | [What is Machine Learning?](#week-1-what-is-machine-learning)                                                         | BM             |
| 2        | [Generalization, Inference, Prediction, and Causality](#week-2-generalization-inference-prediction-and-causality)     | BM             |
| 3        | [Linear Discriminant Analysis, Logistic Regression](#week-3-linear-discriminant-analysis-logistic-regression)         | BM             |
| 4        | [Gradient Descent, Bootstrap, Cross-Validation, Hyperparameters](#week-4-gradient-descent-bootstrap-cross-validation-hyperparameters)   | BM             |
| 5        | [Regularization, Decision Trees](#week-5-regularization-decision-trees)                                               | BM             |
| 6        | _Reading Week_                                                                                                        |  -             |
| 7        | [Support Vector Machines, Active Learning](#week-7-support-vector-machines-active-learning)                           | BM             |
| 8        | [Bias, Fairness, Accountability, and Transparency in ML](#week-8-bias-fairness-accountability-and-transparency-in-ml) | BM             |
| 9        | [Ensembles, Bagging, Boosting](#week-9-ensembles-bagging-boosting)                                                    | FG             |
| 10       | [Dimension Reduction and Clustering](#week-10-dimension-reduction-and-clustering)                                     | FG             |
| 11       | [Other Varieties of Machine Learning](#week-11-other-varieties-of-machine-learning)                                   | FG             |

### Course Description

The amount of data available to social science researchers has exploded in recent years. Advances in machine learning have given social scientists new tools to make sense of these data to answer big and important questions that we did not have the tools to answer just a few years before. For example, some researchers have used machine learning to explore patterns in large databases of text in an effort to identify how the racial and gender biases encoded in language have changed over time. Others have used machine learning methods to detect and analyze the behavior of state-sponsored bots and trolls and the content they produce. In this class we will introduce a wide range of machine learning methods and their applications to social science.

The course surveys machine learning methods and concepts with the application to social sciences in mind. We begin with discussions of how machine learning methods can be adapted from the predictive purposes for which they were originally designed, to the ultimate goal of inference. We will then move on to a survey of common machine learning models for classification and regression, frameworks for out-of-sample validation, and finally, a discussion of unsupervised learning and a brief overview of state-of-the-art methods such as deep learning, reinforcement learning, and active learning.

### Objectives

* To introduce the theoretical foundations of machine learning, statistical inference, and prediction
* To explore the many applications of statistical machine learning to social science research
* To examine the broader social impacts of algorithms and machine learning on contemporary politics and society

### Prerequisites

Applied Regression Analysis (MY452) or equivalent is required. In short, you should 1) understand linear regression and logistic regression and 2) know the basics of a programming language. 

Students in this course will strongly benefit from prior experience with the R programming language. Class assignments will be completed in R. If you do not know R, you will have to invest extra time on your own to learn the language.

### Textbooks and Course Materials

All course materials are available for free download. The R books are for your own reference and will not be assigned as readings for the class.

* James, Gareth, et al. An Introduction to Statistical Learning (ISL). New York: Springer, 2013. [http://www-bcf.usc.edu/~gareth/ISL/](http://www-bcf.usc.edu/~gareth/ISL/)
* Friedman, Jerome, Trevor Hastie, and Robert Tibshirani. The Elements of Statistical Learning (ESL). Vol. 1. No. 10. New York: Springer Series in Statistics, 2001. [https://web.stanford.edu/~hastie/ElemStatLearn/](https://web.stanford.edu/~hastie/ElemStatLearn/)
* Kuhn, Max, and Kjell Johnson. Feature Engineering and Selection: A Practical Approach for Predictive Models. CRC Press, 2019. [https://bookdown.org/max/FES/](https://bookdown.org/max/FES/)
* Wickham, Hadley. Advanced R. Chapman and Hall/CRC, 2014. [https://adv-r.hadley.nz/](https://adv-r.hadley.nz/)

### Required Software

The ISL textbook uses the R programming language for labs that you are required to complete at home before class. R and R Markdown (via R Studio) will also be used in summative assessments, in-class exercises, and for your final assessment.

* Install R: [http://cran.rstudio.com/](http://cran.rstudio.com/)
* Install RStudio: ![http://www.rstudio.com/products/rstudio/download/](http://www.rstudio.com/products/rstudio/download/)

### Assessments

* Problem Sets (40%) in the LT.
* Multiple Choice Assessment (30%) in the LT.
* Take-home assessment (30%) in the ST (Master's and PhD students will have different assessments, see below).

#### Problem Sets for master's students enrolled in MY474 and PhD students enrolled in MY574 (40% of total mark)

Problem sets will be assigned at the beginning of each lab session. These will involve computer exercises applied to data supplied by the instructor. These will be submitted via GitHub Classroom by their due date, and will be marked to provide 40% of the course grade.

Problem sets consist of two parts:

1. Written responses
2. Coding questions

Both parts should be included in the Rmd and PDF files to be uploaded to Moodle.

One formative problem set will **not** count toward your final mark, but will give you an idea of how problem sets are structured:

* Problem Set 1 (Formative): Due Wednesday 10/02/2021 1:00pm

There will be four summative problem sets that will count toward the final grade:

* Problem Set 2 (Summative): Due Wednesday 03/03/2021 1:00pm
* Problem Set 3 (Summative): Due Wednesday 17/03/2021 1:00pm
* Problem Set 4 (Summative): Due Wednesday 31/03/2021 1:00pm
* Problem Set 5 (Summative): Due Wednesday 14/04/2021 1:00pm

#### Multiple Choice Assessment for master's students enrolled in MY474 and PhD students enrolled in MY574 (30% of total mark)

The multiple choice assessment is a timed quiz administered on Moodle, and is based on lecture, seminars, and readings. The exam will be released on Moodle at 7:00am on Monday of Week 11. You can start any time between 7:00am and 2:00pm, but the exam is timed and must be completed within 1 hour. Once the Moodle exam is opened, you will have 1 hour to complete it. After 1 hour your exam will be automatically submitted and you will have no further access to the exam. The exam must be submitted by 2:00pm.

#### Take Home Assessment for master's students enrolled in MY474 (Due Monday, May 24, 2021 by 2pm, 30% of total mark)

1. **Kaggle competition classifying toxic comments (10% of total mark):** A text classification competition will be hosted on the Kaggle website for all students enrolled in the class. Students will submit model predictions for held-out data to Kaggle and the performance of their model output will be calculated on the Kaggle site. The competition will open to students the first day of Summer Term.
2. **Code report and write-up (submitted as Rmd and PDF on Moodle, 20% of total mark)**: Code reproducing the prediction file uploaded to Kaggle should be provided in a Rmd file in chunks that are annotated. Code should be supplemented by a writeup that documents 1) how you settled on the final model, 2) the reasoning behind modelling choices, 3) how you evaluated each iteration of your model, 4) a discussion of feature engineering choices, and 5) conclusions and reflections on the modelling process. The writeup is due at 2:00pm on May 24, 2021.

#### Take Home Assessment for PhD students enrolled in MY574 (Due Monday, May 24, 2021 by 2pm, 30% of total mark)

PhD students are expected to submit a 3000-word paper in which they identify and contextualize a relevant social data science problem related to their dissertation research, find suitable data to address it, plan and conduct extensive machine learning analysis on the data, and present the findings. Marking of these assessments will be at a level appropriate for PhD students.

##### Project proposal (10% of take home assessment, due Week 7 Seminar):

The project proposal should be 1.5 to 2 pages, double spaced. I will provide feedback on the proposals to make sure you are on the right track for the final take home assessment. The proposal will contribute 3% toward your final grade so take it seriously.

Guidelines:

* Introduce your dataset(s). What are variables of interest to you?
* What are your research goals? What questions are you asking? Why are they important? What will we learn from your analysis?
* Is your goal prediction, (causal) inference, description, or some combination of the three?
* What are your methods? What tools from class will you use to accomplish these goals?
* Writing should be clear, well-structured, and easy to follow.

##### Project Report (Due Monday, May 24, 2021 by 2pm, 30% of total mark)

PhD students will submit a project report, which is a 3000-word paper in which they identify and contextualize a relevant social data science problem related to their dissertation research, find suitable data to address it, plan and conduct extensive machine learning analysis on the data, and present the findings. This report should be thought of as a first draft of a paper to submit to a scholarly journal. The analysis need not be ready for publication, but should suggest a roadmap for eventual publication (through discussion of additional analyses to be conducted, additional data to be collected, etc.) Format your report like you would an academic paper. In addition to the paper, you should also include an R markdown file with code and figures used for the analysis. These components should be submitted on Moodle.

### Marking Criteria

#### Written Assignments

Written assignments will be marked using the following criteria:

* 70–100: Very Good to Excellent (Distinction). Perceptive, focused use of a good depth of material with a critical edge. Coherent well-read and researched answers. Original ideas or structure of argument.

* 60–69: Good (Merit). Perceptive understanding of the material. Coherent well-read and researched answers.

* 50–59: Satisfactory (Pass). A "correct" answer based largely on lecture material. Little detail or originality but presented in adequate framework. Small factual errors allowed.

* 30–49: Unsatisfactory (Fail) and 0–29: Unsatisfactory (Bad fail). Based entirely on lecture material but unstructured and with increasing error component. Concepts are disordered or flawed. Poor presentation. Errors of concept and scope or poor in knowledge, structure and expression.

#### Short Answer and Coding Assignments

Some of the assignments will involve shorter questions or coding assignments, to which the answers can be relatively unambiguously coded as (fully or partially) correct or incorrect. In the marking, these questions may be further broken down into smaller steps and marked step by step. The final mark is then a function of the proportion of parts of the questions which have been answered correctly. In such marking, the principle of partial credit is observed as far as feasible. This means that an answer to a part of a question will be treated as correct when it is correct conditional on answers to other parts of the question, even if those other parts have been answered incorrectly. If code output is incorrect but it is clear that some of the implementation has been correctly executed, partial credit will be given as far as feasible.

Short answer and coding assignments will be marked using the following criteria:

* 70-100: Distinction
* 60-69: Merit
* 50-59: Pass
* 30-49: Fail
* 0-29: Bad Fail

#### Final Assessment Coding Competition

Scores for the final coding competition will be calculated on Kaggle and grades will be determined by ranking in competition:

- Top 2: 100
- First Quintile: 95
- Second Quintile: 90
- Third Quintile: 85
- Fourth Quintile: 80
- Fifth Quintile: 75

### Schedule

#### Week 1. [What is Machine Learning?](https://github.com/lse-my474/lectures/blob/master/week1/)

This week we focus on the big picture: what is machine learning? We explore the main varieties of what we consider machine learning and discuss the problems involved in prediction and generalization from training data.

*Reading:*
* Learning from Data (LDF) Ch. 1 (scan on Moodle)
* Introduction to Statistical Learning (ISL) 2.1-2.3

*Further Reading:*
* Elements of Statistical Learning (ESL) 2.1-2.6

#### Week 2: [Generalization, Inference, Prediction, and Causality](https://github.com/lse-my474/lectures/blob/master/week2/)

*Reading:*
* Titiunik, Rocío. "Can Big Data Solve the Fundamental Problem of Causal Inference?." PS: Political Science \& Politics 48.1 (2015): 75-79.
* Monroe, Burt L.; Pan, Jennifer; Roberts, Margaret E.; Sen, Maya, and Betsy Sinclair. 2015. "No! Formal Theory, Causal Inference, and Big Data Are Not Contradictory Trends in Political Science." PS: Political Science and Politics.

*Further Reading:*
* LFD Ch. 2
* Mullainathan, Sendhil, and Jann Spiess. 2017. "Machine Learning: An Applied Econometric Approach." Journal of Economic Perspectives, 31 (2): 87-106.

 *Seminar Materials:* [Click here](https://classroom.github.com/a/SCt_-tES) to access seminar materials **when instructed**.

*Github Reference Materials:* [Click here](https://github.com/lse-my474/lectures/tree/master/github-user-guides) for reference guides to Github. 

#### Week 3: [Linear Discriminant Analysis, Logistic Regression](https://github.com/lse-my474/lectures/blob/master/week3/)

*Reading:*
* ISL Ch. 3 (If you need a refresher on linear regression)
* ISL Ch. 4

#### Week 4: [Gradient Descent, Bootstrap, Cross-Validation, Hyperparameters](https://github.com/lse-my474/lectures/blob/master/week4/)

*Reading:*
* ISL Ch. 5

*Further Reading:*
* Feature Engineering and Selection Ch. 3
* Aloís Bissuel. "Hyper-parameter optimization algorithms: a short review." Medium. ([Access article here](https://medium.com/criteo-labs/hyper-parameter-optimization-algorithms-2fe447525903))
* Ghahramani, Zoubin. "Probabilistic machine learning and artificial intelligence." Nature 521.7553 (2015): 452.
* Bergstra, James, and Yoshua Bengio. "Random search for hyper-parameter optimization." Journal of Machine Learning Research 13.Feb (2012): 281-305.

*Seminar Materials:* [Click here](https://classroom.github.com/a/gT1tbgpT) to access seminar materials **when instructed**.

#### Week 5: [Regularization, Decision Trees](https://github.com/lse-my474/lectures/blob/master/week5/)

*Reading:*
* ISL 6.2, 6.4
* ISL 8.1

#### Week 7: [Support Vector Machines, Active Learning](https://github.com/lse-my474/lectures/blob/master/week7/)

*Reading:*
* ISL Ch. 9
* Miller, Blake, Fridolin Linder, and Walter R. Mebane. "Active learning approaches for labeling text: review and assessment of the performance of active learning approaches." Political Analysis 28.4 (2020): 532-551.

*Further Reading:*
* Barberá, Pablo, et al. "Automated text classification of news articles: A practical guide." Political Analysis (2019): 1-24.

 *Seminar Materials:* [Click here](https://classroom.github.com/a/_H_dzEua) to access seminar materials **when instructed**.

#### Week 8: [Bias, Fairness, Accountability, and Transparency in ML](https://github.com/lse-my474/lectures/blob/master/week8/)

*Reading:*
* [Lee, Nicol Turner, Paul Resnick, and Genie Barton. "Algorithmic bias detection and mitigation: Best practices and policies to reduce consumer harms." Brookings Institute: Washington, DC, USA (2019).](https://www.brookings.edu/research/algorithmic-bias-detection-and-mitigation-best-practices-and-policies-to-reduce-consumer-harms/)
* Wallach, Hanna. "Big Data, Machine Learning, and the Social Sciences: Fairness, Accountability, and Transparency." NeurIPS Workshop on Fairness, Accountability, and Transparency in Machine Learning. 2014.
* Deibert, Ronald J. "The Road to Digital Unfreedom: Three Painful Truths About Social Media." Journal of Democracy 30.1 (2019): 25-39.

*Further Reading:*
* Crawford, Kate. The Trouble with Bias. Link: [Access video here](https://www.youtube.com/watch?v=fMym_BKWQzk)
* Bolukbasi, Tolga, et al. "Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings." Advances in Neural Information Processing Systems. 2016.
* Levin, Sam. "Imprisoned by algorithms: the dark side of California ending cash bail." The Guardian. 2018. ([Access article here](https://www.theguardian.com/us-news/2018/sep/07/imprisoned-by-algorithms-the-dark-side-of-california-ending-cash-bail))
* Rajagopalan, Megha. "This Is What A 21st-Century Police State Really Looks Like." February 2, 2018 ([Access article here](https://www.buzzfeednews.com/article/meghara/the-police-state-of-the-future-is-already-here))


#### Week 9: [Ensembles, Bagging, Boosting](https://github.com/lse-my474/lectures/blob/master/week9/)

*Reading:*
* ISL 8.2

*Further Reading:*
* Hill, Daniel W., and Zachary M. Jones. "An Empirical Evaluation of Explanations for State Repression." American Political Science Review 108.3 (2014): 661-687.

<!-- *Seminar Materials:* [Click here](https://classroom.github.com/a/FiF36LJ7) to access seminar materials **when instructed**.-->

#### Week 10: [Dimension Reduction and Clustering](https://github.com/lse-my474/lectures/blob/master/week10/)

*Reading:*
* ISL Ch. 10

#### Week 11: [Other Varieties of Machine Learning](https://github.com/lse-my474/lectures/blob/master/week11/)

*Reading:*
* TBD

<!-- *Seminar Materials:* [Click here]() to access seminar materials **when instructed**.-->
