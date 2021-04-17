# Eluvio_DS_Challenge
Sentiment Analysis over News Articles

* Loading the Data from the Drive Link
* Subset the Data with two features - up_votes , title
* Derived a new feature based on the condition ( upvotes less than or equalto 4 as negative and > 4 as positive )
* split the data into train and test data
* preprocess all the titles using the function process_tweet() i.e Removing symbols , urls , tickers , hashtags , etc
* convert them into Tokenized vectors i.e string of tokens
* Then Removing the stop words and converting the words into their  base form using stemming
* creating a dictionary mapping each pair into frquency using build_freqs()
* defining sigmoid and gradientdescent algorthim
* create a feature vector of dimension (3, 1) - (Bias , positive sentiment , Negative sentiment)
* initilize the weights as 0 as per the shape of input
* Train the model using gradient descent Algorthim 
* create a function to predict the titles and test the data using test_logistic_regression()


** cons** 


