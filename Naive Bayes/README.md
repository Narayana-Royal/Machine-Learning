# Naive Bayes
> It calculates the probability of target classifiers upon given instance input and whichever probability (target classifier with instance) have high value it classifies to that target classifier. for example : + , - : Target classification values .. P(+/instance) and P(-/instance) is calculated and that instance is calssified based on highest value among both.


> Types of Naive Bayes Classifiers that are used to Create Models
> GaussianNB - continuous data. (example - 0.123,1.4,6.7,9.9,10,99)

> MultinomialNB - descrete data. (example - 0,1,2,3,4,5...)

> BernoulliNB - Binary data. (example - 0,1)


> Also for texted sentence feature, we use count vectorizer to change it to numerical form. Working: Countvectorizer takes unique words of documents and make a dataframe as value 1 where the document has found that particular word.


