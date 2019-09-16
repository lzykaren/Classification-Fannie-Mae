# Classification Research Fannie Mae

Hello!

This is Ziyan Lin, a graduate student from Johns Hopkins University, majoring in applied math and statistics.

In this repository, there is a group project developed by two different parts based on Fannie Mae dataset. The first part is classification method, and the second part is Markov Chain analysis. Group members are Ziyan Lin, Tianqi Cui, Ruoxi Liu, and Kexin Wang.

Fannie Mae provides loan performance dataset. The primary dataset is divided into two text files for each acquisition quarter, starting in 2000. The “Acquisition” file includes static mortgage loan data and the “Performance” file provides the monthly performance data of each mortgage loan. The size of whole dataset is more than 160GB. The datasets are available here: https://.loanperformancedata.fanniemae.com/lppub/index.html. 

Tianqi and I are focus on classification part. Zero Balance code is treated as target variable with three categories: normal, default, and prepaid. All other variables are viewed as features. PCA and eight different classification methods, Perceptron, Ridge classifier, Logistic Regression, KNN, Linear SVM, RBF SVM, Random Forest, and Naïve Bayes are applied into analysis. For each classifier, 10-fold cross validation with accuracy as cv score is used when training. Among these methods, Random Forest plays the best role due to highest accuracy with lowest deviation, and confusion matrix is reported.

This repository contains five parts of code: [(1) Reading all files](https://github.com/lzykaren/Classification-Fannie-Mae/blob/master/(1)%20Reading%20files.ipynb), [(2) Sample Random Selection ](https://github.com/lzykaren/Classification-Fannie-Mae/blob/master/(2)%20Sample%20Random%20Selection%20.ipynb), [(3) Data clean, Format change, Dummy variables, and Feature selection](https://github.com/lzykaren/Classification-Fannie-Mae/blob/master/(3)%20Data%20clean%2C%20Format%20change%2C%20Dummy%20variables%2C%20and%20Feature%20selection.ipynb), [(4) Heatmap, PCA, and Classification](https://github.com/lzykaren/Classification-Fannie-Mae/blob/master/(4)%20Heatmap%2C%20PCA%2C%20and%20Classification.ipynb), and [(5) Classification and Confusion matrix](https://github.com/lzykaren/Classification-Fannie-Mae/blob/master/(5)%20Heatmap%2C%20PCA%2C%20Classification%2C%20and%20Confusion%20matrix.ipynb); one [final poster](https://github.com/lzykaren/Data-Mining-Research-Fannie-Mae/blob/master/FANM%20Final%20Poster.pdf), and one [final report](https://github.com/lzykaren/Data-Mining-Research-Fannie-Mae/blob/master/FANM%20Final%20Report.pdf). If you have any question or suggestion, please feel free to contact me. Thank you very much.

My email address: ziyanlin3@gmail.com
