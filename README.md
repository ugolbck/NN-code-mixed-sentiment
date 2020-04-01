## Neural Networks for Sentiment Analysis of Code-Mixed Spanglish Tweets

* Course: **Research & Development (Autumn 2019), Uppsala university**

* Data set: **SentiMix Spanglish 2019**

* Paper: [right here](https://github.com/ugolbck/NN-code-mixed-sentiment/blob/master/CodeMixed_NN_Paper.pdf)

* Notebook: [right here](https://github.com/ugolbck/NN-code-mixed-sentiment/blob/master/convolutional_sentiment.ipynb) _(not good at all, to redo entirely)_

---------

Best model: `CNN w/ character embeddings and averages FastText embeddings` 

Best performance: `51% F1`

*********

#### TODO:

* Modify CONLL reader to keep **#hastags**
* Adapt pre-processing to GloVe Embeddings
* Use SOTA pre-trained model using multilingual word/document representations
* Optimize runtime and memory allocations
* Make better graphs and statistics (class distrib, embedding coverage, results...)
* _Modify report paper in consequence_
