---
title: BMI-CS-534
description: Short version
---


# BMI 534 - Introduction to Machine Learning
# CS 534 - Machine Learning

This is a summarized version of the syllabus. The detailed version of the syllabus will be available on the Emory Canvas.

### Instructor:

Hyeokhyen Kwon, Ph.D. \
Assistant Professor \
Department of Biomedical Informatics \
Office: Rm 4105, 4th Floor, Emory Woodruff Memorial Research Building (101 Woodruff Cir, Atlanta, GA 30322)


Teaching Assistant: TBD ([mail](mailto:mail_TBD))


## Course Overview


Machine learning is innovating many applications all across our society from autonomous vehicles to biomedicine and science. In this course, students will learn the fundamental theories (optimization, probability, linear algebra, etc) and algorithms of machine learning (supervised and unsupervised learning, etc) and also obtain practical experiences in applying machine learning techniques and analysis in real-world problems in biomedical informatics.


### Learning Objectives


This course will introduce students to fundamental theory and algorithms in machine learning through lectures, homework, midterm, and a semester-long project. Taking this course, students should be able to:
- Prepare datasets for machine-learning experiments
- Understand the basic building blocks and general principles that underlie machine learning algorithms
- Be familiar with specific, widely used machine learning algorithms for classification and regression
- Formulate rigorous validation protocols, and evaluate the rigor of published experiments
- Understand the bias and variance tradeoffs and strategies to mitigate overfitting
- Understand fundamental machine-learning algorithms presented in the second half of the course
- Learn methodology and tools to apply machine learning algorithms to real data and evaluate their effectiveness and performance


### Prerequisites:


- Undergraduate-level linear algebra
- Undergraduate-level multivariate calculus
- Undergraduate-level statistics and probability theory
- Coding experience:
  - Python (required)
  - Matlab (optional)
  - C/C++ (optional)
  - R (optional)
- Permission by the instructor (Send an email to the [instructor](mailto:hyeokhyen.kwon@emory.edu))


## Course Logistics


### Communication & Course Materials:


- **Emory Canvas:** \
The class syllabus, schedule, lecture slides, homework handouts/files, discussion, and grades are posted on this platform. Please ask all questions under the discussions section of Canvas. You are encouraged to answer other students’ questions when you know the answer. Do not ask or answer questions that are exactly homework questions.


- **Email:** \
If there are private matters specific to you (e.g., special accommodations, requesting alternative arrangements, etc.) or confidential matters you want to report, please email with the subject heading starting with “[CS534]”. I probably will not respond immediately but will try to respond within 24 hours(during specific busy periods I may need 48 hours). It is best to avoid last-minute questions that require immediate attention (e.g., before a deadline!). Plan accordingly.

- **Office Hours**
  - Hyeokhyen Kwon: TBD
  - TA-TBD: TBD

### Textbook(s):
- Required
  - "The Elements of Statistical Learning: Data mining, Inference, and Prediction, Second Edition", by Trevor Hastie, Robert Tibshirani & Jerome Friedman ([link](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf))
- Supplemental:
  - "Machine Learning: a Probabilistic Perspective", by Kevin Murphy
  - "Pattern Recognition and Machine Learning", by Christopher Bishop
  - "A First Encounter with Machine Learning", by Max Welling  ([link](https://github.com/tpn/pdfs/blob/master/A%20First%20Encounter%20with%20Machine%20Learning%20-%202011%20(IntroMLBook).pdf))
  - "A Course in Machine Learning", by Hal Daumé III ([link](http://ciml.info/))
  - "Understanding Machine Learning: From Theory to Algorithms", by Shai Shalev-Shwartz & Shai Ben-David ([link](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf))


## Expectations & Grading:

Component   | Weight |
--------- | ------ |
Participation   |  10% |
Homeworks   | 35%    |
Midterm   | 15%    |
Project   | 40%    |

The detailed version of the syllabus with instructions on each component and grading policy will be uploaded on Canvas.

## University Policies and Academic Integrity

All class work is governed by the College Honor Code and Departmental Policy.
Your submitted homework and _all code and writeup_ must be written by yourself.
Any code and writeup that is found to be similar are grounds for an honor code investigation by the Director of Graduate Studies, Laney Graduate School, and the honor council.
Additional extensions on assignments will be granted with appropriate documentation from the Office of Undergraduate Education (OUE)

A syllabus with details of policies will be uploaded on Canvas.


## (Tentative) Course Schedule

Topics may change but the homework, midterm, and project deliverables are fixed.
The reading material listed below is optional and the lecture plan may deviate over the course of the semester.


|\# | Date | Theme | Topic | Reference (Chapter)  | Assignment |
|:- |:---- |:--- |:------------- |:----------- |:---------- |
1  | 1/17 | Intro + Course Logistics | Review syllabus, Overview of course topics | Ch. 1 (Hastie et al.)<br>[Ch. 1 (Murphy)](http://www.cs.ubc.ca/~murphyk/MLbook/pml-intro-22may12.pdf) <br>[Ch. 3 (Welling)](https://github.com/tpn/pdfs/blob/master/A%20First%20Encounter%20with%20Machine%20Learning%20-%202011%20(IntroMLBook).pdf)|  **Homework #0 out (Due 1/30)** |
2  | 1/22  | Intro to Optimization | | Convex optimization notes [Part I](http://cs229.stanford.edu/section/cs229-cvxopt.pdf) and [II](http://cs229.stanford.edu/section/cs229-cvxopt2.pdf) from Stanford's machine learning class<br>Rosenberg's [abridged notes](https://davidrosenberg.github.io/mlcourse/Notes/convex-optimization.pdf)|
3  | 1/24  | Intro to Statistics, Probability, and Random Variables | Random variables, probability density functions, conditional and joint distributions, Bayes rule | Handouts |
4  | 1/29  | Statistical Decision Theory + Linear Regression | Mapping machine learning problems to statistical concepts, Regression, ridge regression | Ch 1 -2; Ch 3.1 - 3.4 (Hastie et al.)<br>Ch. 17.1 - 17.2 [(Barber)](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/171216.pdf)<br>Prof. Carlos Carvalho's [MLR Slides](http://faculty.mccombs.utexas.edu/carlos.carvalho/teaching/Section4.pdf) |
5  | 1/31  | Linear Regression + Naive Bayes | LASSO regression, elastic net regression | |  **Homework #1 out (Due 2/13)** |
6  | 2/5  | Linear Classification | logistic regression, LDA, QDA | Ch 2.1 - 2.4; Ch 4.1 - 4.4 (Hastie et al.) |
7  | 2/7  | Linear Classification + Bias-Variance Tradeoff | Training & test error, conditional and expected test error, bias-variance decomposition and tradeoff, training error optimism | Ch 7.2 - 7.3 (Hastie et al.)<br>Ch. 5.9 (Daumé III) |
8  | 2/12  | Model Assessment + Error Measures | Validation as an estimation problem, cross validation, bias and variance of cross validation schemes, Error measures, class imbalance, ROC analysis, precision-recall | Ch. 7.10 (Hastie et al.)<br>Ch. 2.5 - 2.6 (Daumé III)| |
9  | 2/14  | Model Selection | Effective number of parameters, Akaike and Bayes information criterion | Ch. 7 (Hastie et al.)<br>Ch. 5.5 - 5.6 (Daumé III) | **Homework #2 out (Due 2/27)** |
10 | 2/19  | Practical Issues | Preparing data, labeling issues, interpretation  | Ch. 9 -10 (Hastie et al.) |
11  | 2/21  | Decision Trees | Decision trees, boosting | Ch. 9.2 (Hastie et al.)<br> Ch. 1.3 (Daumé III) |
12  | 2/26  | Perceptron + Support Vector Machines | Perceptron, SVM, kernel SVM | Ch. 12 (Hastie et al.)<br>Ch. 4; Ch. 11 (Daumé III)<br> Ch. 7 - 9 (Welling)<br>Ch. 15 (Shalev-Shwartz & Ben-David)<br>[Standford SVM notes](http://cs229.stanford.edu/notes/cs229-notes3.pdf)<br>[NYU SVM notes](https://davidrosenberg.github.io/ml2015/docs/svm-notes.pdf) | |
13  | 2/28  | Neural Networks | Architectures, gradient optimization, back propagation | Ch. 11 (Hastie et al.)<br>Ch. 1-3 [(Nielsen)](http://neuralnetworksanddeeplearning.com/index.html)<br>Ch. 20.1 - 20.3 (Shalev-Shwartz & Ben-David) | **Homework #3 out (Due 3/14)** |
14  | 3/4  | Neural Networks | | | **Project Proposal due 3/5** |
| | 3/6  | Spring Break | | |
| | 3/11  | Spring Break | | |
15  | 3/13  | Additive Models + Bootstrap | ADABoost, gradient boosting | Ch. 7.11; Ch. 9.1 (Hastie et al.) |
16  | 3/18  | Boosting | | Ch. 10 (Hastie et al.) | **Homework #4 out (Due 4/2)** |
17  | 3/20  | Random Forest | Ensemble methods, random forests | Ch. 15 - 16 (Hastie et al.)<br>Breiman's [paper](http://dl.acm.org/citation.cfm?id=570182) | **Project Spotlight Slides Due 3/24** |
18  | 3/25  | **Project Spotlight** + Ensembles | | |
19  | 3/27  | Prototype methods + Challenges with High-dimensional Data + Demensionality Reduction | KNN, Curse of dimensionality, sparse representation | Ch. 13 - 14; Ch. 18 (Hastie et al.)<br>Ch. 3.2 - 3.3 (Daumé III)<br>Ch. 5 (Welling)<br> Ch. 19.1 - 19.2; Ch. 23 (Shalev-Shwartz & Ben-David)<br>[Stanford PCA notes](http://cs229.stanford.edu/notes/cs229-notes10.pdf) | |
20  | 4/1  | Dimensionality Reduction | Principal component analysis, locally-linear embedding, manifold learning | Ch. 14 (Hastie et al.) | |
21  | 4/3  | Clustering + Mixture modeling | K-means, spectral clustering, expectation maximization | Ch. 14 (Hastie et al.) | **Homework #5 out (Due 4/16)** |
22  | 4/8  | Deep Learning | | | |
23  | 4/10  | Deep Learning | |
24  | 4/15  | Emerging Topics and Application (Human Activity Recognition) | |
25  | 4/17  | Emerging Topics and Application (Generative Artificial Intelligence) | |
21  | 4/22  | **Midterm Exam** | |
27  | 4/24  | Project Presentations | |
28  | 4/29  | Project Presentations | | | **Final Report Due 5/10** |


