# Foundations of Machine Learning Models

## Assignment: Custom Transformer and Transformation Pipeline

#### Name: Richard Lee

### Details
Your task in this assignment is to create a custom transformation pipeline that takes in raw data and returns fully prepared, clean data that is ready for model training.  However, we will not actually train any models in this assignment.  This pipeline will employ an imputer class, a user-defined transformer class, and a data-normalization class.

Please note that the order of features in the final feature matrix must be correct.  See the below figure that illustrates the input and output of the transformation pipeline.  The positions of features $x_1$ and $x_2$ do not change - they remain in the first and second columns, respectively, both before and after the transformation pipeline.  In the transformed dataset, the $x_5$ feature is next, and is followed by the newly computed feature $x_6$.  Finally, the last two columns are the remaining one-hot vectors obtained from encoding the categorical feature $x_3$.
