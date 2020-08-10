# Kaggle-project-Begin-NLP
## Problem 
A hotel was collecting reviews and ratings from its customer in order to improve its performance. Due to lack of time, some of the customers only provided reviews and skipped ratings. 
## Data
Data: It had two columns “Reviews” and “Ratings”. 
Reviews: These were the reviews provided by customers.
Ratings: These were the ratings ranging from 1 to 5.
## Solution 
The hotel wanted to anticipate the missing ratings by the type of reviews provided by its customers. 
I used the labelled data (Reviews + Ratings provided) to train a classification model with high accuracy on the labelled dataset and then I used the model label the unlabelled data.
Why: The data size of the data was less for the labelled data as compared to the unlabelled data. I tried multiple pre-trained models whose accuracy was not too good but to my surprise multinomial logistic regression gave the best accuracy. I learned that sometimes simple models are the best in complicated problems.


