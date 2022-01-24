## Prediction of Goodreads' Ratings:

The goal of this project is to predict Average ratings and decipher user interaction tools that are most important in driving users to read books based on goodreads website.

I scraped the following features:

- Title
- Author name
- Average rating
- Rating counts
- Page counts

The correlation between Page count and average rating turned out to be the highest.

correlation.png![image](https://user-images.githubusercontent.com/64047140/150881337-cc9323c2-c1a0-49ce-9329-8d529f4cbcac.png)

Predicting Average rating:

average_rating_predict.png![image](https://user-images.githubusercontent.com/64047140/150882066-1ccf954c-6db8-4d35-8023-a41b71a52ac8.png)

- MAE: 0.172722582026662
- MSE: 0.052813366663718796
- RMSE: 0.22981158948956162



This analysis was based on 181 books and 6 features. I plan to scrape more features and use more rows to make my model more precise.









