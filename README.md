# Deep Learning for Image-Based Diagnosis of Sleep-Disordered Breathing

## Overview

Sleep diagnostics are critical for identifying and managing a wide range of sleep disorders. However, traditional approaches often face challenges related to the variability of physiological signals, noisy data, and the complexity of sleep patterns. This repository introduces an advanced framework designed to tackle these challenges, combining the **Sleep Pattern Recognition Network (SPRNet)** with an **Integrated Diagnostic Strategy for Sleep Assessment (IDSSA)**.

SPRNet integrates multimodal physiological signals—such as EEG, ECG, and airflow—through dedicated feature extraction pipelines and temporal modeling. This is achieved via a hybrid BiLSTM (Bidirectional Long Short-Term Memory) and attention mechanism, allowing for accurate sleep stage classification and disorder detection.

Complementing SPRNet, IDSSA leverages domain-informed adaptive priors, multi-objective optimization, and temporal reasoning to enhance diagnostic robustness and personalization. It also incorporates attention mechanisms to capture temporal dependencies in both sleep staging and event detection, making the system more reliable and effective for clinical and home-based applications.

## Features

- **Multimodal Integration**: Combines EEG, ECG, and airflow signals to provide comprehensive sleep diagnostics.
- **Temporal Modeling**: Uses a hybrid BiLSTM and attention mechanism for accurate classification and event detection.
- **Probabilistic Modeling**: Addresses the variability in sleep transitions through domain-informed adaptive priors.
- **Multi-Objective Optimization**: Enhances performance by optimizing multiple objectives in sleep disorder detection.
- **Scalable and Reliable**: Suitable for both clinical settings and home-based applications.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.6+
- PyTorch
- TensorFlow (if applicable)
- Other dependencies specified in `requirements.txt`

### Clone the Repository

```bash
git clone https://github.com/your-username/sleep-disorder-diagnosis.git
cd sleep-disorder-diagnosis
