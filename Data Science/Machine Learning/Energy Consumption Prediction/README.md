# Building Energy Consumption Forecast


*Livrables* : 1 notebooks R & 1 notebook Python.

## Work realised

**Data analysis**

1. Start with some unidimensional descriptive statistics of the dataset.
2. Continue with a multidimensional descriptive analysis. In particular, using visualization techniques.
3. Consider the quantitative variables, except the Energy one. Do a principal component analysis.
4. Still about the quantitative variables, use a clustering technique.


**Models**

1. Split the data into a training set and a test set.
2. Implement new metrics to assess the models.
3. First, we consider the **classification** problem directly. Compare the performance of a linear model (logistic regression) with/without penalization, an optimal tree, random forest, boosting and SVM, and tune carefully the parameters. 
4. Then, we consider the **regression** problem and then classify using the given thresholds.
5. Conclude on which approach is the best to predict energy classes: direct classification or regression+thresholding?

