## Tasks for Lab 4 Assignment:-

# Task 1:
The dataset contains no missing values or duplicate records. However, it includes one categorical feature **Gender** that requires encoding before analysis.

# Task 2:
After checking the dataset, and no missing values were found in any column. Therefore, no missing value handling strategy was required.

# Task 3:
The IQR method was applied to the numerical features: Age, Annual Income, and Spending score. Any values falling outside the calculated calculated lower and upper bounds were identified as outliers. 

# Task 4:
Min-Max normalization and Z-score standardization were applied to the numerical features(Age, Annual Income, and Spending score). Min-Max scaling transformed values into a 0-1 range, making features comparable in magnitude. Z-score normalization standardized the features to have a mean of 0 and standard deviation of 1.

# Task 5:
PCA was applied to the standardized numerical features. The first principal component captured the highest variance in the dataset. The first two principal components together explained the majority of the variance.

