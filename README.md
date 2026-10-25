# NLP and review-analysis coursework

Python notebooks exploring review preprocessing, sentiment classification, topic modeling, and web-data collection. The portfolio's product-review example compares count-based and TF-IDF features with logistic regression and Gaussian Naive Bayes.

## Technical skills

- **Core NLP workflow:** Python, pandas, NLTK, scikit-learn, Matplotlib, Seaborn.
- **Text exploration:** tokenization, stemming/lemmatization, unigrams/bigrams, word clouds, and classification reports.
- **Other notebooks:** Gensim topic modeling, Selenium/BeautifulSoup collection, and spaCy/pyLDAvis exploration where imported.

## Start here

- [NLP - preprocessing.ipynb](NLP%20-%20preprocessing.ipynb): clean product reviews, tokenize text, explore word/bigram distributions, and export processed data.
- [NLP - modelling.ipynb](NLP%20-%20modelling.ipynb): convert ratings into positive/negative labels, compare count and TF-IDF representations, and evaluate classifiers and class imbalance.
- `212345x_SentimentClassification.ipynb` and `212345x_TopicModelling.ipynb`: additional shopping-review analysis.
- `ITBW51_212345X_*.ipynb`: scraping, preprocessing, and text-analysis coursework. The checked-in text-analysis filename is `ITBW51_212345X_TextClassificaiton.ipynb`.
- `Beer.ipynb`: additional review-classification experiments.

## Getting started

Open the notebooks in Google Colab or Jupyter. For the main product-review pair, run preprocessing before modeling. The cells reference `product_reviews.csv` and `cleaned_product_review.csv` under personal Google Drive paths; provide the appropriate input data and update those paths first.

Install libraries imported by the chosen notebook and download the NLTK resources requested in its setup cells. Some notebooks need additional datasets, browser-driver setup, spaCy language models, or optional visualization packages. The repository has no shared dependency lockfile and does not include the referenced review CSVs.

## Scope

These are separate coursework experiments, not one packaged service. Notebook outputs and conclusions use different datasets and splits and should not be combined into a single performance claim. Individual contribution boundaries are not explicitly recorded in the repository.
