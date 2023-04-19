# Drug-Drug-Interaction-Classification
Drug to Drug Interaction Classifier

State of the Art Model for Drug-Drug Interaction utilizes Link Prediction Models. These models are work when you already have some information about the drug's interactions with other drugs. What if you don't have that data? What if you are releasing a new drug and you want to know which drugs your new drug might interact with? 

We came up with a solution of utilizing catboost to classify whether two drugs interact with one another only based on their intrinsic property and not their interaction data. After feature extraction, we came to the conclusion that ATC codes were enough to create a classifier that can classify if two drugs could potentially interact. We achieved an accuracy of 0.85 and AUC-ROC score of 0.86.
