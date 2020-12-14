# Toxic Comment Classification

## Dataset Overview
The threat of abuse and harassment online prevent many people from expressing themselves and make them give up on seeking different opinions. In the meantime, platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments. Therefore, Kaggle started this competition with the Conversation AI team, a research initiative founded by Jigsaw and Google. The competition could be found here: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

Being a human, it is essential to make online discussion more productive and respectful, I determined to work on this project and aim to build a model that is capable of detecting different types of toxicity like threats, obsenity, insults, and identity-based hate.

The dataset we are using consists of comments from Wikipedia’s talk page edits. These comments have been labeled by human raters for toxic behavior. The types of toxicity are:

- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

There are 159,571 observations in the training dataset and 153,164 observations in the testing dataset. Since the data was originally used for a Kaggle competition, in the test_labels dataset there are observations with labels of value -1 indicating it was not used for scoring.

## Model Overview
Algorithms from ML and DL are used. Also, the model successfully deployed on Heruko using flask framework.

Deployment Link - https://toxic-comment-classifier-api.herokuapp.com/
