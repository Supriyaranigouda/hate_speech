**Hate Speech Detection using Machine Learning**

The model is trained using machine learning and NLP techniques with the goal of identifying and categorizing harmful content on social platforms.
 
 **About Dataset**

The project uses a labeled dataset (`train.csv`) with the following columns:

- tweet → Text content
-class → Label (0, 1, 2)
-labels (mapped)→ Human-readable label:
  - 0 → "Hate speech"
  - 1 → "Offensive speech"
  - 2 → "Neither"
  
 **Data Preprocessing**

The following steps were applied:

- Text cleaning (URLs, mentions, hashtags)
- Lowercasing
- Removing punctuation & stopwords
- Tokenization
- Lemmatization
- Mapping numeric labels to readable categories

  
**Modeling**

Multiple machine learning models were trained and tested:

Logistic Regression
Naive Bayes 
SVM (Support Vector Machine) 
Random Forest
TF-IDF Vectorizer for feature extraction

The best-performing model was selected based on accuracy, F1-score, precision, and recall.

**Results**

- Achieved strong performance in text classification
- Effective separation between *hate speech*, *offensive speech*, and *neutral content*
- Suitable for real-time content moderation use-cases
