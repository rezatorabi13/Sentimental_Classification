### Sentiment classification task for hotel reviews
Sentiment Analysis is the most prominent branch of natural language processing. It deals with the text classiﬁcation in order to determine the intention of the author of the text. Here, I used data for hotel reviews with rating from 1 to 5. There are 3 sets of data (train, dev, and test). Using train and dev data, we train the model to predict the rating for test data (which has no rating).

### Methods
We use two methods in here:
    1- Naive-Bayes model
    2- LinearSVC model
In Naive-Bayes and LinearSVC models, first we train the model using the default parameters. After that, we tune the hyperparameters to improve the accuracy. Finally, a GrideSearch is used to find the best parametes.
    

### Result
The best accuracy was obtained for LinearSVC model (after tunning the hyperparameters) which is **%76.4**.

the predicted ratings for test data can be found in "prediction.xlsx" file.
