# IMDb Movie Review using logistic regression
---

## Imported Pandas and scikit-learn
Pandas for importing csv file and mapping the sentiment to 1 and 0
scikit-learn is the main backbone for this logistic regression, accuracy_score and as well as Countvectorizer

## Pandas Used
Used pandas to open csv file and marking X as the array of the reviews given and Y as the 0 or 1 based on if its positive or negative respectively

## Vectorization Used
Used sckilearn's module which tries to implement the vectorisation of the strings so its easier for the ML to learn. Here by using stop_words='english', i am trying to remove common words to be added to the vectorization.

## Training and testing data split
Using skitlearn's model, we splited the data in the ration 2:8 for 20% of data to be used for testing and others for training ig. Random set is set to 2 so that the code can be repeatable and still not change (setting the random seed).

## Logistic Regression
Using skitlearn's model, we directly used Logistic regression model and added max_iter as 1500 which means how long should try to find best optimizer, which iteratively try to find the best coeff. and thus find min error. The coeff here is mainly biases and weights. 

## Precting and accuracy
Using skitlearn's model, we try to predict using Logistic regression model and thus try to accuracy percentage!

---

