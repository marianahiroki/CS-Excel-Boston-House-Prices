# CS-Excel-Boston-House-Prices
This repository comprises data visualizations and statistical analyses of the Boston House Prices Dataset, created as part of the L3 Data Essential Skills Bootcamp in 2023. 

## Introduction: ##
- Analyse the relationship between various features of Boston's house prices and the housing market, perform data analysis and generate insights.
- The dataset used is sourced from Kaggle: ([Boston House Prices-Advanced Regression Techniques](https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data/data)), published in a book in 1978.

## Problems and Solutions: ##

- What is the correlation between the number of rooms and the median value of owner-occupied homes?
  After calculating the Pearson correlation coefficient between the number of rooms and the median value of owner-occupied homes, I found a positive correlation of 0.69. This indicates a strong positive linear relationship, suggesting that as the number of rooms in a home increases, the median value of owner-occupied homes also tends to increase.
  
- Which variable has the highest correlation with the median value of owner-occupied homes?
  After calculating the Pearson correlation coefficients between the median value of owner-occupied homes (MEDV) and each variable in our dataset, I found that variable RM (number of rooms) has the highest correlation with MEDV, with a correlation coefficient of 0.69. This indicates a strong positive linear relationship between RM (number of rooms) and the median value of owner-occupied homes.
  
- What is the average age of the homes?
  The dataset includes a variable 'AGE,' which represents the proportion of owner-occupied units built before 1940. This attribute provides insights into the historical distribution of home construction periods, but it does not explicitly capture the actual age of the homes at the time of the dataset's publication in 1978. For a more accurate assessment of the average age of homes in 1978, additional historical context or specific data on construction years would be required.
  
- What is the distribution of the pupil-teacher ratio by town?
  The distribution of the pupil-teacher ratio by town is summarized as follows:
  **Central Tendency:** The mean pupil-teacher ratio is 18.45, indicating the average ratio across towns.
  **Spread:** The standard deviation is 2.16, illustrating the variability of pupil-teacher ratios.
  **Visualization:** The distribution is visualized through a histogram, showing the frequency of different pupil-teacher ratio ranges. Additionally, a box plot provides insights into the spread, median, and potential outliers within the data.
  In the Boston Housing dataset, which is often used for studying housing and neighbourhood characteristics, the pupil-teacher ratio is included as one of the variables to provide insights into the educational landscape of different towns in the Boston area. Researchers and policymakers may analyze this variable in conjunction with other features to explore potential relationships between education, neighbourhood characteristics, and housing values.

For example, a higher pupil-teacher ratio might be associated with resource constraints in schools, potentially impacting the quality of education. On the other hand, a lower pupil-teacher ratio may suggest better-funded schools with more individualized attention for students.
  
- Which town has the highest median value of owner-occupied homes?
  To find the town with the highest median value of owner-occupied homes in the Boston Housing dataset, you would typically look for the entry with the maximum value in the "MEDV" (Median Value of owner-occupied homes) column. The dataset does not provide the town's names, therefore I could only filter the the values for this specific town as the image shown below.
  
- Please see the Excel screenshots below that also answer the questions.

<img width="902" alt="image" src="https://github.com/marianahiroki/CS-Excel-Boston-House-Prices/assets/110165879/82bfbc8c-f716-4b79-99c3-a0f678cd24f7">

<img width="452" alt="image" src="https://github.com/marianahiroki/CS-Excel-Boston-House-Prices/assets/110165879/e091bf40-466d-47af-a798-4d1eaddec26f">



## Conclusion: ## 


## Next steps: ##
