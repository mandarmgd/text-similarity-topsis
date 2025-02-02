# Text Similarity 

Data set link - [https://www.kaggle.com/datasets/rishisankineni/text-similarity](https://www.kaggle.com/datasets/rishisankineni/text-similarity)

Predicting text similarity between two texts (similar or not) by taking both lexical and semantic similarities into consideration, and using multiple machine learning models. 
- Jaccard Similarity was used to find lexical similarities
- Word2Vec text embeddings and Cosine Similarity were used to find semantic similarities 

Then, the models were evaluated using several classification metrics, and finally ranked using TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)
TOPSIS package used - Topsis_Mandar_102203163 
PyPI - [https://pypi.org/project/Topsis-Mandar-102203163/](https://pypi.org/project/Topsis-Mandar-102203163/)
GitHub - [https://github.com/mandarmgd/topsis](https://github.com/mandarmgd/topsis)

## Models used 

- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors
- Decision Trees
- Random Forest

## Metrics used 

- Accuracy
- Precision
- Recall
- ROC-AUC 
- Log-loss 
