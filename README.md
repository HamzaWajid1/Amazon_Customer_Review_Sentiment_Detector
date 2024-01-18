# Project Title: Fine-tuning BERT on Amazon Reviews Classification

## Overview
This project involves fine-tuning a BERT (Bidirectional Encoder Representations from Transformers) model on a dataset of Amazon reviews for sentiment classification. The goal is to predict the sentiment of reviews using a five-class classification approach.

## Dataset
The dataset consists of a text column ('Text') and a one-hot encoded sentiment column ('One'). The sentiment column has five classes represented as binary vectors.

```python
Text	One
0	I have bought several of the Vitality canned d...	[0, 0, 0, 0, 1]
1	Product arrived labeled as Jumbo Salted Peanut...	[1, 0, 0, 0, 0]
2	This is a confection that has been around a fe...	[0, 0, 0, 1, 0]
3	If you are looking for the secret ingredient i...	[0, 1, 0, 0, 0]
4	Great taffy at a great price. There was a wid...	[0, 0, 0, 0, 1]
