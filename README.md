# Fake News Detection
The NLP project submission to a DataCup Competition ["Leaders Prize: Fact or Fake News"](http://leadersprize.truenorthwaterloo.com)

is based on "Leaders Prize: Fact or Fake News" Competition (http://leadersprize.truenorthwaterloo.com). The goal of this competition is to develop a classification model that automate the fact-checking process and flag whether a claim is true, partly true or false.

## Problem Overview
The goal of this competition is to develop a classification model that automate the fact-checking process and flag whether a claim is true, partly true or falsebased on some related articles and the metadata associated with each claim.

## Solution
Firstly, the text data are initially cleaned while applying stemming which are processed into a TF-IDF representation. The featurized vectors along with various features such as claimants were concatenated and were used to feed into the model.

The Naive Bayes classifier is selected as the final model which yielded F1 score of 46.9%, placing 22nd amongst 74 contestants.


## Related Files:
* ["Presentation"](https://github.com/seok0704/fake-news-datacup/blob/main/Fake%20News%20Deck.pdf)
* ["Notebook"](https://github.com/seok0704/fake-news-datacup/blob/main/CourseProject.ipynb)
* ["Report"](https://github.com/seok0704/fake-news-datacup/blob/main/Group%235_ConsultingReport_CourseProject_MIE1624H1.pdf)
