# Song Lyrics Dataset


Data: https://www.kaggle.com/mousehead/songlyrics


###  Eminem-Lyrics-generation-using-LSTM-and-Analysis-with-Word2vec

RNNs (Neural networks with feedback) are very useful in NLP and language modelling

Recurrent neural networks can also be used as generative models.

This means that in addition to being used for predictive models (making predictions) they can learn the sequences of a problem and then generate entirely new plausible sequences for the problem domain.

Generative models like this are useful not only to study how well a model has learned a problem, but to learn more about the problem domain itself.

Reference: https://machinelearningmastery.com/text-generation-lstm-recurrent-neural-networks-python-keras/


### Ed Sheeran lyrics reference (N Gram)

https://www.kaggle.com/shivamb/beginners-guide-to-text-generation-using-lstms

n-gram models are widely used in statistical natural language processing. In speech recognition, phonemes and sequences of phonemes are modeled using a n-gram distribution. For parsing, words are modeled such that each n-gram is composed of n words.

n-gram models are often criticized because they lack any explicit representation of long range dependency. This is because the only explicit dependency range is (n − 1) tokens for an n-gram model, and since natural languages incorporate many cases of unbounded dependencies (such as wh-movement), this means that an n-gram model cannot in principle distinguish unbounded dependencies from noise (since long range correlations drop exponentially with distance for any Markov model). For this reason, n-gram models have not made much impact on linguistic theory, where part of the explicit goal is to model such dependencies.

### Word2Vec Analysis of the Lyrics

Word2vec is a two-layer neural net that processes text. Its input is a text corpus and its output is a set of vectors: feature vectors for words in that corpus. While Word2vec is not a deep neural network, it turns text into a numerical form that deep nets can understand.

The purpose and usefulness of Word2vec is to group the vectors of similar words together in vectorspace. That is, it detects similarities mathematically. Word2vec creates vectors that are distributed numerical representations of word features, features such as the context of individual words. It does so without external human intervention.


Given enough data, usage and contexts, Word2vec can make highly accurate guesses about a word’s meaning based on past appearances. Those guesses can be used to establish a word’s association with other words (e.g. “man” is to “boy” what “woman” is to “girl”), or cluster documents and classify them by topic. Those clusters can form the basis of search, sentiment analysis and recommendations in such diverse fields as scientific research, legal discovery, e-commerce and customer relationship management.


