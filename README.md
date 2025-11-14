# shoe-type-classifier# Shoe Type Classifier — MLOps Project

This repository implements a 14-class shoe type classifier with a full MLOps pipeline:
- Dataset: hinata/kaggle-shoe-classification (HuggingFace)
- Model: PyTorch transfer learning (ResNet/EfficientNet variants)
- Tracking: MLflow experiments + Model Registry + aliases (champion/staging)
- Explainability: SHAP + LIME
- HPO: Optuna integration with MLflow logging
- Serving: PyFunc wrapper + Streamlit UI
- Dockerized MLflow & Streamlit
- CI/CD: GitHub Actions
