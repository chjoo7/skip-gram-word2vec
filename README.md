# skip-gram-word2vec
Implement the word2vec algorithm using the skip-gram architecture

## How to install

git clone https://github.com/chjoo7/skip-gram-word2vec.git

## Why we use skip-gram model

In this implementation, we'll be using the skip-gram architecture because it performs better than CBOW. Here, we pass in a word 
and try to predict the words surrounding it in the text. 
In this way, we can train the network to learn representations for words that show up in similar contexts.

## Get the data

Load the text8 dataset, a file of cleaned up Wikipedia articles from Matt Mahoney. The next cell will download the data set 
to the data folder. Then you can extract it and delete the archive file to save storage space.

## Visualizing Word Vectors

we'll use T-SNE to visualize how our high-dimensional word vectors cluster together. T-SNE is used to project these vectors into two dimensions while preserving local stucture. 
Check out this post from Christopher Olah to learn more about T-SNE and other ways to visualize high-dimensional data
