# FINAL PROJECT: BOSTON HOUSING MACHINE LEARNING

 
When looking into sourcing our dataset for our final project, we took a deep dive into the Scikit-Learn libraries for Machine Learning in Python. After discussing and considering how we wanted to proceed as a group, we elected to go with 'sklearn.datasets.load_boston' as our dataset of choice. We see this as a dataset worth exploring, analyzing, and visualizing. 

We will be using Python Pandas, and Python Mathplotlib, in addtion to other technologies we have learned within our notebook to further analyze the data. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------

The Boston house prices dataset contains 13 numeric/categorical predictive attributes, including:

 - CRIM: per capita crime rate by town [renamed to Crime]

 - ZN: the proportion of residential land zoned for lots over 25,000 sq.ft. [renamed to Zone_Proportion]

 - INDUS: the proportion of non-retail business acres per town [renamed to Non_Retail_Proportion]

 - CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise) [renamed to Charles_River]

 - NOXL: nitric oxides concentration (parts per 10 million) [renamed to Nitric_Oxide]

 - RM: the average number of rooms per dwelling [renamed to Average_Room]

 - AGE: the proportion of owner-occupied units built prior to 1940 [renamed to Unit_Age]

 - DIS: weighted distances to five Boston employment centres [renamed to Distance_To_Centre]

 - RAD: index of accessibility to radial highways [renamed to Highway_Access_Index]

 - TAX: full-value property-tax rate per $10,000 [renamed to Property_Tax_Rate]

 - PTRATIO: pupil-teacher ratio by town [renamed to Pupil_Teacher_Ratio]

 - B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town [renamed to Blacks_By_Town]

 - LSTAT: % lower status of the population [renamed to Lower_Status]

 - MEDV: Median value of owner-occupied homes in $1000's [renamed to Median_Home_Value]

-----------------------------------------------------------------------------------------------------------------------------------------------------------
 
The original dataset was created by Harrison, D. and Rubinfeld, D.L., and was taken from the StatLib library, which is maintained at Carnegie Mellon University. 
 
Given the sources disclosed when using the describe method, it can be assumed that this data was gathered from Boston housing-price data collected within the years of 1978-1992. 
