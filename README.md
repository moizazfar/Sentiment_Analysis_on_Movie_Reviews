# Sentiment Analysis on Movie Reviews

This project implements sentiment analysis on movie reviews using Logistic Regression and Naive Bayes. The data is sourced from the Rotten Tomatoes dataset.
## Table of Contents
- [Installation](#project-overview)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Results](#results)
- [Usage](#usage)
- [License](#license)
## Installation

Install the necessary packages using pip:

```bash
pip install pandas matplotlib seaborn nltk scikit-learn
```


## Dataset

- **train.tsv:** Contains phrases with sentiment labels.

- **test.tsv:** Contains phrases for sentiment classification.

**Sentiment labels:**

- 0: Negative
- 1: Somewhat Negative
- 2: Neutral
- 3: Somewhat Positive
- 4: Positive
## Preprocessing

Text data is preprocessed through:

1. Lowercasing
2. Tokenization
3. Removing punctuation
4. Stop word filtering
5. Lemmatization
## Model Training

Two models are trained:

- **Naive Bayes**
- **Logistic Regression**

Both models predict sentiments on the test dataset.
## Results
Predictions for each model are stored in the ```test_df``` DataFrame, showing:

- ```PhraseId```
- ```Phrase```
- ```Log_Reg_Prediction```
- ```NB_Prediction```
## Usage
To run the project, ensure you have the dataset files (```train.tsv``` and ```test.tsv```) in the same directory. Execute the script

```python
python sentiment_analysis_on_movie_reviews.py
```
## Contributing

Contributions are always welcome!
Feel free to fork this repository and submit pull requests. Contributions to improve the code, analysis, or documentation are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.

