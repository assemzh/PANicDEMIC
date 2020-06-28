# PANicDEMIC
Detecting Emotions on COVID-19 Over Time Using NLP

## Building classifier:
### Emotional words extractor:
Dataset:
twitter_crosstab.csv, downloaded from saifmohammad.com

Labeled tweets in 4 emotion categories: anger, fear, joy, sadness

Extractor: return scored features based on Bayesian posterior probability

Model: bag-of-word, Tf-idf vectorization

#Presentation video:
[![Watch the video](https://img.youtube.com/vi/1AEVI7UAa6w/hqdefault.jpg)](https://www.youtube.com/watch?v=1AEVI7UAa6w)

#Results:
Anger is dominant in emotions on COVID-19. The main sources of anger may lie in the government response and policies.  However,further investigation is needed to support our hypothesis.  The next step may include classifying results by location and analyzing not only news titles but also the content of the news. In this case, building a news-specific model may be required. Overall,  by  using  a  simple  and  interpretable model in Python and NLTK, our project may contribute in providing an insight to take into account the mental state of the country,  while imposing some policies and setting recovery strategies during hard times of the pandemic.
