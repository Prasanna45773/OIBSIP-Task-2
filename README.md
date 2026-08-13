# OIBSIP-Task-2

💬 **Sentiment Analysis**

A Machine Learning project that classifies text into **Positive, Negative, and Neutral** sentiments using Natural Language Processing (NLP), TF-IDF, and classification algorithms.

🎯 **Objectives**

* Load and inspect the sentiment dataset
* Analyze positive, negative, and neutral sentiment distribution
* Preprocess text using lowercasing, punctuation removal, stopword removal, tokenization, and lemmatization
* Convert text into numerical features using TF-IDF
* Split the dataset into 80% training and 20% testing data
* Train and compare Naive Bayes and Logistic Regression models
* Evaluate models using accuracy, precision, recall, and F1-score
* Generate confusion matrices and WordClouds
* Perform error analysis on misclassified reviews

🛠️ **Tech Stack**

Python
Pandas
NumPy
Scikit-learn
NLTK
WordCloud
Matplotlib
Seaborn
Jupyter Notebook

📈 **Key Analysis**

* Sentiment Distribution
* TF-IDF Feature Extraction
* Naive Bayes Classification
* Logistic Regression Classification
* Confusion Matrix
* Model Performance Comparison
* Positive, Negative & Neutral WordClouds
* Misclassified Text Analysis

💡 **Key Insights**

* Identified the distribution of positive, negative, and neutral text samples.
* TF-IDF effectively converted text data into numerical features for machine learning.
* Compared Naive Bayes and Logistic Regression performance.
* Used confusion matrices to identify correctly and incorrectly classified sentiments.
* Analyzed misclassified examples to understand model limitations.

▶️ **How to Run the Project**

1. Clone the repository
2. Navigate to the project folder

```bash
cd Sentiment-Analysis
```

3. Install required libraries

```bash
pip install pandas numpy scikit-learn nltk wordcloud matplotlib seaborn jupyter
```

4. Start Jupyter Notebook

```bash
jupyter notebook
```

5. Open:

```text
Sentiment_Analysis.ipynb
```

Run the cells sequentially to reproduce the analysis and model results.
