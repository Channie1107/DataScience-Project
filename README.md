# DS-Project (Spam email detection)
This project focuses on detecting and classifying spam emails using Logistic Regression and Natural Language Processing (NLP) techniques.

📌 Overview
- Dataset: Email dataset from Kaggle (5,572 records, 2 columns: Category & Message).
- Preprocessing: Data cleaning, removing duplicates, stopword removal, stemming, and TF-IDF feature extraction.
- Modeling: Logistic Regression with K-Fold Cross Validation (k=5) and SMOTE for class balancing.
- Tools: Python, Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn, WordCloud, Imblearn.

🔑 Key Results
- Achieved 97.34% accuracy across 5-fold validation.
- High performance in precision, recall, and F1-score (>97%).
- Word analysis showed spam emails often contain terms like "free", "call", "text".

📖 Future Work
- Extend to other ML models (e.g., SVM, Random Forest, Deep Learning).
- Integrate with real-time email filtering systems.
