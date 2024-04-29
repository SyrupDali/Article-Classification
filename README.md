## Challenge
In this challenge you are expected to train a classifier that will be able to classify medium articles into one of three categories: 'software-development', 'artificial-intelligence' and 'ux'.

We provide a dataset of medium articles which have to be tagged to corresponding topics (software-development, artificial intelligence, Ui/UX). Along with articles we have subscriptions lists. The subscription lists are reading lists and the articles may be related by common subscription lists. The goal is to exploit this naturally occurring network structure for classifying articles to topics. Hence, it is a 3-way node classification task. 


## Addition
This was an assignment from Data Mining course. The faculty posted the assignment as a Kaggle Competition to evaluate the algorithm we implemented. We categorized medium articles to topic tags leveraging the network structure arising from relation using subscription lists and the distances in semantic space. The Jupyter notebook is /data/pipeline_assignment_updated.ipynb
