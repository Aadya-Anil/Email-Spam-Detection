# Email Spam Detection using NLP and Machine Learning
This project demonstrates how Natural Language Processing (NLP) and Machine Learning can be used to detect spam messages. It uses TF-IDF vectorization and Logistic Regression to classify emails as spam or ham (not spam).

Content:
### Dataset
### Preprocessing Steps
## Model
## Skills Demonstrated


## Dataset
The dataset is sourced from a publicly available SMS Spam Collection dataset.
URL: spam.csv

116 labeled messages with two columns:
type → spam or ham
text → the actual email content

## Preprocessing Steps
Tokenization: Splits the message into individual words.
Stemming: Reduces words to their root forms using SnowballStemmer.
Lemmatization: Normalizes words using WordNet.
Stopword Removal: Removes common English stopwords.
TF-IDF Vectorization: Converts text into numerical feature vectors.

## Model
Model Used: Logistic Regression
Train/Test Split: 80/20
Vectorization: TfidfVectorizer
Accuracy: 87.5%


## Skills Demonstrated
Natural Language Processing (NLP)
Text Vectorization (TF-IDF)
Feature Engineering
Supervised Learning
Model Evaluation

👩‍💻 Author
Aadya Anil Kumar
GitHub: @Aadya-Anil
