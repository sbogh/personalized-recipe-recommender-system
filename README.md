# Personalized Recommender System

## Overview
This repository contains the [implementation](https://github.com/sbogh/personalized-recipe-recommender-system/blob/main/CSE_258_Assignment_2_Notebook.ipynb) for a set of hybrid recommender system models for the Food.com Recipe Dataset found [here](https://cseweb.ucsd.edu/~jmcauley/datasets.html#foodcom).

## Abstract
This paper presents a personalized recipe recommendation system based on user-recipe interaction data
and individual preferences. We propose two hybrid models: (1) one that combines content-based filtering
with collaborative filtering through an optimized Singular Value Decomposition (SVD) approach and (2)
another that integrates content-based filtering with a logistic regression model. We evaluate these models
against several baselines, including popularity-based, Jaccard and cosine similarity, and standalone collaborative filtering models. Our analysis reveals that the SVD model’s performance was constrained by
the sparsity of user interaction data, limiting the effectiveness of its collaborative filtering component. As
a result, content-based filtering became the primary driver of recommendations. In contrast, the hybrid
content-based filtering and logistic regression model outperformed baselines, achieving superior accuracy and precision. The results highlight the potential of hybrid models in capturing user preferences,
with opportunities for future improvements in handling sparse datasets and enhancing personalization.

## Paper
The full paper can be found [here](https://github.com/sbogh/personalized-recipe-recommender-system/blob/main/CSE_258_Assignment_2_Paper.pdf).