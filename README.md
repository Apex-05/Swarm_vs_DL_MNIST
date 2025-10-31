# Swarm Intelligence vs Deep Learning on MNIST

This project compares **swarm-based optimization methods** (Particle Swarm Optimization and Grey Wolf Optimization) against a **conventional clustering method** (KMeans) for the task of image segmentation on the MNIST dataset.

The segmentation quality is evaluated using **Adjusted Rand Index (ARI)**, **Normalized Mutual Information (NMI)**, and the **Dice Coefficient**.

---

## Methods Used

- **KMeans Clustering**
- **Particle Swarm Optimization (PSO)**
- **Grey Wolf Optimization (GWO)**

Each method is used to find the optimal threshold for binary segmentation of MNIST images.

---

## Evaluation Metrics

- Adjusted Rand Index
- Normalized Mutual Information
- Dice Coefficient

Example Output (on 200 images):

| Metric               | KMeans        | PSO           | GWO           |
|----------------------|---------------|---------------|---------------|
| Adjusted Rand Index  | ≈ 0.9549 ± 0.0377 | ≈ 0.9547 ± 0.0379 | ≈ 0.7009 ± 0.0558 |
| Normalized Mutual Info | ≈ 0.9084 ± 0.0614 | ≈ 0.9081 ± 0.0618 | ≈ 0.6024 ± 0.0544 |
| Dice Coefficient     | ≈ 0.9681 ± 0.0277 | ≈ 0.9679 ± 0.0279 | ≈ 0.7974 ± 0.0485 |

---


