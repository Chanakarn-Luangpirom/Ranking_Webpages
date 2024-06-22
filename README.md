# Ranking Websites using Learning to Rank Algorithms

This repository contains implementations of various Learning to Rank (LTR) algorithms to rank webpages from the Microsoft Learning to Rank dataset. 
The algorithms are built from scratch using PyTorch, and include Pointwise, Pairwise, and Listwise approaches. 
Additionally, the project explores online learning to rank, where predictions are made in real-time to evaluate the regret incurred by each algorithm.


## Overview of LTR Algorithms Implemented

1. **Pointwise**: Treats ranking as a classification problem on individual documents.
2. **Pairwise**: Considers pairs of documents and aims to minimize the number of inversions in the predicted ranking.
3. **Listwise**: Directly optimizes the order of a list of documents.
