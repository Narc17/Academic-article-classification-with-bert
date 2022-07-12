# Academic-article-classification-with-bert
This is my work for a local Kaggle cometition in the course "Special Topics in Machine Learning" from Computer Science and Inform Engineering Department in National Taiwan University.

## Competition Goal
The goal of this competition is to classify academic articles from their abstracts into 4 categories: ***Theoretical, Engineering, Empirical*** and ***Others***.

## Solution
The solution I implemented is to fine-tune BERT with random noise augmentations. During the training process, dataloader randomly replaces 15% tokens in each sentence with <UNK> tokens. It results with 69.77% accuracy on local testing data.
