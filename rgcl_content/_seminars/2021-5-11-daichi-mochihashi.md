---
layout: seminar
title: "How LSTM Encodes Syntax: Exploring Context Vectors and Semi-Quantization on Natural Text"
speaker: "Prof Daichi Mochihashi"
affiliation: "Institute of Statistical Mathematics, Japan"
time: 9am
series: mldl # emtti, nlp, mldl, dh 
image: null 
---

### Abstract
LSTM (Hochreiter 1997) is a well-known recursive neural network that models time series and word sequences, and applied in many fields including natural language processing. For example, Google neural machine translation (Wu+ 2016) is a model that connects 8-level LSTM both for the source language and the target language.
Lately several studies investigate the behavior of neural networks including LSTM; however, they are all limited in their method of regarding neural network as a black-box and only analyze its outputs.
On the contrary, in this study we directly investigate the internal vectors of LSTM from a statistical point of view, and visualize how its state vectors distribute.
Specifically, leveraging syntactic tree assigned to Penn Treebank WSJ corpus, we show that the depth of syntactic tree can be highly predictable using a linear regression on some elements of its state vectors. When using only raw words as input, precision becomes lower but the statistical behavior is still the same. We also show that the state vectors associated with polysemous words such as "that" actually distribute differently, which are identified with an
ingenious use of PCA.
 
This is a joint work with Chihiro Shibata (Hosei University) and Kei Uchiumi (Denso IT Laboratory), and appeared at COLING 2020.

### Speaker's bio

Daichi Mochihashi is an associate professor at the Institute of Statistical Mathematics, Japan. He obtained BS from The University of Tokyo and PhD from Nara Institute of Science and Technology in 1998 and 2005, respectively. He currently serves as an action editor at TACL and served as an area chair in some ACL conferences.
