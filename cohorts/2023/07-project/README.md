Predicting Nigerian GDP Growth Rate based on PMS Price, Average Crude Oil Price, and Consumer Price Index

1. Introduction:
The objective of my machine learning project is to develop a model that accurately predicts the Nigerian GDP growth rate. By leveraging historical data on PMS Price in naira per litre, Average Crude Oil Price in USD per barrel, and Consumer Price Index, I aim to uncover the relationship between these variables and the country's economic growth.

2. Dataset:
For this project, I utilized a comprehensive dataset containing historical information on the Nigerian GDP growth rate, PMS Price, Average Crude Oil Price, and Consumer Price Index. To ensure reliable results, I will source a dataset that spans multiple years, preferably with yearly granularity. This will enable me to capture significant economic trends and patterns.

3. Data Preprocessing:
To prepare the dataset for analysis, I performed data preprocessing steps. This includes handling missing values, removing duplicates, and ensuring data consistency. Additionally, I will conduct exploratory data analysis (EDA) to gain insights into data distributions, correlations, and identify potential outliers.

4. Feature Engineering:
Feature engineering is a vital step in improving the model's performance. To ensure my model was good I made use of MinMaxScaler so as to scale my data within a fixed ranged (0 to 1) to prevent huge flunctuations.

5. Model Selection, Training and Evaluation:
For this regression task, I will select an appropriate machine learning algorithm. 
   a. Random Forest Regression: These ensemble methods handle non-linear relationships and capture complex feature interactions.

I split the dataset into training and testing sets using an 80-20 split. The model will be trained on the training set and evaluated using appropriate metrics such as mean squared error (MSE) or R-squared. To assess the model's performance, I will evaluate it using the testing set.

6. Limitations:
This project was limited by the small amount of data present in the dataset leading to a bad mean squared error.

7. Conclusion:
In conclusion, this machine learning project aims to predict the Nigerian GDP growth rate by leveraging historical data on PMS Price, Average Crude Oil Price, and Consumer Price Index. Through data preprocessing, feature engineering, model selection, and training, I developed a predictive model that provides valuable insights into the country's economic growth trends. I also discussed the limitations of the model and potential avenues for further improvement.