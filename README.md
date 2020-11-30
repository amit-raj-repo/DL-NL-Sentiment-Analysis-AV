# Sentiment Analysis


Hate  speech is an unfortunately  common  occurrence  on  the  Internet.  Often social media sites like Facebook and Twitter face the problem of identifying and censoring  problematic  posts  while weighing the right to freedom of speech. The  importance  of  detecting  and  moderating hate  speech  is  evident  from  the  strong  connection between hate speech and actual hate crimes. Early identification of users promoting  hate  speech  could  enable  outreach  programs that attempt to prevent an escalation from speech to action. Sites such as Twitter and Facebook have been seeking  to  actively  combat  hate  speech. 

The code above contains multiple modules:

## Data Preprocessing:
There is generally a lot of randomness in the data i.e. stopwords, '@' or 'https' etc. need to identify these and remove from the text.

## Word Cloud:
This allows us to visualize how the hate speech differ from the general text.

## Deep Learning Architecture:
I have tried out different models but the LSTM one performed the best. I intend to train my own embeddings as the the twitter data contains a lot of short hand words. I plan to get the embedding from Glove and BERT etc. will be updating the files post the trial.
