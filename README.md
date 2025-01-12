# CS412-Project
 Fall 2024 - 2025 Machine Learning Course Project

# Contributors:
29267 - Bilal Berkam Dertli: Worked on data preprocessing and Classification task, using TF-IDF with Classic Machine Learning models. 

28962 - Cem Aydemir: Worked on Regression task, using various Regression models and hyperparameter tuning.

28946 - İsmail Zafer Özdemir: Worked on Regression task, using various Regression models and hyperparameter tuning.

32742 - Guanghui Ma: Worked on data preprocessing and Classification task, using TF-IDF with Classic Machine Learning models. 

29550 - Furkan Şafak Öksüz: Worked on Regression task, using various Regression models and hyperparameter tuning.


## Overview of the Repository:
This repository contains the code and resources for the Machine Learning course project. The project involves both **classification** and **regression** tasks, with work conducted across three rounds. Each round has a dedicated folder with the following structure:


### Round I/II/III folders:
classification_roundX.ipynb: Notebook for the classification task.

regression_roundX.ipynb: Notebook for the regression task.

### Project Report:
The repository includes a comprehensive project report named **Machine Learning Project Report** (PDF format), summarizing the methodologies, results, and analysis of the project.

### Methodology:
The project was carried out in three iterative rounds, with each iteration refining models and strategies. The following models were implemented:

- **Classification:** TF-IDF with XGBoost, Logistic Regression, SVM; **BERTurk and TurkishBERTweet** embeddings with input chunking.
- **Regression:** TF-IDF, Gaussian Mixture Models Clustering, BERT for Sentiment Analysis, Gradient Boosting.
- **Final Models:** GMM + BERT + Gradient Boosting for Regression, SVM with TF - IDF for Classification.

### Key considerations:

- Addressed class imbalance in classification tasks.
- Managed heavy-tailed distributions in regression tasks.
- Ensured data consistency and handling missing values.
- Applied strategies for handling long texts with **BERTurk** and **TurkishBERTweet**, including truncation, padding, and hyperparameter tuning (e.g., learning rate, optimizer, early stopping).
- Added sentiment analysis using BERT for regression, integrating it into a pipeline with GMM clustering and Gradient Boosting.

### Results
The results of the project are as follows:
#### Classification: 
- Evaluated using 5-fold cross-validation for average accuracy.
- **Final accuracy: 65%** using SVM with TF-IDF features.
- BERTurk and TurkishBERTweet embeddings were explored with hyperparameter tuning, but the final model used TF-IDF + SVM for consistent results.
- Example results from BERTurk (single 80-20 split) can be found at the end of this file:

#### Regression:
- Evaluated using Mean Squared Error (MSE) on log-transformed data.
- **Final model: Log MSE = 0.15**, achieved with GMM clustering, BERT sentiment analysis, and Gradient Boosting.

Detailed results, including figures and tables, can be found in the project report (PDF).

 ![image](https://github.com/user-attachments/assets/74376323-91e7-4ffc-a47e-6bebe9a29855)

