RNA-StruSiNet
======

A Siamese Deep Neural Network to assess the similarity between RNA secondary structures

___

![siamese2](https://github.com/nicoaira/RNA-StruSiNet/assets/59507281/c1c30984-24f3-4ff0-8f80-24f8c0853020)

Our model takes an input RNA secondary structure in the dotbracket format and outputs and embedding vector representing structural features of the molecule.
Then, the output vector of two or more RNA secondary structures can be compared by computing the squared distance, which outputs a distance measure that represent the degree of difference between the RNAs. 

This is an alignment-free aproach, which overcomes many of the difficulties of the alignment-based methods, which are usually computationally expensive.

___

## First example

Here are the results of our preliminary test with the structures of RNAses P from bpRNA-1m(90) dataset

![fig01B2](https://github.com/nicoaira/RNA-StruSiNet/assets/59507281/2801d1ef-98c5-41d8-93e8-eca10f586703)


In this test, we made pairwise comparison between RNAses P (either from the RFam class or different classes) and between random sequences (with the same lenght and GC% content as the RNAses P dataset.
