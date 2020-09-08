# OCVED-ML
 Scripts for generating the models used in Osorio & Beltran (2020)

More information on the paper and results available at ocved.mx

Script 1: OCVED_GSR_Trained_v2_4.ipynb
    This script preprocesses the text for OCVED, cleans out accents and runs various ML models including the logistic regression used in the paper.

Script 2: OCVED_CNN_v2_1.ipynb
    This script runs the convolutational neural networks used in the paper. It uses the preprocessed text from the first script.

Script 3: Pending BERT script
    I am still cleaning out the script, Bert takes a while to run and I haven't finished cleaning out the script.

Script 4: OCVED_Applied_v2.ipynb
    This is the final script that applies the LR model from script 1 on the entire universe of articles scraped from EMIS. It applies the model and tf-idf saved from script 1. 
