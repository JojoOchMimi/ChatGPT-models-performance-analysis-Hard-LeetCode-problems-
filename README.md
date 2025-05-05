# ChatGPT Models LeetCode Performance Analysis

This repository contains the results and statistical analysis of two experiments comparing the performance of three ChatGPT models—**GPT-3.5**, **GPT-4o**, and **o1**—on solving hard coding problems from **LeetCode**.

## 📊 Overview

The experiments were designed to evaluate how effectively each model solves coding challenges, using two different scoring approaches:

- **Aggregated Approach (2-out-of-3):** A problem is considered solved if a model solves it at least 2 out of 3 times.
- **Proportional Approach:** Scores are assigned based on how many of the 3 attempts were successful (0%, 33.33%, 66.67%, 100%).

## 📁 Repository Structure

```plaintext
📂 experiment-results/
    ├── Main experiment results of o1
    ├── Main experiment results of 4o
    ├── Main experiment results of 3.5
    ├── Post-experiment results of o1
    └── Post-experiment results of 4o

📂 unsolved-problems/
    ├── Unsolved problems by models in Main experiment
    └── Unsolved problems by models in Post-experiment

📂 statistical-analysis/
    ├── Pairwise p-value (Aggregated Approach, n=60)
    ├── Pairwise p-value (Proportional Approach, n=30)
    ├── Wald Confidence Interval (Aggregated Approach, n=60)
    └── Wald Confidence Interval (Proportional Approach, n=30)
