# WeRateDogs (@dog_rates) - Tweet archive Exploration
## by HAMZAT ABDULRAHMAN

___
## Getting Started: Software Requirements
Jupyter Notebook

The following packages(libaries) need to be installed:
- pandas
- Numpy
- requests
- tweepy
- json
___
## Dataset
WeRateDogs (@dog_rates) is a Twitter account that rates people’s dogs with a humorous comment about the dog.
The WeRateDogs dataset (their tweet archive ) contains basic tweet data (tweet id, retweet counts, favorite counts, dog ratings, names of the dogs, and their stages (doggo,floofer,pupper and puppo) etc.
Their is an additional dataset that contains the top three image prediction results of a neural network that can classify breeds of dogs. This dataset also includes the image number that corresponds to the most confident prediction, and the respective confidence levels of the algorithm for each predictions. These image prediction results data was provided by ***Udacity*** for this project usecase in the classroom.

___
## Summary of Findings
From this dataset, using only descriptive statistics and visualizations, I produced the following insights:
1. About 85.8% of original tweets with ratings had their first image (out of a maximum of 4 images any tweet could have) corresponding to the most confident prediction. 9.58%  of tweets (with ratings) had the most confident  prediction on the second image, while 3.11% and  1.51% goes to the third and fourth images respectively.

2. 74.06% of the neural network’s most confident image prediction results are true breeds of dogs, while the remaining percentage are false.

3. The maximum retweet count (79,515) and the maximum favorite count (131,075) both belongs to a tweet that had an anonymous “doggo” dog, which scored a rating of 13/10, and it’s likely a “Labrador_retriever” or a “whippet” breed of dog according to the prediction result.
Meanwhile, there are other 260 tweets with a dog rating score of 13/10 as well.

4. The mean retweet count for all dog ratings greater than or equal to ‘10’ is three times more than the mean retweet count for all dog ratings less than ‘10’. Thus tentatively, the result shows that the number of retweets can be influenced or dependent on the dog ratings. 

5. Similarly, the mean favorite count for all dog ratings greater than or equal to ‘10’ is three times more than the mean favorite count for all dog ratings less than ‘10’. Thus tentatively, the result shows that the number of favorite counts can be influenced or dependent on the score ratings. 

6. Lastly, I found a positive correlation between retweet counts and favorite counts in the dataset.


