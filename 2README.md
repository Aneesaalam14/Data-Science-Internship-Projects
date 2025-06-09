# Sentiment Analysis on IMDB Movie Reviews

## Project Description
This project demonstrates building a simple sentiment analysis model that classifies movie reviews from the IMDB dataset as **positive** or **negative**. It covers the full pipeline from text preprocessing to model evaluation using Python and machine learning.

## Key Steps
1. **Text Preprocessing**  
   - Tokenization  
   - Stopword removal  
   - Lemmatization

2. **Feature Engineering**  
   - Convert text to numerical vectors using TF-IDF

3. **Model Training**  
   - Train a Logistic Regression classifier on the processed data

4. **Model Evaluation**  
   - Evaluate model accuracy, precision, recall, and F1-score on test data

5. **Sentiment Prediction Function**  
   - Predict sentiment on custom input text

## Technologies and Libraries
- Python 3.x  
- Jupyter Notebook  
- NLTK (for text preprocessing)  
- Scikit-learn (for vectorization, model training, and evaluation)

## How to Use
1. Install required libraries:
   ```bash
   pip install nltk scikit-learn
   
   
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('punkt')

Run the Jupyter Notebook step-by-step to:

Load and preprocess the data

Train the Logistic Regression model

Evaluate the model

Use the predict_sentiment() function for new text

RESULTS!!!

Achieved ~79.5% accuracy on the test dataset

Balanced precision and recall for both positive and negative reviews

Model can predict sentiment for any custom input text

EXAMPLE USAGE
print(predict_sentiment("The movie was boring and slow."))  # Output: Negative 😞
print(predict_sentiment("I really enjoyed the storyline!"))  # Output: Positive 😊
