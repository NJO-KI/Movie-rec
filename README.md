# DSA 4060 Week 1: Popularity-Based Movie Recommender

## Student Details
* **Name:** Monica Njoki
* **Student Number:** [Your Student ID Number]

## Project Overview
This repository contains a non-personalized movie recommender baseline constructed using Python, Pandas, and the MovieLens latest-small dataset. The system establishes two reference baselines for streaming homepages: a threshold-filtered popularity model and a Bayesian weighted-rating model.

## Dataset
* **Source:** [GroupLens MovieLens latest-small Dataset](https://grouplens.org/datasets/movielens/)
* **Files Used:** `movies.csv` (9,742 items) and `ratings.csv` (100,836 interactions)
* **Accessed:** September 2026

## Methods
1. **Exploratory Interaction Analysis:** Aggregation of explicit user ratings, score distributions, and matrix sparsity calculations (98.30%).
2. **Minimum-Rating Popularity Baseline:** Filtering titles below a fixed threshold ($N=50$) and ordering by average score.
3. **IMDb Weighted Rating Baseline:** Regularizing ratings using the global average mean ($C \approx 3.501$) and 90th percentile rating count ($m = 27.0$).

## Repository Structure
```text
dsa4060-week1-recommender/
├── data/
│   ├── movies.csv
│   └── ratings.csv
├── images/
│   └── top10_recommendations.png
├── notebooks/
│   └── week1_popularity_recommender.ipynb
├── .gitignore
├── README.md
└── requirements.txt
