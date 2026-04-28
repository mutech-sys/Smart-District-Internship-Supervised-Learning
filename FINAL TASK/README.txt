DATASET:
The dataset used was california housing. with 9 columns and 20,640 rows. After cleaning the dataset contained 7 columns. There were no missing values and duplicate values. The target columns was Price.
Scaled the data using StandardScaler.
EDA showed: 
    - HouseAge Distribution was binomial.
    - AveRooms, AveBedrms, and Population outliers support each other.
    - MedInc strong positive correlation with price.
    - HouseAge and Population has negative correlation


The ridge regression performed better other models. This is because it reduced the less correlated values and did not completely eliminate them.