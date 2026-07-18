Fake News Detection Using Machine Learning

Project Overview

This project is a Fake News Detection system developed using Machine Learning and Natural Language Processing (NLP). It classifies news articles as **Real** or **Fake** based on their textual content. The model is trained using the Fake and Real News Dataset and uses TF-IDF Vectorization with the Passive Aggressive Classifier for text classification.

Features

* Detects fake and real news articles
* Uses Natural Language Processing (NLP)
* Converts text into numerical features using TF-IDF
* Trains a Passive Aggressive Classifier
* Predicts whether a news article is real or fake
* Developed using Python in Google Colab

 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* NLP (TF-IDF Vectorization)

Dataset

The project uses the **Fake and Real News Dataset**, which contains two files:

* `Fake.csv`
* `True.csv`

These datasets are merged, labeled, shuffled, and used for training and testing the model.

Machine Learning Workflow

1. Import required libraries
2. Load the datasets
3. Assign labels to fake and real news
4. Merge and shuffle the data
5. Split into training and testing sets
6. Convert text using TF-IDF Vectorization
7. Train the Passive Aggressive Classifier
8. Evaluate the model using Accuracy Score, Confusion Matrix, and Classification Report
9. Test the model with custom news articles

Model Used

Passive Aggressive Classifier

Evaluation

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

The trained model achieves high accuracy in distinguishing fake news from real news articles.

Project Structure

`text
Fake_News_Detection/
│
├── Fake_News_Detection.ipynb
├── README.md
├── requirements.txt
├── fake_news_model.pkl
└── tfidf_vectorizer.pkl
`

Future Improvements

* Build a web application using Streamlit
* Use Deep Learning models such as LSTM or BERT
* Deploy the project online
* Improve preprocessing and feature engineering

Conclusion

This project demonstrates the application of Machine Learning and Natural Language Processing in detecting fake news. It provides a simple and effective solution for binary text classification and serves as a practical AI project for learning and experimentation.

Author

VINOD MOHAN

Artificial Intelligence Internship Project

CodeTech IT Solutions
