PROCESSES:
1.DATA CLEANING :-
Data cleaning refers to identifying and correcting errors in the dataset that may
negatively impact a predictive model. Data cleaning is used to refer to all kinds of tasks and
activities to detect and repair errors in the data.
2.HANDLING MISSING VALUES :-
Data can have missing values for a number of reasons such as observations that were not
recorded and data corruption. Handling missing data is important as many machine
learning algorithms do not support data with missing values.
• Deductive Imputation : This is an imputation rule defined by logical reasoning,
as opposed to a statistical rule.
• Mean/Median/Mode Imputation : In this method, any missing values in a given
column are replaced with the mean (or median, or mode) of that column.
• Regression Imputation.
• Stochastic Regression Imputation.
3.FEATURE ENGINEERING :-
Feature engineering is the process of using domain knowledge to extract features from
raw data via data mining techniques. These features can be used to improve the performance
of machine learning algorithms. Feature engineering can be considered as applied machine
learning itself.
[5]
Having and engineering good features will allow you to most accurately represent the
underlying structure of the data and therefore create the best model. Features can be
engineered by decomposing or splitting features, from external data sources, or aggregating or
combining features to create new features.
4.FEATURE SELECTION :-
Feature Selection is the process where you automatically or
manually select those features which contribute most to your prediction variable or output in
which you are interested in. Having irrelevant features in your data can decrease the accuracy
of the models and make your model learn based on irrelevant features.
Feature selection is for filtering irrelevant or redundant features from your dataset. The
key difference between feature selection and extraction is that feature selection keeps a subset
of the original features while feature extraction creates brand new ones.
5.OUTLIER REMOVAL :-
Outlier Detection and Removal In this case, simple statistical methods for
identifying outliers can break down, such as methods that use standard deviations or the
interquartile range. It can be important to identify and remove outliers from data when
training machine learning algorithms for predictive modelling.
One of the simplest methods for detecting outliers is the use of box plots. A box plot is
a graphical display for describing the distributions of the data. Box plots use the median and
the lower and upper quartiles.
6.HANDLING CATEGORICAL VARIABLES :-
Below are the methods to convert a categorical (string) input to numerical nature:
1. Label Encoder: It is used to transform non-numerical labels to numerical
labels (or nominal categorical variables).
2. Convert numeric bins to number: Let's say, bins of a continuous variable are
available in the data set (shown below).
7.TRAINING THE DATASETS :-
The training data is an initial set of data used to help a program understand how to apply
technologies like neural networks to learn and produce sophisticated results. ... Training data is
also known as a training set, training dataset or learning set.
[6]
7. K FOLD CROSS VALIDATION TO MEASURE ACCURACY :-
Cross validation is a technique for assessing how the statistical analysis generalises to
an independent data set. It is a technique for evaluating machine learning models by training
several models on subsets of the available input data and evaluating them on the
complementary subset of the data.
8.USE GRIDSEARCHCV FOR FINDING BEST MODEL:-
GridSearchCV is a library function that is a member of SKlearn's model_selection
package. It helps to loop through predefined hyperparameters and fit your estimator (model)
on your training set. ... In addition to that, you can specify the number of times for the crossvalidation for each set of hyperparameters.
9. PREDICT THE MODEL :-
Typically, such a model includes a machine learning algorithm that learns certain
properties from a training dataset in order to make those predictions. ... In contrast to
regression models, the task of pattern classification is to assign discrete class labels to
particular observations as outcomes of a prediction.
