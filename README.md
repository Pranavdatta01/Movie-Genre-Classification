Movie Genre Classification

Overview

The Movie Genre Classification project aims to predict the genre of a movie based on its textual metadata, such as plot summary, title, and other relevant features. This project utilizes Natural Language Processing (NLP) and Machine Learning techniques to classify movies into various genres.

Features

Data Processing: Cleaning and preprocessing of movie descriptions.

Feature Extraction: TF-IDF vectorization, word embeddings.

Machine Learning Models: Logistic Regression, Random Forest, Naïve Bayes, and Deep Learning models.

Evaluation Metrics: Accuracy, Precision, Recall, F1-score.

Dataset

The dataset consists of movie descriptions along with their corresponding genres. It is sourced from publicly available datasets such as IMDB, TMDB, or other movie databases.

Installation

To run this project, install the required dependencies:

pip install -r requirements.txt

Usage

Prepare Data: Ensure the dataset is in the correct format.

Train Model: Execute the script to train the classification model.

Predict Genre: Provide a movie description to predict its genre.

python train.py
python predict.py "A thrilling adventure of a detective solving crimes."

Results

The model achieves a high accuracy in genre classification, with performance varying based on the model and dataset used.

Future Improvements

Incorporating Deep Learning techniques such as LSTMs or Transformers.

Expanding the dataset for improved generalization.

Implementing multi-label classification for movies with multiple genres.

Contributing

Feel free to fork this repository and contribute to improving the model.
