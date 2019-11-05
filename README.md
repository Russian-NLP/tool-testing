# tool-testing
Jupyter notebooks for testing out existing Russian NLP tools on various Russian corpora.

## Tools
### Lemmatization & stemming (Quinn)
* [PyMyStem](https://pypi.org/project/pymystem3/)
* NTLK snowball stemmer for Russian

### Named-entity recognition (Andy)
* [Natasha](https://natasha.readthedocs.io/) rule-based named-entity recognition
* [BERT](http://docs.deeppavlov.ai/en/master/features/models/ner.html) model
* Spacy [multilingual model](https://spacy.io/models/xx#xx_ent_wiki_sm) for NER

### Part-of-speech & syntax (Aaron)
* [Stanford NLP model](https://stanfordnlp.github.io/stanfordnlp/) in Spacy
* [Russian model](https://github.com/buriy/spacy-ru) with older version of Spacy

### Sentiment analysis (Sarah)
* [Dostoevsky](https://pypi.org/project/dostoevsky/)
* [Polyglot](https://pypi.org/project/polyglot/) for sentiment analysis

### Coreference
* [Corpus](http://rucoref.maimbava.net/) and [code](https://github.com/max-ionov/russian-anaphora)

## To be tested on the following corpora
* [Russian Drama Corpus](https://dracor.org/rus)
* Revolutionary poetry (1914-1924)
* (Журналный зал](https://magazines.gorky.media/)
* Russian Bible
* Правда articles
* Contemporary Russian newspapers
* 19th century novels (via lib.ru)
* Russian tweets (including [troll tweets](https://github.com/fivethirtyeight/russian-troll-tweets))
* Harry Potter fanfic (ficbook.net)
* Feminist zines
* [Прожито diaries](http://prozhito.org/)
