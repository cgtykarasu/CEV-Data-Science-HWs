### TASK-7A: Please apply one-hot encoding method on one of the categorical variables (not SEX/gender) for the given AD dataset. Please explain what kind of transformation occured on the dataset.

### TASK-7B: Please provide a couple of pivot tables in order to illustrate how SEX variable is influential on our target array (CDRGLOB). Please provide a few multidimensional analyses (not limited to two variables).

### TASK-7C: Referring to the problem in part B, please provide a potential solution to the gender-based issue that appears as a bottleneck for the model development phase. One possible solution might be to provide normalization of the numeric columns with respect to the total brain volume (NACCBRNV column).

### TASK-7D: After the normalization process, please provide a correlation matrix to report the critical features that have high correlation (positive or negative) with the target array (CDRGLOB).

### TASK-7E: Please develop 3 distinct formulas (in other words derived features like BMI score) that involve the critical features in Part-7D and then ensure that these derived features could be used as predictive variables for CDRGLOB (again correlation analysis will give you insight).

### TASK-7F: Then please develop a machine learning model with the 3 derived features that you obtain in 7E via the use of train-test split (be careful about stratify parameter in this function) and gridsearchCV function as well as a classification algorithm (such as Gaussian Naive Bayes) but please do not forget to optimize its hyperparameters. Finally, please report your findings via the use of classification report function (also a sklearn function).
