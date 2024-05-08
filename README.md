###STOCK PRICE PREDICTION BASED ON NEWS SENTIMENTS USING LSTM AND GRU

##Introduction:

Machine/Deep Learning are popular methods in finanancial data analysis. Stock price prediction is a complex task due to several influencing factors. In order to cater the "News Factor" this project
proposes a method to calculate the sentiments scores of news from different channels and then use LSTM and GRU networks to predict the stock prices. Lastly, it would integrate the ensemble learning
in order to produce the most accurate prediction from both the models. 

##How to run this repository?
execute the following commands:

-git clone https://github.com/alpha0352/StockPricePrediction_DLPProject.git
then start the terminal in cloned folder and run,

-pip install -r requirements.txt

This will setup the entire enviornment to run.

Now for the news extraction from each site, we need to run the extraction code for each news channel website.
Run:
-CNBC_newsextract.ipynb
-Fortune_newsextract.ipynb
-WSJ_newsextract.ipynb

then for the sentiment analysis of news run,

-SentimentAnalyzer.ipynb

Finally, we can execute "main.ipynb" file. 

The execution of main.ipynb consists of all the main process of data pre-processing, models definition, model training and predictions.

##Collaborators:

This project was done by the help of teams members:
Ali Ahmed (20K-0140)
Muhammad Rafay (20K-0180)
Anas Ali (20K-0352)

