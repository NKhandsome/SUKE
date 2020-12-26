# Description
The warehouse stores data sets of CN15k, PPI5k and NL27k.

The designers of UKGE (Embedding Uncertain Knowledge Graphs) are the original authors who provided this data set. Thanks for their contributions.so,the original data set can still be found at https://github.com/stasl0217/UKGE.
# SUKE
SUKE: Embedding Model for Prediction in Uncertain Knowledge Graph
# ABSTRACT
Graph embedding models are widely used in knowledge graph completion (KGC) task.
However, most models are based on the assumption that knowledge is completely certain, and this
is inconsistent with real-world situations. Although there are multiple studies on uncertain knowledge
embedding tasks, they often use knowledge confidence to learn embedding and cannot make full use
the structural and uncertain information of knowledge. This paper presents a new embedding model
named Structural and Uncertain Knowledge Embedding (SUKE), which comprises two components: an
evaluator and a confidence generator. For unknown triples, the evaluator learns the structural and uncertain
information to evaluate its rationality and obtain a candidate set. The confidence generator then determines
the confidence of the candidate set to achieve KGC. To verify the effectiveness of the proposed model,
confidence prediction, triple evaluation, and fact classification tasks are performed on three data sets.
Experimental results show that SUKE performs better than mainstream embedding methods. 
