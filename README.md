# books
Using the Kaggle Dataset 
Goodreads-books: comprehensive list of books listed in goodreads
## Dataset link: https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks

# Exploring Goodreads Dataset and Topic Modeling

In this project, I explore the Goodreads dataset obtained from Kaggle to gain insights into the world of books. Goodreads is a popular platform for readers to discover, rate, and review books. This dataset provides valuable information about a wide range of books, including their titles, authors, ratings, and more.

The primary goal of this project is to apply machine learning techniques for topic modeling. Topic modeling allows us to uncover underlying themes or topics within a large collection of text data. By doing so, we can better understand the content and categorization of books in the Goodreads dataset.

# Project Structure

The project is structured as follows:
-Goodread_bookEDA.ipynb: Google colab containing initial exploration of the dataset and data preprocessing like text cleaning and feature engineering. Also applied machine learning techinique (Latent Dirichlet Allocation) for tom=pic modeling.

- `README.md`: This document providing an overview of the project.

## Exploratory Data Analysis (EDA)

In the initial exploration phase, I performed the following tasks:

- Data loading and inspection.
- Descriptive statistics to gain an understanding of the dataset's basic properties.
- Data visualization using various plots to identify trends and patterns.

## Data Preprocessing

Before applying topic modeling, it's crucial to preprocess the text data. This involves:

- Text cleaning, including removing punctuation, stopwords, and special characters.
- Tokenization of text into words or phrases.
- Vectorization of text using techniques like TF-IDF (Term Frequency-Inverse Document Frequency).

## Topic Modeling

Topic modeling is a form of unsupervised learning that aims to identify topics or themes in a collection of documents. In this project, I use techniques such as Latent Dirichlet Allocation (LDA) to discover latent topics in the book descriptions or other relevant text data.

- Application of LDA for topic modeling.
- Interpretation of results to identify and label topics.

## Dependencies

The project was developed using the following Python libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn


## Results and Insights

The project's main findings, including the identified topics and any insights gained from the topic modeling process

