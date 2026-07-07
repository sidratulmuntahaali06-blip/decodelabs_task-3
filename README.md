# decodelabs_task-3
---

## 🚀 Project 3: Unsupervised Learning (Customer Segmentation)

### 📌 Project Overview
This project focuses on driving business strategy by identifying hidden mathematical groupings within unlabeled retail data. High-dimensional customer features are processed and compressed using advanced unsupervised learning techniques to extract clear, actionable business personas.

### 🛠️ Key Technical Requirements & Milestones
* **Dimensionality Reduction (PCA):** Applied Principal Component Analysis (PCA) to successfully compress 20+ feature columns down into 3 principal components while retaining optimal dataset variance.
* **Mathematical Validation of Clusters:** Proven the optimal number of K-Means clusters (K=3) using a data-driven approach via the **Elbow Method (WCSS)** and **Silhouette Scores**.
* **3D Visualizations:** Rendered the reduced PCA dimensions in a scatter plot to visually inspect cluster separation and structural density.
* **Business Intelligence Translation:** Mapped mathematical cluster attributes back to original retail scales to build distinct, strategic market personas.

### 👥 Extracted Business Personas
| Cluster / Persona | Core Behavior | Actionable Marketing Strategy |
| :--- | :--- | :--- |
| **0. The Bargain Hunters** | Low average spend, high recency, high sensitivity to sales. | Target with clearance event alerts and flash discounts. |
| **1. The Loyal Enthusiasts** | High total spend, frequent purchase history, low return rates. | Enroll in VIP loyalty tiers, grant early access to new arrivals. |
| **2. The Seasonal Whales** | High transaction value but low purchase frequency. | Deploy re-engagement campaigns and exclusive seasonal gift guides. |

### 🧮 Tech Stack & Skills
* Python (Pandas, NumPy)
* Scikit-Learn (StandardScaler, PCA, KMeans, silhouette_score)
* Data Visualization (Matplotlib, Seaborn, Plotly)
* Business Intelligence Translation
