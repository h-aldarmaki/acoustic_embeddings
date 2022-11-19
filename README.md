# Acoustic Embeddings
Python code to replicate experiments described in "Supervised Acoustic Embeddings And Their Transferability Across Languages". ICNLSP 2022.

* Training & Evaluation

The notebooks include everything you need to train and evaluate the supervised and self-supervised AWE models. You need to provide the input data, which should be pre-processed by segmenting spoken words and extracting features. We used the [Librispeech](https://www.openslr.org/12) and [Multilingual Librispeech](https://www.openslr.org/94/) datasets for English, French, German, and Spanish. We used the [s3prl toolkit](https://github.com/s3prl/s3prl/blob/main/s3prl/upstream/README.md) to extract all features. For word boundaries, we used the [Montreal Forced Aligner](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner).

Refer to the paper for more details. 

