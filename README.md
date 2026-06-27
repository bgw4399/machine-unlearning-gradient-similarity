# Machine Unlearning with Gradient Similarity Initialization

Public-safe research summary for the Machine Unlearning work accepted to PoPETs 2026.

## Overview

This research studies how to initialize model weights for Machine Unlearning using gradient similarity. The goal is to reduce the cost of retraining while balancing retained-data performance, forgotten-data removal, and privacy-related metrics.

## Motivation

Machine Unlearning is not only about lowering accuracy on data to be forgotten. A useful method must also preserve performance on retained data and avoid leaking information about removed samples. This project explored initialization and training strategies that make that tradeoff more stable.

## Experiments

- Gradient similarity-based weight initialization
- Pruning-based unlearning baselines
- Knowledge distillation-style transfer experiments
- Poisoning experiments to check whether changes led to meaningful robustness/performance differences
- Retain/forget split evaluation and privacy metric review
- Kaggle-style teamwork and private-data generalization strategy from the NeurIPS Machine Unlearning Challenge

## Results

- PoPETs 2026 accepted research
- NeurIPS 2023 Machine Unlearning Challenge 2nd Place experience connected to the research direction
- Built experimental habits around reproducibility, ablation, and private-score generalization rather than only public-score optimization

## Public Sharing Notes

Do not upload private competition data, restricted model artifacts, reviewer materials, or unpublished manuscript files unless sharing is explicitly allowed. This repository should contain public-safe notes, sanitized experiment scripts, and reproduction guidance.
