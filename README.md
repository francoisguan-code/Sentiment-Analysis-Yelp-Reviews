# Sentiment-Analysis-Yelp-Reviews

Group Project for a class in Text And Social Media Analytics. 

An analysis of the local Provigo on Milton Parc by examining how various sentiment analysis approaches align with star ratings of Yelp reviews. We used and compared  VADER, Sentistrength, and a supervised KNN model in a multivariate regression, having star rating as a dependent variable. 
Results show that Sentistrength is the approach with the best fit and is the strongest predictor of customer ratings having the largest and statistically significant coefficient (0.7139). VADER also provides some meaningful insights, while the KNN model doesn’t significantly explain variation in the star ratings (with a 5% threshold). The three sentiment scores overall explain a bit more than half of the variation in star ratings, showcasing that other factors than text also impact how customers evaluate Provigo, or that our approach could be more refined. 
These results show that sentiment analysis can be a useful tool for retailers to keep an eye on customer satisfaction. These results show that sentiment analysis can be a useful tool for retailers to keep an eye on customer satisfaction. 

In a second step, we built a classifier using bag-of-words, TF–IDF and embeddings parameters to tune a KNN classifier. The objective is to identify reviews that discusses service performances. By conducting this analysis, we can further aid Provigo by predicting whether or not a review will be classified as service or not, which can help them identify important areas regarding their employees and customer experiences.

