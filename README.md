# Climate-Change-Misinformation-Detection
Although there is ample scientific evidence on climate change, there is still a lingering debate over fundamental questions whether global warming is human-induced. One factor that contributes to this continuing debate is that ideologically-driven misinformation is regularly being distributed on mainstream and social media. The challenge of the project was to build a system that detects whether a document contains climate change misinformation. The task is framed as a binary classification problem: a document either contains climate change misinformation or it doesn’t. The caveat of the task is that we only have training documents with positive labels. That is, the training documents provided are articles with climate change misinformation only. 

The files that have been attached are described below:
1. train.json -: This json file consists of the training articles, along with their labels. The training data contains only misinformed articles.
2. dev.json -: This file contains a development/evaluation data set with a small number of data points, which will be used as a validation set to regularize our training models. The data points contained in this file belong to both the classes.
3. test-unlabelled.json -: This is the test data, for which we have to predict the labels after training our models. 
4. dev-baseline-r.json -: A baseline model on the validation set.
5. scoring.py -: The scoring criteria defined for a competition that was running on 'Codalab' during the course of the project. 
6. projectNLP_2 (1).ipynb -: The python code for the final model. 
7. NLP_1041953.pdf -: The final report submitted along with the code, which defines the process in entirety, for achieving good results in the classification problem. 

