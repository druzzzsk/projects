### Model for predicting caries development
This project was conducted as part of the ITMO University Megaschool in the track Artificial Intelligence in Chemistry. The aim was to explore the potential of machine learning algorithms for predicting the likelihood of dental caries development based on a patient’s oral microbiome profile.

Input data consisted of bacterial compositions retrieved from oral samples. It was hypothesized that the structure and relative abundance of various microorganisms could serve as indicators of a patient’s susceptibility to caries.

Several popular machine learning models were implemented and compared, including:

- XGBoost
- LightGBM
- Random Forest
  
Each model was trained on a dataset containing microbiological features and binary labels indicating the presence or absence of caries. The workflow included data preprocessing and cross-validation, with evaluation metrics such as accuracy, ROC-AUC, and F1-score.

Results showed that all three models achieved consistently high classification performance, confirming a clear correlation between the oral microbiota profile and caries risk. With access to larger and more diverse clinical datasets, this approach could be effectively applied in personalized preventive dentistry.
