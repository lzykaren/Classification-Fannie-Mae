# Data-Mining-Research-Fannie-Mae
Data Mining Research about Fannie Mae Dataset

Hello!
This is Ziyan Lin, a graduate student from Johns Hopkins University, majoring in applied math and statistics.

In this repository, there is a group project developed by two different parts based on Fannie Mae dataset. The first part is classification method, and the second part is Markov Chain analysis. Group members are Ziyan Lin, Tianqi Cui, Ruoxi Liu, and Kexin Wang.

Fannie Mae provides loan performance dataset. The primary dataset is divided into two text files for each acquisition quarter, starting in 2000. The “Acquisition” file includes static mortgage loan data and the “Performance” file provides the monthly performance data of each mortgage loan. The size of whole dataset is more than 160GB. The datasets are available here https://.loanperformancedata.fanniemae.com/lppub/index.html.

Tianqi and I are focus on classification part. Classification is one of the most useful approaches to identify categories of loan performance. We treat loan performance as target variable with three categories: normal, default, and prepaid. All other variables are viewed as features. In preprocessing step, we merge files, modify datetime format, set dummy variables, and select features. In analysis step, we apply PCA to reduce dimensions and use eight different methods: Perceptron, Ridge classifier, Logistic Regression, KNN, Linear SVM, RBF SVM, Random Forest, and Naïve Bayes. For each classifier, 10-fold cross validation with accuracy as cv score is used when training. Among these methods, Random Forest plays the best role due to highest accuracy with lowest deviation.

This repository contains all codes for classification part, one final poster, and one final report. If you have any question or suggestions, please feel free to contact me. Thank you very much.

My email address: ziyanlin3@gmail.com
