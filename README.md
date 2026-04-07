# hybrid-embed4tox-pred
Machine Learning with Hybrid Fingerprint- Embedding Strategy to predict drug toxicity
welcome to start your drug toxicity prediction with my code.
first, you need a drug property file like tox 21.csv which act as a learning data for your model.
then, you embed drug formulas into ecfp+chemberta strings using smiles2matrices.ipynb to get a data frame as final_df.csv
finally, ecfp+chemerta.ipynb builds deep learning models. models in this code file is preliminarily tested to have good performance.
you can use these models to predict a ramdom drug with its formula in SMILES string.
