# Model Evaluation for Fake News Classification

This repository contains code for evaluating different machine learning models for classifying fake news. The dataset used for this evaluation consists of labeled news articles as either "REAL" or "FAKE". Three popular classifiers, Support Vector Machine (SVM), Decision Tree, and Logistic Regression, are trained and evaluated on this dataset.

## Data Preparation
The dataset is preprocessed to convert the raw text data into numerical feature vectors using the TF-IDF vectorization technique. The processed data is then split into training and testing sets.

## Model Training and Evaluation
### Accuracy
The accuracy of each model is computed on the test dataset. The accuracy scores for each model are as follows:
- SVM Accuracy: 0.80
- Decision Tree Accuracy: 0.71
- Naive Bayes Accuracy: 0.81

### F1 Score
The F1 scores for each model are calculated for both classes ('REAL' and 'FAKE'). The F1 scores for each model are as follows:
- SVM F1 Score: [0.80, 0.81]
- Decision Tree F1 Score: [0.72, 0.71]
- Logistic Regression F1 Score: [0.80, 0.82]

### Classification Report
Detailed classification reports for each model are provided, including precision, recall, and F1-score for each class ('REAL' and 'FAKE'). 

### Confusion Matrix
The confusion matrices for each model are computed to visualize the true positive (TP), true negative (TN), false positive (FP), and false negative (FN) values.

## Conclusion
Based on the evaluation metrics, the Logistic Regression model appears to be the best-performing model for classifying fake news, achieving an accuracy of 81% and higher F1 scores for both classes.

Feel free to explore the code and use it for your own classification tasks. If you have any questions or suggestions, please feel free to contact me.

Happy coding!

*Note: The actual code for data preprocessing and model training is available in the Jupyter notebook 'fake_news_classification.ipynb'.Code can be provided on request*
