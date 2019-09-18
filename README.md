# Manufacturing-Line-I4.0

Shop floor is always have challenges. When the part fails at the end of line testing, you instinctively retrace your steps to identify at what point you went wrong. The ML based algorithm is closely monitoring the parts as they progress through the manufacturing processes. So that the defective parts can be intelligently identified.

The data represents measurements of parts as they move through production lines. Each part has a unique Id. The goal is to predict which parts will fail quality control (represented by a 'Response' = 1).

The dataset contains an extremely large number of anonymized features. Features are named according to a convention that tells you the production line, the station on the line, and a feature number. E.g. L3_S36_F3939 is a feature measured on line 3, station 36, and is feature number 3939.

On account of the large size of the dataset, we have separated the files by the type of feature they contain: numerical, categorical, and finally, a file with date features. The date features provide a timestamp for when each measurement was taken. Each date column ends in a number that corresponds to the previous feature number. E.g. the value of L0_S0_D1 is the time at which L0_S0_F0 was taken.

**Description**

train_numeric.csv - the training set numeric features (this file contains the 'Response' variable)

test_numeric.csv - the test set numeric features (predict the 'Response' for these Ids)

train_categorical.csv - the training set categorical features

test_categorical.csv - the test set categorical features

train_date.csv - the training set date features

test_date.csv - the test set date features
