# Amazon-Price-Prediction - Multiple Regression with Regularization


### Team Members
Eric Landstein, [Quan Nguyen][1]

[1]:https://github.com/quannguyen234

### Project Goals
To Predict if a product is likely to have a lower price in the future 
1. Scrape Data from Amazon to get current price, item, reviews and ratings 
2. Scrape camelcamelcamel for price history 
3. Commit data to mysql workbench db in AWS 
4. Predict if a product is likely to have a lower price using multiple linear regression 

### Data
scraped the movie data from https://amazon.com and https://camelcamelcamel.com

### EDA 

**Lowest Price vs Date of lowest price**
![](https://github.com/Landstein/Amazon-Price-Prediction/blob/master/images/Lowest%20Price%20vs%20Date%20of%20lowest%20price.png)

**Lowest Price vs Number Reviews**
![](https://github.com/Landstein/Amazon-Price-Prediction/blob/master/images/Lowest%20Price%20vs%20Number%20Reviews.png)

**Lowest Price vs Ratings**
![](https://github.com/Landstein/Amazon-Price-Prediction/blob/master/images/Lowest%20Price%20vs%20Ratings.png)

**Rating Count by Rating**
![](https://github.com/Landstein/Amazon-Price-Prediction/blob/master/images/Rating%20Count%20binned.png)

## Results 

**Model Predictions** 
![](https://github.com/Landstein/Amazon-Price-Prediction/blob/master/images/Regression%20Prediction.png)

![](https://github.com/Landstein/Amazon-Price-Prediction/blob/master/images/OLS%20Results.png)

### Conclusion

[Results and Conclusion ][2]

[2]:https://medium.com/@quannguyen234/too-good-to-be-true-c1fc04cb07ea