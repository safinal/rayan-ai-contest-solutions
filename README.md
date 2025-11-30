# Rayan AI Contest Solutions

## 🚀 Challenges & Solutions

This repository serves as the entry point for our solutions to three distinct machine learning challenges. Below is a high-level overview of our approach for each task.

### 🧩 Q5: Compositional Image Retrieval (1st Place)
* **Objective:** Retrieve images based on a reference image and a textual modification (e.g., "remove motor and add microwave").
* **Approach:** We utilized a two-stage pipeline consisting of a **Token Classification** module for semantic parsing and **Compositional Embedding Arithmetic** to modify visual representations in the latent space.
* **Performance:** 95.38% Accuracy.
* **Repository:** [compositional-image-retrieval](https://github.com/safinal/compositional-image-retrieval)

### 🔍 Q6: Zero-Shot Anomaly Detection (2nd Place)
* **Objective:** Detect and localize anomalies in industrial and medical images without prior exposure to abnormal examples (Zero-Shot setting).
* **Approach:** We adopted the **MuSc framework** (Mutual Scoring of unlabeled images) combined with a custom post-processing masking strategy to handle background noise in industrial datasets.
* **Performance:** 73.14% Accuracy.
* **Repository:** [zeroshot-anomaly-detection](https://github.com/safinal/zeroshot-anomaly-detection)

### 🛡️ Q7: Backdoored Model Detection (2nd Place)
* **Objective:** Distinguish between clean and backdoored neural networks without knowing the specific attack type or trigger structure.
* **Approach:** We implemented **Activation Perturbation Optimization** to reverse-engineer latent triggers, followed by a statistical outlier detection method using exponential distribution fitting.
* **Performance:** 78% Accuracy.
* **Repository:** [backdoored-model-detection](https://github.com/safinal/backdoored-model-detection)

## 🏆 Final Leaderboard

| **Rank** | **Team**                             | **Q5 Score (%)** | **Q6 Score (%)** | **Q7 Score (%)** |
|----------|--------------------------------------|------------------|------------------|------------------|
|🥇        | **No Trust Issues Here (Our Team)**  | **95.38**        | **73.14**        | **78**           |
|🥈        | AI Guardians of Trust                | 88.59            | 66.29            | 72               |
|🥉        | AIUoK                                | 78.32            | 72.98            | 70               |
| 4        | red_serotonin                        | 85.45            | 63.51            | 65            |
| 5        | Persistence                          | 80.63            | 61.62            | 74            |
| 6        | GGWP                                 | 80.97            | 62.25            | 63            |
| 7        | Tempest                              | 69.86            | 70.88            | 63            |
| 8        | AlphaQ                               | 82.89            | 62.15            | 60            |
| 9        | Cogniverse                           | 49.71            | 61.53            | 63            |
| 10       | AUTs                                 | -                | 60.84            | 79            |


## 📄 Technical Report
For a detailed explanation of our methodologies, experiments, and results, please refer to our full [Technical Report](./Technical_Report.pdf).
