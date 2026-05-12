# Sentiment Analysis Model

A machine learning project that classifies text as positive or negative using TF-IDF vectorization and a Random Forest classifier.

## Overview
This project demonstrates a complete Natural Language Processing (NLP) workflow:
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Model training using Random Forest
- Sentiment prediction
- Model evaluation

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TF-IDF Vectorizer
- Random Forest Classifier

## Dataset
The model is trained on a labeled text dataset containing positive and negative sentiments.

## Workflow
1. Load the dataset
2. Clean and preprocess text
3. Convert text into numerical features using TF-IDF
4. Split data into training and testing sets
5. Train a Random Forest classifier
6. Evaluate model accuracy
7. Predict sentiment for new text

## Results
The model successfully classifies text sentiment and demonstrates the use of machine learning techniques for NLP tasks.

## Project Structure
- `sentiment-analysis.ipynb` – Jupyter notebook containing the complete code
- `README.md` – Project documentation

## Example Prediction
Input:
`"This movie was amazing and inspiring."`

Output:
`Positive`

## Future Improvements
- Try advanced models such as XGBoost or Neural Networks
- Add support for multi-class sentiment classification
- Deploy as a web application using Flask or Streamlit
