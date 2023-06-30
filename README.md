# Bidirectional-LSTM-Sentiment-Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xPGlzrhixdJjNDbuj2FYJLvE1wG7nql7?pli=1)

This repository provides an example of an end-to-end approach to sentiment classification using [Bidirectional](https://en.wikipedia.org/wiki/Bidirectional_recurrent_neural_networks) [Long Short-Term Memory](https://en.wikipedia.org/wiki/Long_short-term_memory) networks with pre-trained [Glove embeddings](https://nlp.stanford.edu/projects/glove/). The workflow involves several preprocessing steps, including expansion of contractions and extraction of sentiment from multiple files, before implementing the Bi-LSTM model for classification. Additionally, experiments with early stopping, test sequences and cross-validation are carried out. The dataset, available in this repository, originates from the following paper:

> Ding, X., Liu, B. and Yu, P. S. (2008) ‘A Holistic Lexicon-Based Approach to Opinion Mining’. In *Proceedings of the 2008 International Conference on Web Search and Data Mining (WSDM '08)*. [DOI: 10.1145/1341531.1341561](https://dl.acm.org/doi/10.1145/1341531.1341561).

This notebook was created as a part of COMP34711 at the University of Manchester.

To run the notebook with access to a free GPU, click on the 'Open In Colab' badge above.
