RNA-StruSiNet
======

A Siamese Deep Neural Network to assess the similarity between RNA secondary structures

___

![siamese2](https://github.com/nicoaira/RNA-StruSiNet/assets/59507281/c1c30984-24f3-4ff0-8f80-24f8c0853020)

Our model operates by receiving an input RNA secondary structure in dot-bracket format and generates an embedding vector that encapsulates the structural features of the molecule. Subsequently, the output vectors from two or more RNA secondary structures can be compared by calculating the squared distance. This distance measure signifies the extent of dissimilarity between the RNA structures.

This approach is alignment-free, offering a solution that mitigates several challenges associated with alignment-based methods, known for their typical computational expense.

___

## First example

Here are the results of our preliminary test with the structures of RNAses P from bpRNA-1m(90) dataset

![fig01B2](https://github.com/nicoaira/RNA-StruSiNet/assets/59507281/2801d1ef-98c5-41d8-93e8-eca10f586703)


In this test, we made pairwise comparison between RNAses P (either from the same or different RFam classes) and between random sequences (with the same length and GC% content as the RNAses P dataset.
