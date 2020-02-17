# Major_Project
Importing the 20NewsGroups dataset consisting of 11314 articles in the training dataset and 7532  articles in the test dataset accross 20 classes.
  		fetching training and testing data.

Next we Vectorize the articles in the Corpus.For this we use sci-kit learn's CountVectorizer to create a sparse matrix of the count of each word in an article.For better results we then calculate the inverse term frequency for the words using sci-kit learn's TfidfTransformer.
		20 classes
		sparse matrix
Having got the sparse matrix, we would now apply classification Algorithms on this vectorized word matrix to predic classes for data in test dataset.
		

Starting with K-Nearest Neighbours
 		Accuracy and
		time to predict tesing and training data

Next we apply Support Vector Machine algorithm
		Accuracy and
		time to predict tesing and training data

Next we apply Naive Bayes
		Accuracy and
		time to predict tesing and training data
All this while we used Bag-Of-Words technique to vectorize the dataset.
Here we apply ngrams technique to create the sparse matrix. Let's have an example as how n-grams is differnt from Bag-of-Words and what it actually does.
		Bag-of-Words
		Bi-grams
		Tri-grams    sparse matrix.
What if we need to apply Bag-of-2grams, or in other words club two consecutive words in a document, then vectorize.
		Bag-of-2grams
		Time take to vectorize the training data.
Now we will apply n-grams on our dataset and will then apply SVM classification algorithm. We will compare the accuracies for uni-gram, bi-gram and tri-gram vectorization on character level.
		character level n grams
Now we apply N-Grams with Naive Bayes Classifier.
		Time take to Vectorize training data and train model
		Time take to predict classes for Test data
		Accuracy
Now applying Bag-of-1gram(Same as bag of words), Bag-of-2grams and Bag-of-3grams to our dataset this time grouping words together instead of characters.
		word level n grams.
Now we apply Word level CNN on the same dataset and calculate accuracy.
		sequential 1		
		test accuracy.
		Time take to Predict classes for testing data.
Now we apply CNN on data pre processed with N-Grams, taking value of N as 2.
		sequential 2.
		test accuracy.
		Time take to Predict classes for testing data.
