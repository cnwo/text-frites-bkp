# text-frites

Playing with NLP techniques for the win.

# Installation instructions

### 1. Clone the repository

### 2. Install Environment

To run this project, you need the packages listed in the environment YAML [file](https://github.com/itismouad/text-frites/blob/master/environment.yml). If you have Anaconda installed, you can create an environment for this project by using the following command :

```
conda env create -f environment.yml
```

### 3. Download Word Embeddings

Download pre-trained word embeddings at the following links :

* [Google’s pre-trained Word2Vec model](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing). See this [link](http://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/) for more details. Store the file in `./data/word2vec/`.
* [GloVe: Global Vectors for Word Representation](http://nlp.stanford.edu/data/glove.6B.zip). See this [link](https://nlp.stanford.edu/projects/glove/) for more details. Store the files in `./data/glove/` (we will only use `glove.6B.200d.txt` and `glove.6B.300d.txt`.