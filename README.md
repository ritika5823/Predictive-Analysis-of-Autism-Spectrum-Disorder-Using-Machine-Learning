# Predictive-Analysis-of-Autism-Spectrum-Disorder-Using-Machine-Learning
This project presents an intelligent Autism Spectrum Disorder (ASD) risk prediction system using an attention-based deep learning model. The system analyzes AQ-10 behavioral screening responses along with clinical factors such as age and jaundice history to classify individuals into Low, Medium, and High ASD risk categories.

The proposed framework integrates data preprocessing, feature engineering, attention-based neural learning, Explainable AI (SHAP), fairness evaluation, and real-time deployment using Streamlit. Interaction features and total AQ scores are generated to capture hidden behavioral relationships and improve prediction performance.

A custom PyTorch-based ASDTransformerModel is used to dynamically assign importance weights to behavioral features through an attention mechanism. SHAP explanations are incorporated to improve transparency and interpretability of predictions, making the system more clinically understandable. Fairness analysis using Equal Opportunity metrics is also performed to ensure unbiased performance across demographic groups.

The proposed model achieved high performance with:

* Accuracy: 96%
* Macro Precision: 94%
* Macro Recall: 95%
* Macro F1-Score: 95%

The system provides a scalable, interpretable, and ethical solution for early ASD risk assessment and demonstrates the potential of attention-based deep learning in healthcare applications.
