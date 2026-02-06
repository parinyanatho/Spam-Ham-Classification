SMS Spam Detection

The file we are going to use contains a collection of more than 5 thousand SMS phone messages. Using labeled ham and spam examples, we'll train a machine learning model to learn to discriminate between ham/spam automatically. Then, with a trained model, we'll be able to classify arbitrary unlabeled messages as ham or spam.

Here I am going to develop an SMS spam detector using SciKit Learn's Naive Bayes classifier algorithm. However before feeding data to Machine Learning NB algorithim, we need to process each SMS with the help of Natural Language libraries.
