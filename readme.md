# Empirical Results of Skip List Analysis

This repository contains empirical results of the analysis of skip lists, a probabilistic data structure that allows for fast search, insertion, and deletion operations.

## upperbound_graph.ipynb

This Jupyter notebook contains the expected of the analysis of skip lists. Based on the Expected
cost and Variance calculated using mathematical analysis and Chebyshev's inequality, the notebook visualizes the upper bounds on the probability of the search cost exceeding the expected cost.

## test_expected_cost_skiplist.py

This Jupyter notebook contains the implementation and tests for the empirical cost of skip lists. It includes the following:
- Implementation of a skip list data structure with additional variables to compute costs.
- A test suite that runs multiple trials to compute the empirical expected cost of search operations in a skip list.
- Visualization of the empirical expected cost and comparison with theoretical expectations.