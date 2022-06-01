# HW2-RNN
Notebook for HW2- Knowledge Discovery 

## Description
A model in which we use recurrent neural networks, and in particular LSTMs, to perform sentiment analysis that consists into determine the sentiment behind a text. Therefore, in this kind of application we have many sequences as input and we get one label as output. In our case we have three target: "Positive", "Neutral" and "Negative".
In RNNs, which are particularly useful when we have arbitrary lengths, we need a memory that at each step takes into account the decision of a previous step. In particular, at each time stamp we have a blackbox in order to pass into the other timestamp the information about decision taken in a state vector that encodes this information in a memory and pass it to the next step. If we unfold this vision, we get the RNNs and we unfold as many time as the points we have in our sequence.
![image](https://user-images.githubusercontent.com/102547301/171500398-dace134d-6ffb-481b-9fca-7f39328661a0.png)

## Dataset
Data we have used in our model:

https://drive.google.com/file/d/1o5MUso55NfTymcO_KsWAaLLd7py4yU6Q/view?usp=sharing

These data are taken from Kaggle:

https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis?select=twitter_training.csv

On Drive you have the data already split in train and test set.

## Contacts
Fabiana Monaco - fabianamonaco96@hotmail.com

Federico Puglisi - federico.puglisi10@gmail.com
