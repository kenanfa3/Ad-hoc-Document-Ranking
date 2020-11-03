# Ad-hoc-Document-Ranking
Ad-hoc Document Ranking done on TREC 2004 Robust dataset <br/>
This repositery contains project work for Deep Learning and Data Mining courses.<br/>
Anserini toolkit was used to retrieve candidates for each query using a pre-built index for Robust 2004 dataset. <br/>
For the purpose of re-ranking, I experimented with Convolutional Kernel-based Neural Ranking Model (CONV-KNRM) similar to the work done in "Convolutional Neural Networks for Soft Matching N-Grams in Ad-hoc Search" .<br/>
I also experimented with BERT Next Sentence Prediction classification for the purpose of re-ranking where query-document pairs are used as sentence pairs with BERT. <br/>
