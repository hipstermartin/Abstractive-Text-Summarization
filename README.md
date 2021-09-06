# Abstractive-Text-Summarization

The basic idea behind abstractive text summarization is to be able to extract a short subset of the most important information from a large set and present it in a human-readable format. As the amount of textual data on the internet grows, automatic text summarization methods have the potential to be very useful because more useful information can be read in a shorter amount of time.

## PROPOSED SYSTEM 

### 1. Preprocessing and Dataset

Within this particular project, we trained the model on Kaggle's Amazon Fine Food Reviews dataset, containing 500,000 reviews, generally used for training models for abstractive summarization from 1999 through 2012. We have drawn up 80% data and summaries during preprocessing and trained the model to predict the abstract summary following the user review.

Ref: https://www.kaggle.com/snap/amazon-fine-food-reviews/download

### 2. Model

A Three Layer Stacked LSTM Encoder-Decoder model with Global Attention Mechanism was used during implementation. On the training set, the algorithm was able to achieve an accuracy of 77.27 percent using this model (constituting 80 percent of the dataset). This model also achieved a cumulative BLEU-4 score of 0.8800 on the test set.

### Stay Up to date
It is important for you stay up to date with the new improvements, latest updates and bug fixing. Ensure to Star( * ) the project on Github and get notified whenever any update coming.

## That's all folks!
Feel free to mail me for any doubts/query 
:email: abhi.yalamaddi@gmail.com


Feel free to **file a new issue** with a respective title and description on the the [Abstractive Text Summarization](https://github.com/hipstermartin/Abstractive-Text-Summarization/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! 
