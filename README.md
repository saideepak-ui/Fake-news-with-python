# Fake-news-with-python
📰 Fake News Detection with Python
This project is a machine learning model built to detect fake news articles using Python. It classifies news into real or fake based on the content, using TF-IDF vectorization and a Passive Aggressive Classifier.

📌 Project Description
The rise of misinformation and fake news on the internet has made it important to build automated tools that can help identify them. This project aims to solve that problem using natural language processing (NLP) and machine learning.

We used the following techniques:

TF-IDF Vectorization to convert raw news text into numerical features.

PassiveAggressiveClassifier for training a binary classifier that learns quickly and handles large datasets well.

🛠️ Tools and Technologies Used
Python

Pandas and NumPy for data manipulation

Scikit-Learn for ML model building and evaluation

TF-IDF Vectorizer for feature extraction

PassiveAggressiveClassifier for classification

📁 Dataset
The dataset used in this project contains labeled real and fake news articles. It includes:

title

text

label (FAKE or REAL)

The dataset was loaded using pandas and preprocessed for training and testing.

🧠 Model Training and Evaluation
The data was split into training and test sets (80/20 split).

A TF-IDF vectorizer was used to transform the text data.

The PassiveAggressiveClassifier was trained on the TF-IDF features.

Model accuracy on the test set: ~92-94%.

🔍 Results
Confusion Matrix and Accuracy Score were used to evaluate the model.

The model effectively distinguishes between real and fake news articles.

📊 Sample Output
bash
Copy
Edit
Accuracy: 93.5%
Confusion Matrix:
[[586  43]
 [ 31 593]]
🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/saideepak-ui/Fake-news-with-python.git
cd Fake-news-with-python
Install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the script:

bash
Copy
Edit
python fake_news_detection.py
📚 References
Scikit-learn documentation

TF-IDF Wikipedia

Passive Aggressive Algorithms
