# OKCupid-Date-a-Scientist
This machine learning project is built based on file **profiles.csv**. It contains data about users of dating site **OkCupid**. 
File was too big to upload on GitHub so if you want to get it just dm me. Project was made in Jupyter Notebook using Python and some basic Data Science librarys like Pandas and NumPy. 
For building a model I choose Naive Bayes classifier, In my opinion it is one of the best model for working with text data.
I used scikit-learn library to create vectorizer *CountVectorizer()* ([This is how it works](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html))
to create an array of all words used in df and classifier *MultinomialNB()* ([documentation here](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html)).
To summarize I created 3 models:
1. Predicting sex of the user based on profile description - with accuracy 75%
2. Predicting status of the user based on profile description - with accuracy 92%
3. Predicting user sexual orientation based on profile description - with accuracy 85%
