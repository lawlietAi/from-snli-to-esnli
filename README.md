# from-snli-to-esnli
  
These days, I'm trying to reproduct SNLI and e-SNLI models as an exercise. In this project, I will accomplish the following two tasks.

First, I hope to be able to complete all the experiments in the [original paper](https://arxiv.org/abs/1705.02364). 

Then, Based on the InferSent model, I will implement esnli model and complete corresponding experiments.

if you want to use my project in you repositories. All requirments as follow:

Python 3.7 with anaconda

Pytorch 1.2.0 GPU

nltk with punck model

snli dataset and glove 840b 300d

### current progress:

all infersent models are complete, you can train these models using train.py(The first time you use this project, you need to run data_process.py to generate a small glove file and dataset)
