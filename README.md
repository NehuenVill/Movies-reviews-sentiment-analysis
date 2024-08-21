# Sentiment Analysis on IMDB Movie Reviews

## Project Overview

This project implements sentiment analysis on IMDB movie reviews, using machine learning techniques to classify reviews as positive or negative. The model is trained on a dataset of labeled IMDB reviews.

1. Clone the repository:

```
git clone https://github.com/NehuenVill/Neural-Networks-From-Scratch.git
cd Neural-Networks-From-Scratch
```

## Dataset

The dataset used in this project is the IMDB Movie Reviews Dataset, which contains 40,000 movie reviews labeled as 1 (positive) or 0 (negative).

- **Train Dataset**: 32,000 reviews
- **Test Dataset**: 8,000 reviews

## Model Training

**The model was trained using the following steps:**

1. Text Preprocessing: Tokenization, removing stopwords, turning into lowercase.

2. Feature Extraction: Converting text data to numerical features using TF-IDF technique.

3. Model Selection: Various machine learning models were explored such as Random Forest, SVM, Naive Bayes, and Logistic Regression, using cross validation and comparing each models accuracy, precision, recall, and F1-score.

4. Hyperparameter tuning of the selected model: Using grid search.

5. Evaluation: The model was evaluated using accuracy, precision, recall, and F1-score.

### Results

- **Accuracy:** 90%
- **Precision:** 89.5%
- **Recall:** 90%
- **F1-Score:** 89.5%

## Usage


To predict the sentiment of a new review, as shown in the last cell of the notebook.


## Future Work

Experiment with different models like LSTM, BERT, or Transformer-based models.

Improve the preprocessing with more NLP techniques like bag of words.

Using the preprocessed data to train a Neural Network model made from scratch using only Python and Numpy, like this one on another project of mine: [Neural-Networks-From-Scratch](https://github.com/NehuenVill/Neural-Networks-From-Scratch)

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for suggestions.

## License

This project is licensed under the MIT License - see the LICENSE file for details.