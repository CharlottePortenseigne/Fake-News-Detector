# Fake-News-Detector
Fake News detector where the news is from the Fake News Challenge from Kaggle and KGP Talkie manually checked the news.

# Installation
### To clean the Data and DataFrame library
- Pandas 1.3.5
`pip install pandas`
- Re 2021.11.10
`pip install regex`
- NLTK 3.6.7
`pip install nltk`

### Visualisation library
- Matplotlib 3.5.1
`pip install matplotlib`
- Word Cloud 1.8.1
`pip install wordcloud`

### To save the model library
- Pickle 5
`pip install pickle5`

### Neural Network library
- TensorFlow 2

Requires the latest pip
`pip install --upgrade pip`

Current stable release for CPU and GPU
`pip install tensorflow`
- Keras 2.7.0
`pip install keras`
- Numpy 1.22.1
`pip install numpy`
- Sckikit-learn 1.0.2
`pip install scikit-learn`

### Natural Language Processing library
- NLTK 3.6.7
`pip install nltk`
- SpaCy 3.2.1
`pip install spacy`
- SkLearn 1.0.2
`pip install scikit-learn`

### Test the Model
- SkLearn 1.0.2

# Development
### Loading Data
The corpus come from Kaggle's competition about Fake News. KGP Talkie checked the data and classified them. The csv of Fake News and real News are freely available in his GitHub.
Then, we load the csv files of the Fake News and the real News and we put them in a DataFrame with Pandas.

### Visualization of the Data
We put the different topics of the news : News, politics, left-news, Government News, US_News and Middle-east, in a bar plot with Matplotlib. It's easier to see what kind of news you have the most or the lest.
To easily see which words are more frequent in the Fake News and the real News we do a Bad of Word of each one with WordCloud.

### Cleaning and Preprocessing the Data
We clean the Data by dropping the news with empty index.
- Clean the Data (nltk, re)
- Stemming (nltk)
- Tolkenization (Keras)
- Save corpus (Pickle)
- Embedding Representation (Keras)

### Predictive Modeling
- Predictive Model : LSTM Model (Keras)

### Testing the Model
- Confusion Matrix (sklearn)
- Accuracy Score (sklearn)
- Classification Report (sklearn)
