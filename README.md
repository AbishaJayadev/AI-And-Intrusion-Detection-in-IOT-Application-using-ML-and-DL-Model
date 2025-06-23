# AI-Based Intrusion Detection in IoT Using ML and DL

This project focuses on enhancing the security of IoT networks through Artificial Intelligence-based Intrusion Detection Systems (IDS). Using Machine Learning (ML) and Deep Learning (DL) models, we aim to detect and classify network intrusions across three real-world datasets.

## Project Overview

With the growing number of Internet of Things (IoT) devices, the risk of cyberattacks has significantly increased. Traditional security measures often fall short due to the lightweight nature and resource constraints of IoT systems. This project proposes AI-powered IDS models capable of real-time intrusion detection that are also optimized for performance and efficiency.


## Models & Techniques

We explored both ML and DL approaches:

- **Machine Learning Models:** Random Forest, SVM, Decision Tree (using Scikit-learn)
- **Deep Learning Models:** Neural Networks (using TensorFlow/Keras)

Each model was trained and evaluated independently on the following datasets.
## Datasets Used

1. **UNSW-NB15**  
2. **CIC-IDS2017**  
3. **NSL-KDD**

Each dataset includes diverse attack types (e.g., DoS, brute-force, botnet, probing), enabling robust evaluation.

## Methodology

- Data Preprocessing: Encoding, normalization, and cleaning
- Feature Selection: Correlation filtering + feature importance (Random Forest)
- Model Training: Hyperparameter tuning with grid search & cross-validation
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Comparison of ML vs. DL: Accuracy vs Resource Efficiency

## Key Findings

| Dataset       | ML Accuracy | DL Accuracy |
|---------------|-------------|-------------|
| UNSW-NB15     | 92.12%      | 92.30%      |
| CIC-IDS2017   | 100%        | 100%        |
| NSL-KDD       | 98.85%      | 97.19%      |

- ML models like **Random Forest** often outperform DL models in **efficiency** and **interpretability** while maintaining high accuracy.
- DL models can learn complex patterns but are resource-intensive and slower to train.


