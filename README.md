# Fingerprints-vs.-SMILES-BERT-Evaluating-Cancer-Drug-Prediction
This repository contains my MSc thesis project at the University of Glasgow (2025). The work compares traditional molecular fingerprints (ECFPs) with transformer-based SMILES-BERT embeddings for predicting cancer-related drugs using 12,306 DrugBank compounds (~1.8% cancer).

Five models (Logistic Regression, SVM, Random Forest, XGBoost, MLP) were benchmarked under severe class imbalance. Results show that tree-based ensembles with fingerprints consistently outperformed embeddings, achieving the best balance of recall and precision. Threshold analysis revealed that accuracy was misleading at default cutoffs, with F1-optimal thresholds providing the most practical trade-offs for early-stage screening.

This project demonstrates that fingerprints remain more reliable than embeddings for imbalanced biomedical tasks and proposes preventive measures such as hybrid features, fine-tuned embeddings, and advanced imbalance handling for future work.
