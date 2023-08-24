# Python-Powered Fake News Detection Using Data Analytics

Unveiling deception through data analytics and Python, this project combats fake news. The dataset, "news.csv," stands at 7796x4, with columns for news identification, title, text, and FAKE/REAL labels.

Steps:

Imports: Include required modules.  

Data Load: Import "content/train.csv" to a DataFrame and note its shape.
Label Extraction: Capture FAKE/REAL labels.
Data Split: Segregate data into training and testing sets.
Feature Setup: Employ TfidfVectorizer with English stop words.
Classifier Initialization: Set up PassiveAggressiveClassifier.
Model Assessment: Evaluate via confusion matrix for insights into true/false positives/negatives.
Accuracy: Attain 97.82% accuracy on project conclusion.

Modules: Python3, NumPy, pandas, sklearn
