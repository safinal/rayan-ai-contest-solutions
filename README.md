# Rayan AI Contest Solutions

## 🚀 Challenges & Solutions

This repository serves as the entry point for our solutions to three distinct machine learning challenges. Below is a high-level overview of our approach for each task.

### 🧩 Compositional Image Retrieval (1st Place)
* **Objective:** Retrieve images based on a reference image and a textual modification (e.g., "remove motor and add microwave").
* **Approach:** We utilized a two-stage pipeline consisting of a **Token Classification** module for semantic parsing and **Compositional Embedding Arithmetic** to modify visual representations in the latent space.
* **Performance:** 95.38% Accuracy.
* **Repository:** [compositional-image-retrieval](https://github.com/safinal/compositional-image-retrieval)

### 🔍 Zero-Shot Anomaly Detection (2nd Place)
* **Objective:** Detect and localize anomalies in industrial and medical images without prior exposure to abnormal examples (Zero-Shot setting).
* **Approach:** We adopted the **MuSc framework** (Mutual Scoring of unlabeled images) combined with a custom post-processing masking strategy to handle background noise in industrial datasets.
* **Performance:** 73.14% Score.
* **Repository:** [zeroshot-anomaly-detection](https://github.com/safinal/zeroshot-anomaly-detection)

### 🛡️ Backdoored Model Detection (2nd Place)
* **Objective:** Distinguish between clean and backdoored neural networks without knowing the specific attack type or trigger structure.
* **Approach:** We implemented **Activation Perturbation Optimization** to reverse-engineer latent triggers, followed by a statistical outlier detection method using exponential distribution fitting.
* **Performance:** 78% Accuracy.
* **Repository:** [backdoored-model-detection](https://github.com/safinal/backdoored-model-detection)

## 🏆 Final Leaderboard
The final leaderboard ranking was determined by Total Points, calculated as:

$$\text{Total Points} = \sum_{i=1}^{3} (101 - \text{rank}_i)$$

where $\text{rank}_i$ denotes the team's rank in the $i$-th challenge. Our cumulative 298 points placed us at the top of the final leaderboard, as shown in the following Table.

| **Rank** | **Team**                             | **Rank in Compositional Image Retrieval** | **Rank in Zero-Shot Anomaly Detection** | **Rank in Backdoored Model Detection** | **Total Points** |
|----------|--------------------------------------|-------------------------------------------|-----------------------------------------|----------------------------------------|-----------------|
|🥇        | **No Trust Issues Here (Our Team)**  | **1**                                     | **2**                                   | **2**                                  | **298**         |
|🥈        | Pileh                                | 4                                         | 1                                       | 6                                      | 292             |
|🥉        | AI Guardians of Trust                | 2                                         | 6                                       | 4                                      | 291             |
| 4        | AIUoK                                | 9                                         | 3                                       | 5                                      | 286             |
| 5        | red_serotonin                        | 3                                         | 7                                       | 9                                      | 284             |
| 6        | Persistence                          | 7                                         | 11                                      | 3                                      | 282             |
| 7        | GGWP                                 | 6                                         | 9                                       | 11                                     | 277             |
| 8        | Tempest                              | 11                                        | 5                                       | 13                                     | 274             |
| 9        | AlphaQ                               | 5                                         | 10                                      | 16                                     | 272             |
| 10       | Cogniverse                           | 20                                        | 13                                      | 12                                     | 258             |

## 📄 Technical Report
For a detailed explanation of our methodologies, experiments, and results, please refer to our full [Technical Report](https://arxiv.org/abs/2512.01498).
