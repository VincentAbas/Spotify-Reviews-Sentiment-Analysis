![eval before Optuna SVM](https://github.com/user-attachments/assets/717cd4dc-ae9c-4cd8-9f9c-1aace4c64521)# Spotify-Reviews-Sentiment-Analysis

Use NLP to Classify Reviews if its a POSITIVE or a NEGATIVE.

## Data Source
- Kaggle
- Dataset: https://github.com/VincentAbas/Spotify-Reviews-Sentiment-Analysis/blob/3f127efbe27b261fa71ecba637549e491764e2a4/SpotifyRev.csv

## Data Info
- "Review" - a column that contains the Review in English
- "label" - a column that labels whether the Review is a positive or a negative review.

## Tools Used
- Python, Pandas, NumPy, MatPlotlib, Seaborn, nltk, Scikit-learn, WordCloud, Optuna.

## Key Highlights
- Remove unnecessary items from the dataset such as URLs, encoded characters, extra spaces, and others that are not letters, numbers, and punctuation.
- Word Cloud to check what are the differences a positive and a negative reviews have.
- Train and Evaluate the Models (SVM, Logistic Regression)
- use Optuna to tune the Hyperparameters.

## Visualizations
- **Word Cloud**
![Word Cloud](https://github.com/user-attachments/assets/9137c416-1218-4ae5-babf-8d80431a89e6)

- **Positive and Negative Distribution**
![Label](https://github.com/user-attachments/assets/46a9063b-49b8-42eb-b99c-e31aa2c30255)

## Results

### Model Evaluation
**Base Hyperparameters**

**SVM**
![eval before Optuna SVM](https://github.com/user-attachments/assets/9ead5da3-fc96-4149-a97f-3972ef361561)

**Logistic Regression**
![eval before Optuna LR](https://github.com/user-attachments/assets/7d0f41cc-676e-4361-a953-51e83b98a729)

**After Optuna Hyperparameter Tuning**

**SVM**
![eval before Optuna SVM](https://github.com/user-attachments/assets/09eb5ec9-5744-4573-9123-b18a4e6fe23b)

**Logistic Regression**
![eval after Optuna LR](https://github.com/user-attachments/assets/182b7feb-7a6a-46eb-9542-34cb761720c1)

**Ensemble Method for the SVM and Logistic Regression Model**
![Ensembled SVM and LR](https://github.com/user-attachments/assets/103093ed-a3c2-44dd-8a55-2cc4bd2e5b0d)

