---
title: "Classifying Reading-Level Difficulty from Text"
excerpt: "Trained a binary classifier to predict age suitability of text excerpts with 70% AUROC accuracy. First attempted a Bag of Words feature representation, then improved performance with our open-ended solution.<br/><a href='/files/ML_Project_A.pdf' target='_blank'><img src='/images/ML-Project-A-Report-Snapshot3.png' style='max-width:300px; height:auto; margin-top:20px; margin-right:20px;'></a><a href='/files/ML_Project_A.pdf' target='_blank'><img src='/images/ML-Project-A-Report-Snapshot.png' style='max-width:300px; height:auto; margin-top:20px; margin-right:20px;'></a><a href='/files/ML_Project_A.pdf' target='_blank'><img src='/images/ML-Project-A-Report-Snapshot2.png' style='max-width:300px; height:auto; margin-top:20px; margin-right:20px;'></a>"
collection: portfolio
---

*See the full report here:* [Classifying Reading-Level Difficulty from Text](/files/ML_Project_A.pdf)

The goal of this month-long project was to explore the possibility of automatic assessment of reading level. Accurate automatic assessment of reading level could empower students to select more possible materials (recent novels, current event articles) while being confident the difficulty of the text remains in reach.

Working through various methods, hyperparameter configurations, and feature representations, my partner and I built one of the top-performing classification models in our machine learning class. Our final model leveraged Google's BERT embeddings, alongside a grid search and neural network, to achieve impressive predictive power with limited training data.

Our dataset comes from research work by Jordan J. Bird, released in December 2024. His raw dataset, UK Key Stage Readability for English Texts is [available on Kaggle](https://www.kaggle.com/datasets/birdy654/uk-key-stage-readability-for-english-texts) under an MIT license.

<a href='/files/ML_Project_A.pdf' target='_blank'><img src='/images/ML-Project-A-Report-Snapshot3.png' style='max-width:300px; height:auto; margin-top:20px; margin-right:20px;'></a><a href='/files/ML_Project_A.pdf' target='_blank'><img src='/images/ML-Project-A-Report-Snapshot.png' style='max-width:300px; height:auto; margin-top:20px; margin-right:20px;'></a><a href='/files/ML_Project_A.pdf' target='_blank'><img src='/images/ML-Project-A-Report-Snapshot2.png' style='max-width:300px; height:auto; margin-top:20px; margin-right:20px;'></a>