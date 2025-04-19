# McGill_BIOS_694_Project_NexCP
## Description

This repository contains the code and results for reproducing the findings presented in the article *"Conformal Prediction Beyond Exchangeability"*. The reproduction study uses the **electricity dataset**, originally used in the paper, to investigate the effects of various weighting schemes on nonexchangeable conformal prediction performance.

This project was completed as the final project for **BIOS 694 (Winter 2025 Term)** at **McGill University**.

We evaluate four different weighting schemes:
- \( w_i = 0.99^{N+1-i} \) — the original weight proposed in the article,
- \( w_i = 0.96^{N+1-i} \),
- \( w_i = 0.93^{N+1-i} \),
- \( w_i = 0.90^{N+1-i} \).

These weights allow us to explore how different rates of exponential decay influence empirical coverage under nonexchangeable conformal prediction.

## Data

The required dataset is available at:  
👉 [data/](https://github.com/qc-zhao/McGill_BIOS_694_Project_NexCP/tree/main/data)

## Code

The replication code is located in:  
👉 [src/](https://github.com/qc-zhao/McGill_BIOS_694_Project_NexCP/tree/main/src)

This code has been adapted from the original implementation provided by the authors of the article.

## Results

Empirical coverage results and associated visualizations can be found in:  
👉 [RESULTS/](https://github.com/qc-zhao/McGill_BIOS_694_Project_NexCP/tree/main/RESULTS)
