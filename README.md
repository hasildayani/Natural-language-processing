# Natural-language-processing
This project focuses on classifying text messages as Spam or Ham and Machine Learning techniques. The dataset is preprocessed through text cleaning, tokenization, stop-word removal, and stemming/lemmatization. Feature extraction is performed using methods such as TF-IDF or Bag of Words.

# Features

Text cleaning and preprocessing, Exploratory Data Analysis (EDA), Message length analysis, TF-IDF vectorization, Spam/Ham classification using Multinomial Naive Bayes, Model evaluation with:Accuracy Score, Classification Report, Confusion Matrix, Custom message prediction function.

# Technologies Used
* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn

# Dataset
The project uses a dataset named:
spam_ham_dataset.csv
Expected columns:
* text – Message content
* label – Message category (spam or ham)

# Model Training
The dataset is split into training and testing sets and trained using:
MultinomialNB()

# Model Evaluation
Performance is evaluated using:
* Accuracy Score
* Classification Report
* Confusion Matrix


# Installation
Clone the repository:
git clone <repository-url>
cd spam-ham-detection

Install dependencies:
pip install -r requirements.txt


Download NLTK resources:
import nltk
nltk.download('stopwords')
nltk.download('wordnet')


# How To Run Project
Open the Jupyter Notebook:
jupyter notebook spam_ham.ipynb
Run all cells to train the model and test predictions.


# Sample Prediction
MessagePredictionCongratulations! You won a free prize.SpamHey, are we meeting tomorrow at 5pm?HamURGENT! Your account will be suspended. Verify now.Spam










