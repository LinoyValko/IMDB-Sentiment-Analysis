# IMDB-Sentiment-Analysis
This project analyzes movie reviews from the IMDB dataset using sentiment classification techniques. The goal is to classify reviews as positive or negative based on their textual content.


## Project Highlights

- **Dataset**: IMDB reviews dataset (50,000 labeled reviews)
- **Preprocessing**: 
  - HTML tags removal
  - Lowercasing
  - Stop words removal
- **Feature Engineering**: TF-IDF Vectorization
- **Model**: Logistic Regression (best performance)
- **Evaluation Metrics**: Accuracy (89.3%), Recall (90.7%), Precision (88.3%)
- **Visualization**: Word frequency, SHAP values, n-grams

## Tools Used

- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- SHAP for explainability

## Results

Logistic Regression outperformed other models such as SVM, Random Forest, and Naive Bayes in terms of accuracy.
