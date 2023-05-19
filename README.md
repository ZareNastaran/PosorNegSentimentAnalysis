# PosorNegSentimentAnalysis
In this project, I developed a model that can determine if a sentence is positive or negative with good accuracy. The dataset that I worked with, was IMDB movie reviews.

# Data Preprocessing

For the aim of data prepration, I tokenized the sentences, removed the stop words, punctuations, and also regarding th POS, I just keep the adjectives. Because the adjectives mostly determine if the whole sentence is positive or negative. 

# Classification

For this part, I used different classifier to determine if the adjective is positive or negative. It means, if the adjective is positive, I would say the whole review is positive and vice versa. This can be baised as people can use positive adjective with a negative meaning, for example, I can say, "The movie lacked pretty actors" This review is negative, but the adjective, "pretty", is positive. Or in some case, there can be slangs or sarcasam that make this task even harder.

Calssifiers that I used from nltk classifers: NaiveBayes, logistic regression, svm, bernouli, multinomial naive bayes, SGD, and SVC.

# Evaluation

For evaluation, I use accuracy metric from sklearn library.

