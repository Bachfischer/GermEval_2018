# GermEval_2018

## Overview

This is the source code for the GermEval submission from KAUSTmine team.

This work was conducted as part of a research project at [King Abdullah University for Science and Technology](https://www.kaust.edu.sa/en) and supervised by Uchenna Akujuobi and Professor Xiangliang Zhang.

## Installation

For our models, word embeddings published by SpinningBytes were used. They can be downloaded under this [link](https://www.spinningbytes.com/resources/wordembeddings/) (look for "Word Embeddings trained with Word2Vec on 200 million German Tweets using 200 dimensions"). Extract the content of the folder into the directory */input/embed_tweets_de_200M_200D/*.

For the GermEval submission, Tensorflow 1.8.0 and Keras 2.2.2 was used.

## Documentation

The *src* folder contains a variety of models that were used for experimentation. For the final submission, *SVM baseline.ipynb, CNN.ipynb* and *LSTM.ipynb* were used. This repository also contains additional code for plotting ROC curves and training a variety of additional models that were not submitted to the shared task.

## Contact

For more information, please feel free to contact me via e-mail (bachfischer.matthias@googlemail.com). 
