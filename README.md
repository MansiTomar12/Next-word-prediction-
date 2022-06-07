# Next-word-prediction-
Most of the keyboards in smartphones give next word prediction features; google also uses next word prediction based on our browsing history. So a preloaded data is also stored in the keyboard function of our smartphones to predict the next word correctly. In this article, I will train a Deep Learning model for next word prediction using Python. I will use the Tensorflow and Keras library in Python for next word prediction model. Google uses our browsing history to make next word predictions, smartphones, and all the keyboards that are trained to predict the next word are trained using some data.
After reading and splitting the data into each word as a single string in the form of list. Now the next process will be performing the feature engineering in our data. For this purpose, we will require a dictionary with each word in the data within the list of unique words as the key, and it’s significant portions as value.

---
 <br />
 
**Feature Engineering**
Feature Engineering means taking whatever information we have about our problem and turning it into numbers that we can use to build our feature matrix.Here I will define a Word length which will represent the number of previous words that will determine our next word. I will define prev words to keep five previous words and their corresponding next words in the list of next words.

 <br />
 
**Building the Recurrent Neural network**
As I stated earlier, I will use the Recurrent Neural networks for next word prediction model. Here I will use the LSTM model, which is a very powerful RNN. Using LSTM model is preffered as it is the best fit for the prediction models. After this, the model will be trained.

 <br />
 
**Evaluating the Next Word Prediction Model**

 <br />
 
*Model Accuracy*

 <br />
 
 
![alt text](git1.jpg)

 <br />
 

*Model Loss*
![alt text](git2.jpg)
