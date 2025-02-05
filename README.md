# Logic and Language project code

This code provides the rule-based model developed for the paper “Detecting inference patterns in SNLI”. The model can be run using the run_patterns() function and provides the precision and coverage results of the model tested on SNLI’s test dataset. Here, covered examples are those that satisfy at least one pattern, and hence received a label from the model.

The precision and coverage results of each pattern on the training dataset we used, are retrieved in the section “Precision and Coverage on Training Data”.  To make sure that the training data remains the same, the file "sampleKeysLoLa.txt" should be in the same repository of the .ipynb file.

The last section provides the code to plot the Jaccard similarities between the different inference categories.

