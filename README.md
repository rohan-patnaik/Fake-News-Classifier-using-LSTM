# Fake-News-Classifier-using-LSTM
Fake News Classifier is built using LSTM for the Trump dataset from kaggle

Download the dataset from the following link :

https://www.kaggle.com/c/fake-news/submit

# Preview

I try to build a system to identify unreliable news articles from a given set of phrases and sentences.

# Steps taken
 Start by reading the data and storing it in a dataframe.
  
 ![image](https://user-images.githubusercontent.com/22250758/138297100-9a53113e-6c0a-4082-a595-e17464bb50ca.png)


 Do the basic EDA by checking for null values.
 
 We drop them in our case.
 
 ![image](https://user-images.githubusercontent.com/22250758/138297158-71c5e336-ca70-423d-acef-320b4fca3759.png)

 
 Create the datasets for storing independent and dependent variables X and y.
 
 We move on with one hot representation for our categorical variables.
 
 Next is the step to preprocess and clean the data in order to create our corpus.

 Now we assign the words in the corpus some index.
 
 Next step is to embed our doc representation to make them as array number values.
 
 The next steps are similar to a normal ML model creation.
 
 Start by building a model.
 
 Train the model.
 
 Evaluate its performance.
 
 And display its metrics and accuracy.
 
