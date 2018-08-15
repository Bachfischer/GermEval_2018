# GermEval_2018

## Overview

This is the source code for the GermEval submission by the KAUSTmine team.

This work was conducted as part of a research project at [King Abdullah University for Science and Technology](https://www.kaust.edu.sa/en) and supervised by Uchenna Akujuobi and Professor Xiangliang Zhang.

## Installation

This project uses word embeddings from tweets that were published by SpinningBytes. They can be downloaded under the following [link](https://www.spinningbytes.com/resources/wordembeddings/) (look for "Word Embeddings trained with Word2Vec on 200 million German Tweets using 200 dimensions"). Then extract the content of the folder into the */input/embed_tweets_de_200M_200D/* directory.

For the GermEval submission, Tensorflow 1.8.0 and Keras 2.2.2 was installed.

## Documentation

The *src* folder contains a variety of models that were used for experimentation. For the final submission, SVM baseline.ipynb, CNN.ipynb and LSTM.ipynb were used.


## Contact

For more information, please feel free to contact me via e-mail (bachfischer.matthias@googlemail.com). 
