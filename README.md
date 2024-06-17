# NLP-TF-IDF-Based-Text-Analysis-for-Document-Categorization

Natural Language Processing Project
This project implements a complete workflow for text processing and analysis using Term Frequency-Inverse Document Frequency (TF-IDF) to categorize documents into predefined categories. The process includes:

- Preprocessing text data to normalize and tokenize the corpus.
- Calculating TF-IDF scores to quantify word importance.
- Averaging TF-IDF scores across documents within the same category to identify key features.
- Evaluating the feature vectors in a supervised learning context to classify documents.

Key Features:
Data Preprocessing: Converts raw text into a clean, tokenized format ready for analysis.
TF-IDF Calculation: Implements custom functions to compute Term Frequency and Inverse Document Frequency, offering insights into the significance of terms within and across documents.
Average TF-IDF Computation: Calculates and stores average TF-IDF scores for terms within each document category, facilitating deeper analysis into category-specific language use.
Machine Learning Integration: Utilizes TF-IDF vectors for training a classification model, demonstrating the application of text analysis in predictive modeling.

Project Structure:
data_preprocessing.ipynb: Notebook containing the preprocessing steps.
tfidf_analysis.ipynb: Notebook for calculating and analyzing TF-IDF scores.
model_training.ipynb: Notebook demonstrating how to train and test a classifier using the TF-IDF features.
requirements.txt:
spacy, pandas, sklearn, string, nltk

How to Use:

Clone the repository.
Install dependencies: pip install -r requirements.txt
Run the Jupyter Notebooks in sequence to understand the workflow and results.
