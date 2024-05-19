# Gist
+ Analyzed an extensive dataset, nearly 1gB in size, encompassing labeled data (fake or real) about US elections and designed a basic website that classified the text given by the user (input) as fake news or real news (output).
  + Tech Stack: HTML, CSS, Flask, Python.
+ Split the dataset into 70% training data and 30% testing data. Implemented various models, namely Naive Bayes, Decision Trees, Random Forest, SVM, Logistic Regression, and Passive-Aggressive Classifier on the training data by applying count-vectorization and tf-idf techniques and calculated their accuracy using confusion matrices. SVM and Passive-Aggressive Classifier provided the highest accuracy (>90%) among them.

# Prerequisites
+ You can run the Notebook directly on Google Colab.
+ The dataset is already provided in the code (check for the file 'Fake_news.csv').