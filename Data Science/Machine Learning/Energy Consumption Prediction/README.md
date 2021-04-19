# Prévision de la performance énergétique des bâtiments


*Delivrables* : 2 notebooks R & Python dont 1 rapport technique : introduction, interprétation des résultats, conclusion, etc.

*Deadline* : 2 décembre 2020.



**Data analysis**

1. Start with some unidimensional descriptive statistics of the dataset. Can you see anomalies?
2. Continue with a multidimensional descriptive analysis. In particular, using visualization techniques (e.g. scatterplot, conditional plot), which variable(s) seem to be the most influential on the output? Can you see interactions?
3. Consider the quantitative variables, except the Energy one. Do a principal component analysis. Can you see clusters? Do they correspond to the energy classes?
4. Still about the quantitative variables, use a clustering technique. Conclusion?


**Models**

1. First of all, split the data into a training set and a test set. Why is this step necessary when we focus on performance?
2. Here, we consider the classification problem directly. Compare the performance of a linear model (logistic regression) with/without penalization, an optimal tree, random forest, boosting and SVM. Justify your choice (e.g. kernel for SVM), and tune carefully the parameters. Interpret the results and quantify the improvement brought by non-linear models.
3. Now, we first consider the regression problem and then classify using the given thresholds. Same question as before.
4. What approach is the best to predict energy classes: direct classification or regression+thresholding?
5. Interpretation and come-back to data analysis. Are your results consistent with the preliminary data analysis, e.g. about non-linearities, influence of variables (or variable importance)?
