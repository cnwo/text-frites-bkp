# text-frites

Playing with NLP techniques for the win.

# Installation instructions

### 1. Clone the repository

### 2. Install conda environment

To run this project, you need the packages listed in the environment YAML [file](https://github.com/itismouad/text-frites/blob/master/environment.yml). If you have Anaconda installed, you can create an environment for this project by using the following command :

```
conda env create -f environment.yml
```

### 3. Download Word Embeddings

Download pre-trained word embeddings at the following links :

* [Google’s pre-trained Word2Vec model](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing).
	+ See this [link](http://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/) for more details.
	+ Store the file in `./data/word2vec/`.

* [GloVe: Global Vectors for Word Representation](http://nlp.stanford.edu/data/glove.6B.zip).
	+ See this [link](https://nlp.stanford.edu/projects/glove/) for more details.
	+ Store the files in `./data/glove/` (we will only use `glove.6B.200d.txt` and `glove.6B.300d.txt`.


# Cools things to read

* Understanding LSTMs, Colah : [link](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* The Unreasonable Effectiveness of Recurrent Neural Networks, A. Karpathy : [link](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
* Advances in Pre-Training Distributed Word Representations, Facebook AI Research : [link](https://arxiv.org/abs/1712.09405)
* Learned in translation: contextualized word vectors, Einstein AI (Salesforce) : [link](https://einstein.ai/research/learned-in-translation-contextualized-word-vectors)