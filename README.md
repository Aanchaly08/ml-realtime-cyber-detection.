# ml-realtime-cyber-detection.

An empirical benchmarking framework evaluating Random Forest, SVM, and XGBoost classifiers for real-time network intrusion and phishing URL detection, focusing on the precision-latency trade-off.

## Project Overview
This repository contains the official open-source engineering implementation and data pipeline for our research paper evaluation: **"An Evaluation of Machine Learning Classifiers for Real-Time Phishing and Network Intrusion Detection."**

The objective of this project is to address the "Computational Precision-Latency Dilemma" in live security systems. While modern deep learning or gradient-boosted models achieve elite accuracy scores, their sequential compute requirements often bottleneck real-time firewalls. This framework provides an automated pipeline that ingests network logs and URL patterns, processes them, and simultaneously benchmarks three core classification boundaries (**Support Vector Machines, Random Forest ensembles, and XGBoost gradient architectures**) across statistical metrics (Accuracy, F1-Score) and physical compute constraints (Inference Latency in milliseconds).

machine-learning 
cybersecurity  
intrusion-detection 
phishing-detection 
xgboost 
random-forest
benchmarking 
python
