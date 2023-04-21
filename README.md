# Drug-Drug-Interaction-Classification
Drug to Drug Interaction Classifier

Our solution utilizes CatBoost and link prediction to classify predict drug-drug interactions in the absence of information about each individual drug's other interactions. CatBoost predicts whether pairs of drugs interact, and we use these predictions as adjacency matrix entries for link prediction. 

This method appears to slighly outperform standalone CatBoost.

# Code

parse.ipynb contains the code for collecting features from the DrugBank database and saving them as a csv.
The catboost folder contains all the code we used to train our CatBoost model.
link_prediction.ipynb contains the code for evaluating standalone link prediction, standalone CatBoost, and our stacked model.
