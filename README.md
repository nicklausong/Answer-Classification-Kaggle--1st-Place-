# Answer Classification Kaggle (1st Place)
 Notebooks used for in-class kaggle competition for module BT4222 Mining Web Data for Business Insights. Obtained 1st place out of 61 students. The objective is to build a binary classification model to classify whether a given answer to a question is a good answer or not. In the final solution, intuitive text preprocessing that maintained the integrity of answers that contained coding was used. Final model used was an ensemble of uncorrelated models, LightGBM, CatBoost and Neural Networks that were tuned for hyperparameters.

 Link to kaggle competition: https://www.kaggle.com/c/rating-classification/leaderboard

![alt text](Leaderboard.png)

# Overview Of Notebooks
1. Preprocess.ipynb contain the feature engineering steps, such as punctuation count and part of speech tagging.
2. Exploratory Data Analysis.ipynb to visualise distributions, feature analysis, and correlations.
3. Final Models.ipynb, containing final ensemble of LightGBM, CatBoost and Neural Networks, as well as an exploit of a data leakage due to in depth data analysis.
4. Also highly crucial are the notebooks found in Hyperparameter Tuning, where I tuned hyperparameters of text preprocessing, and optimized the model parameters of LGBM and Neural Networks.
5. In folder Other Models, I also attempted using Stanford's GloVe 100d word embeddings for LSTM, XGBoost using bag of words, and a novel method of enhancing test predictions called pseudo labelling. Unfortuneately, these models did not outperform the other models included in the final solution.