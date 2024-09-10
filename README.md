# Explainable AI for Machine Fault Diagnosis: Understanding Features’ Contribution in Machine Learning Models for Industrial Condition Monitoring

A project focused on using Explainable AI (XAI) techniques to interpret machine learning models for diagnosing faults in medium-sized industrial bearings. This repository includes implementations of Support Vector Machine (SVM) and k-Nearest Neighbors (kNN) models, leveraging SHapley Additive exPlanations (SHAP) to provide insights into the contribution of different features to model predictions.

## Project Description

This repository hosts a machine learning project aimed at understanding and diagnosing faults in industrial bearings. The project is rooted in the work described in the paper *"Explainable AI for Machine Fault Diagnosis: Understanding Features’ Contribution in Machine Learning Models for Industrial Condition Monitoring"* by Brusa et al. (2023) [1], which investigates the use of SHAP values to make machine learning models more interpretable in the context of industrial condition monitoring.

[1] Brusa, E., Cibrario, L., Delprete, C., & Di Maggio, L.G. (2023). Explainable AI for Machine Fault Diagnosis: Understanding Features’ Contribution in Machine Learning Models for Industrial Condition Monitoring. *Applied Sciences*, 13(4), 2038. [https://doi.org/10.3390/app13042038](https://doi.org/10.3390/app13042038)

### Motivation

The motivation behind this project is to bridge the gap between the development of machine learning models and their interpretability in real-world industrial applications. The use of SHAP values helps in understanding the importance of different features in the decision-making process of machine learning models, ensuring that the models can be trusted and effectively applied in critical industrial environments.

## Features

- **Data Preprocessing and Feature Selection**: Comprehensive processing of vibration data and selection of relevant features based on their importance as described in the referenced paper.
- **Model Implementation**: Application of SVM and kNN models for fault diagnosis, with detailed evaluation of their performance.
- **SHAP Analysis**: Computation of SHAP values to interpret the models, identifying key features that contribute to the predictions.
- **Visualization**: t-SNE plots for dataset visualization and SHAP value plots for feature importance.

## Getting Started

1. **Clone the Repository**:
   ```bash
    git clone https://github.com/LGDiMaggio/Explainable-AI-for-Machine-Fault-Diagnosis.git

### Set Up Your Environment

#### Windows

1. **Create a Virtual Environment**:
   - Open Command Prompt (or PowerShell).
   - Navigate to the project directory:
     ```bash
     cd explainable-ai-machine-fault-diagnosis
     ```
   - Create a virtual environment:
     ```bash
     python -m venv venv
     ```

2. **Activate the Virtual Environment**:
   - In Command Prompt:
     ```bash
     venv\Scripts\activate
     ```
   - In PowerShell:
     ```bash
     .\venv\Scripts\Activate
     ```

3. **Install Dependencies**:
   - Ensure your virtual environment is activated, then install the required packages:
     ```bash
     pip install -r requirements.txt
     ```

#### Linux and macOS

1. **Create a Virtual Environment**:
   - Open a terminal and navigate to the project directory:
     ```bash
     cd explainable-ai-machine-fault-diagnosis
     ```
   - Create a virtual environment:
     ```bash
     python3 -m venv venv
     ```

2. **Activate the Virtual Environment**:
   ```bash
   source venv/bin/activate

3. **Install Dependencies**:
   - Ensure your virtual environment is activated, then install the required packages:
     ```bash
     pip install -r requirements.txt
     ```

### Explore the Notebooks
- Explore the Jupyter notebooks provided in the repository to understand the methodologies applied for fault diagnosis and model interpretation.

## Contributing

Contributions to this project are warmly welcomed. You can contribute by:
- Extending the methodologies or introducing new analysis techniques.
- Enhancing visualizations or contributing additional datasets.
- Reviewing or improving documentation.

Please fork the repository, make your changes, and submit a pull request for review.

## License

This project is licensed under the GNU General Public License v3.0. You are free to copy, distribute, and modify the software as long as you track changes/dates in source files. Any modifications to this project must also be made available under the GPL with attribution to the original authors.

For more details, see the LICENSE file in this repository.

## Acknowledgments

- Special thanks to the co-authors of the paper *"Explainable AI for Machine Fault Diagnosis: Understanding Features’ Contribution in Machine Learning Models for Industrial Condition Monitoring"* for their work.
- [@lucaCibrario](https://github.com/lucaCibrario) for coding activity within this project.

## Why Share This Project?

The techniques used in this project are crucial for advancing the field of machine fault diagnosis, especially in making machine learning models more interpretable and trustworthy in industrial applications. By sharing this project, we hope to contribute to the broader adoption of Explainable AI in industry and support ongoing research and development in this critical area.

