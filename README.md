# Dynamic Coattention Network for Question Answering 

## Status:
Implementation of https://arxiv.org/abs/1611.01604. <br/>
Will try to update this repository as an end to end model for dynamic coattention network in near future to provide command line training and testing. <br/>

## Requirements:
Python 2.7.x <br/>
Tensorflow (1.3.0) <br/>
Numpy 1.13.1 <br/>

## Data
SQuaD dataset : https://rajpurkar.github.io/SQuAD-explorer/ <br/>
data/ : folder contains the word embeddings, and whole dataset [train and validation dataset] <br/>

## P.S.:
The snapshot is for the running of dcn_qa.py file where training is done only on dataset of size 200 owing to excessive running time on cpy but the dcn_qa.ipynb file incorporates the whole dataset.
