# AI Project 

### Title: News summarization and twitter metainfo sentiment analysis  
<<<<<<< HEAD
In partial fulfillment of the coursework for CSE537: Artificial Intelligence  
=======
In partial fulfillment of the coursework for CSE5XX: Artificial Intelligence  
>>>>>>> 8a7a6030fb9a78b5eba17a287e1729faeef816f5
Stony Brook University, Fall '16

### Authors
* Siddharth Shah
* Nidhi Panpalia
* Rushabh M. Shah

### Setup
* Build a Machine Learning ready environment in Python 2.7 as follows:
* Using Anacondas:
* Create a virtual environment with the common ML packages - 
```
$ conda install -n venv python=2.7 numpy scipy scikit-learn nltk
```
* Activate the environment -
```
$ source activate venv
```
* Install additional packages using pip -
```
$ pip install networkx BeautifulSoup lxml
```
* A few twitter streaming APIs -
```
$ pip install tweepy twitter-text-python twython
```
* Some nltk packages - 
```
$ python
>>>> import nltk
>>>> nltk.download(['stopwords', 'punkt', 'vader_lexicon', 'brown'])
```

### Run
* Activate the environment - 
```
$ source activate venv
```
* Once the environment is up and running, the go ahead and play with `src/main.py`
* Help:
```
$ python main.py
  
  USAGE:
  main.py <SEARCH TERM>
```
* Usage:
```
$ python main.py Donald Trump

  http://time.com/4605223/donald-trump-israel-david-friedman/
  http://www.nytimes.com/2016/12/16/us/politics/ryan-zinke-mitch-mcconnell-trump-cabinet.html
  http://www.cnn.com/2016/12/16/politics/donald-trump-supporters-vicious-violent/
  http://www.wsj.com/articles/donald-trump-to-nominate-rep-mick-mulvaney-as-budget-director-1481932653
  http://www.wsj.com/articles/donald-trump-takes-conciliatory-tone-at-postelection-rallies-1481904085
  http://www.huffingtonpost.com/entry/trump-national-security-monica-crowley
  .
  .
  .
<<<<<<< HEAD
=======
```
```
>>>>>>> 8a7a6030fb9a78b5eba17a287e1729faeef816f5
  The summarization, tweet fetching and sentiment anlysis of tweets code is in the src/ directory.
  The web code for the same is in the LSA/ directory. 
  On load of the search page, the query is sent to the python using php exec command and a json object is returned
  The object contains all the summaries, stats about the data, tweets mentioning the articles 
  The positive tweets are shown in blue, the negative are shown in red.
```
