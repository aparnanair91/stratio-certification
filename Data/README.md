DATA

There are two datasets (internal and external) used for this use case

1.	German Credit 
Description: There are two internal datasets used namely german_credit_list.csv and german_credit_data.csv. 
german_credit_data.csv is used as a training set for building a model.  It has columns mentioned below including the target variable called ‘Risk’ column. The relationship of target variable with other columns are statistically analysed , to select valid feature columns. These feature columns are given as an input to the model. This dataset has a mixture of continuous numerical values and categorical column values. 
german_credit_list.csv is used as a testing set for executing the model build. Unlike other dataset, this list do not have target variable and it is obtained from the model prediction.

2.	External Dataset
Description: This is an external dataset called externalList.csv. The external data set is used for applying business rules and classifying the model predicted risk into different class labels like Red, Green and Yellow. 
