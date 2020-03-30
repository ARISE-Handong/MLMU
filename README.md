# MLMU
MLMU Training Data

## Data

Each expression label has input data of 20 or less tokens that comes before the expression and 20 or less tokens that comes after the expression.

The number of the target classes is 2359 and each class has an identification number (ID#)

Expression labels for each class is saved in data/ID#\_expr
The preceding and succeeding tokens for Nth expression of ID# class is saced in Nth line of data/ID#\_pre and data/ID#\_succ

