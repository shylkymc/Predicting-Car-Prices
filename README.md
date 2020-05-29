# Predicting Car Prices

In this project, I used a car data set to make predictions on cars' prices. The data set has data from different car brands. I used Pandas and Numpy libraries to open and prepare the data set to predict. I cleaned missing values. Especially, I deleted missing values from the "price" column to use it on my prediction. I filled the other missing values while using the mean of the columns. 
<br>
I used knn classification models with Sklearn library. I found random mean squared errors to test my models' performance. I developed my models step by step. In the first step, I developed models to make predictions on one column without a k value. After that I improved the knn model to make predictions on one column and with multiple k values.  I used Matplotlib library to visualize the "RMSE" values for every k value. In my last step, I improved the knn model on multiple columns while using multiple k values. I created 5 features, each with a set of columns, starting with 2 and increasing to 6. As a result, I succeded in increasing the "RMSE" value while increasing the k value on multiple columns. 
  
