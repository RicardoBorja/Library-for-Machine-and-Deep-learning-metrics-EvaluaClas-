# Library-for-Machine-and-Deep-learning-metrics-EvaluaClas-
The repository contains a library designed in RStudio software that allows to directly obtain the performance metrics of a Machine or Deep Learning classifier (accuracy, kappa index, Recall, F1-score, ROC graph and AUC).

In addition, it makes a comparative graph of the values ​​of the metrics (accuracy, kappa index and F1-score) under five scenarios (reducing their sample size to 75%, 50%, 25% and 10%). In order to allow the researcher to use the most appropriate performance measure depending on the case studied (through its sensitivity in each case).
To use it, just download the file in .zip format and install it in RStudio. The package has the name EvaluaClas.
Once installed you must activate it.

library (EvaluaClas)

It also consists of a brief explanation using the code:? EvaluaClas
 To execute you must enter the file in dataframe format where each column belongs to the classification results either from several observers or Machine or Deep Learning classifiers. The first column must belong to the Gold Standard (actual results). The program will automatically install the necessary libraries and activate them. When executing the results you will get them in the console so they can also be stored in a variable (the output will be in a list format).
Its execution is very simple through the following code:

Results <- EvaluaClas (data = data)

In the established work address the results will be presented in pdf format, also in the console and finally the function will return a list of the results.
