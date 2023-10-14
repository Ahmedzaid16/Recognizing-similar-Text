# Recognizing similar Text
## This is a project using NLP to Recognize similar Text based on machine lerning 
## - Data
We Used <a href="https://www.kaggle.com/competitions/quora-question-pairs">quora-question-pairs</a> Dataset to Train our Model <br>
First we rebalanced the date because of The gab between the two classes of the data <br>
![image](https://github.com/Ahmedzaid16/Recognizing-similar-Text/assets/84353686/262fba09-fce0-4513-855d-ee104bdd0db6)
<br>
## - Cleaning data
Data clening and preprocessing is an important stage to remove unwanted and meaningless words and symbols so we shosed to do the following steps:
- Removing Null values 
- Tokenization
- Stemming
- Remove Punctuation
## - Feature Engineering
Started by selecting The most useful Features That helps the model to recognize similare text like:
- count common words
- count total words
- word length
- punctuation percentage
- count stopwords
## - Model Selection
Trained more Than one model to get the best model to oure case like:
- Decision tree
- Random Forest
-  Naive Bayes
## - Result
After training we found that the best algorithm was Random Forest With the following metrix:
<br>
![image](https://github.com/Ahmedzaid16/Recognizing-similar-Text/assets/84353686/21c78b9c-f55e-4fa7-9fa7-29954a76a359)

