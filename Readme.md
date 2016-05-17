About
=====
This package contains the CRF Baseline and LSTM-RNN implementation for the paper named "Fine-grained Opinion Mining with Recurrent Neural Networks and Word Embeddings" published in EMNLP2015, Lisboa, Portugal. If you use the code in this package, please cite the paper:

@inproceedings{liu2015fine,
  title={Fine-grained opinion mining with recurrent neural networks and word embeddings},
  author={Liu, Pengfei and Joty, Shafiq and Meng, Helen},
  booktitle={Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing},
  pages={1433--1443},
  publisher={Association for Computational Linguistics},
  venue={Lisbon, Portugal}
  year={2015}
}


Prerequisite
============
To run the scripts, the datasets and some open source tools need to be downloaded:
(1) Datasets from SemEval-2014 Task 4: http://alt.qcri.org/semeval2014/task4/index.php?id=data-and-tools and put in the evaluation folder.
(2) word2vec and Google News Embeddings: https://code.google.com/p/word2vec/
(3) Amazon Reviews: https://snap.stanford.edu/data/web-Amazon.html
(4) SENNA Embeddings: http://ronan.collobert.com/senna/
Note that the Embeddings should be put in the embeddings folder.

Example Commands
================
Some example commands are as follows:
(1) bash rnn-batch.sh Senna
(2) bash cv-batch.sh laptop Senna 50 50

Credits
=======
(1) We used the tool CRFsuite for the CRF baseline, please refer to http://www.chokkan.org/software/crfsuite/.
(2) For Elman-RNN and Jordan-RNN implementation, please refer to https://github.com/mesnilgr/is13.

