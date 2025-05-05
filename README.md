# ChatGPT Models LeetCode Performance Analysis

This repository contains an Excel workbook that presents the results and statistical analysis of two experiments comparing the performance of three ChatGPT models—**GPT-3.5**, **GPT-4o**, and **o1**—on solving hard LeetCode problems.

## 🧪 Experiment Overview

The goal of this study was to evaluate and compare how well each model performed when solving challenging coding problems. Two types of scoring methods were applied:

- **Aggregated Approach (2-out-of-3):** A problem is considered solved if the model succeeds in at least 2 out of 3 attempts.
- **Proportional Approach:** Each problem is scored based on how many attempts were successful (0%, 33.33%, 66.67%, 100%).

Two experiments were conducted:
- **Main Experiment**: Used a benchmark problem set from Kuhail et al.
- **Post-Experiment**: Used a new problem set selected by the authors.

## 📘 Workbook Structure

The Excel workbook contains the following sheets:

1. **Experiment Results by Model**  
   Shows individual results for each model in both experiments, with links to detailed results within the workbook.

2. **Unsolved Problems**  
   Summarizes which problems were not solved by each model across experiments.

3. **Pairwise P-Value Comparison**  
   Displays statistical significance between models using Wald z-tests:
   - Aggregated Approach (n = 60)
   - Proportional Approach (n = 30)

4. **Wald Confidence Intervals**  
   Includes confidence intervals for each model's performance using both scoring methods.

## 📄 File

- `Experiment Result.xlsm`: The main workbook with all results and analyses.

## 🧠 Acknowledgments

This project was inspired by the benchmark study by Kuhail et al., whose curated LeetCode dataset was used in the main experiment:
https://github.com/kuhailamin/ChatGPT_data


