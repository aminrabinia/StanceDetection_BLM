# StanceDetection_BLM


This project downloads related tweets to #BLM and performs the stance detection task: for each tweet a label (in favor, against, or neutral) will be assigned with respect to the target (i.e. BLM).

The data is collected using Twitter's API. For the training we used the dataset for SemEval16 task 6 (http://alt.qcri.org/semeval2016/task6/index.php?id=data-and-tools). 

Our classifier is an extension of a BERT model uncased_L-12_H-768_A-12.
