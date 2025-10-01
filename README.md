# Predicting the Beats-per-Minute of Songs

## Overview

This competition is part of the Kaggle Playground Series - Season 5, Episode 9 (2025). The goal is to predict the beats-per-minute (BPM) of songs using a synthetically generated dataset. The competition is designed to help participants practice and improve their machine learning skills through approachable challenges.

## Goal

The task is to build models that can accurately predict a song's BPM based on the provided features.

## Evaluation

Submissions are evaluated using **Root Mean Squared Error (RMSE)** between predicted and observed BPM values.

## Submission Format

Each submission must be a CSV file with the following format:

```
ID,BeatsPerMinute
524164,119.5
524165,127.42
524166,111.11
```

* The file must include a header row.
* Each `id` corresponds to an entry in the test set.
* `BeatsPerMinute` must be a continuous numeric prediction.

## Dataset

The dataset used in this competition is **synthetically generated**. This approach allows Kaggle to create realistic tabular datasets without releasing private labels. The synthetic data aims to be as artifact-free as possible, offering participants a practical experience similar to real-world datasets.

## Citation

Walter Reade and Elizabeth Park. *Predicting the Beats-per-Minute of Songs*. Kaggle, 2025.
[Competition Link](https://kaggle.com/competitions/playground-series-s5e9)
