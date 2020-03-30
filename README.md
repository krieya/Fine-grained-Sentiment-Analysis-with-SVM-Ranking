# Fine-grained-Sentiment-Analysis-with-SVM-Ranking

## Description

This task aims to classify 5-level Amazon reviews and reserve the intensity of reviews during classification.

Here is the [data source](http://jmcauley.ucsd.edu/data/amazon/)

Specifically, I compare the results of SVM regression and SVM ranking, and the evaluation metric I used is [Kendall's Tau](https://www.statisticshowto.datasciencecentral.com/kendalls-tau/) which reveals the rank correlations. 

Results are shown below:

| Dataset | SVM Regression | SVM Ranking |
|---------|-------|---------------|
| Video Games | 0.4058 | 0.4928 |
| Beauty | 0.4434 | 0.5404|
| Cellphones and Accessories | 0.4419 | 0.5501|

Using SVM Ranking effectively boosts Kendall's Tau by about 10% in the provided datasets.

## Credits

This task is designed and mentored by my instructor [Julian Brooke](https://linguistics.ubc.ca/person/julian-brooke/) in my class COLX 565 Sentiment Analysis in UBC.