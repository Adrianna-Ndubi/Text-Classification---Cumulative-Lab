# Text-Classification---Cumulative-Lab
# Overview
This Jupyter Notebook demonstrates the application of Natural Language Processing (NLP) techniques to classify text data. It includes steps for data preprocessing, feature engineering, model building, and evaluation using a machine learning pipeline. The project utilizes the Multinomial Naive Bayes algorithm to classify text into predefined categories.

## Steps Included
1. Data Preprocessing
- Tokenization, stemming, and stopword removal for text cleaning.
- Feature extraction using TfidfVectorizer for vectorization.
- Additional features engineered:
  - Number of sentences.
  - Presence of price information.
  - Presence of emoticons.
  
  2. Exploratory Data Analysis (EDA)
- Visualizations and metrics to understand class distributions and text characteristics.
Model Training and Evaluation

3. Multinomial Naive Bayes model training on the processed dataset.
- Confusion matrix to evaluate model performance.
- Comparison against a random guessing baseline.

4. Interpretation and Next Steps
- Analysis of misclassifications and recommendations for future improvements.

## Key Libraries Used
- NLP Preprocessing: nltk, pandas
- Machine Learning: scikit-learn
- Visualization: matplotlib

