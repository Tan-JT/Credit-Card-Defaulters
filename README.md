# Credit-Card-Defaulters
# Introduction
We conduct an analysis on the proposed implementation of machine learning to predict loan defaulters, reducing our losses. We first begin with an overview of the problem at hand and variables. We then explore the dataset and note relationships between variables. Furthermore, due to the unbalanced nature of the dataset, we conduct SMOTE and undersample the majority while oversampling the majority. 
We then investigate the robustness of different machine learning models on the dataset, making use of Accuracy, F1-Score and false negative rate to determine the most applicable model. Throughout, we discuss the extent of usefulness of each model. We end the report with an evaluation of our work, noting further areas of exploration and potential for improvements.

# Summary of best performing models

Model | AUC | Accuracy | Recall | F1-Score
--- | --- | --- | ---| ---
SVM + SMOTE + Boruta | 0.680 | 0.701 | **0.641** | 0.489
Random Forest + SMOTE | 0.767 | 0.798 | 0.518 | **0.534**
Boosting + SMOTE + Boruta | 0.774 | 0.8072 | 0.4846 | 0.5302
Logistic Regression + Boruta | 0.765 | 0.818 | 0.396 | 0.493
