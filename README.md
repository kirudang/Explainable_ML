
# Understand the black-box - Explainable Machine Learning techniques

Interpretable ML Demonstration

## Description

This project aims to demonstrate the use of three common techniques for interpretable machine learning (ML) in Python: Partial Dependence Plot (PDP), LIME (Local Interpretable Model-agnostic Explanations), and SHAP (SHapley Additive exPlanations). It provides step-by-step examples of how to use these techniques for interpretability on different datasets.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Notebook Description](#notebook-description)
- [Comparative Analysis](#comparative-analysis)
- [Repository Structure](#repository-structure)
- [License](#license)

## Requirements

Before you begin, ensure you have met the following requirements:

- Python 3.x
- Jupyter Notebook

All the necessary Python packages are listed in the `requirements.txt` file.

## Installation

To install the required packages, run the following command:

```bash
pip install -r requirements.txt
```

## Usage

To use the project, follow these steps:

1. Clone this repository to your local machine.

2. Install the required packages as mentioned in the [Installation](#installation) section.

3. Open the Jupyter Notebook included in the project.

4. Follow the step-by-step examples in the notebook to understand and use the PDP, LIME, and SHAP techniques for model interpretability.

5. Analyze the comparative results of these techniques at the end of the notebook using the provided comparison table.

## Notebook Description

The Jupyter Notebook in this repository includes the following sections:

- PDP for Bike Rent Data: Demonstrates how to use Partial Dependence Plots for interpreting a machine learning model using bike rental data. It explains how the model works and how to interpret PDP plots.

![PDP](https://github.com/kirudang/Explainable_ML/assets/91911269/ecd4eec2-8939-4e67-b756-4db5cfb7d231)


- LIME for Image Classification: Illustrates the use of LIME to explain an image classification model. It provides insights into the model's predictions and how to interpret LIME plots.

![LIME](https://github.com/kirudang/Explainable_ML/assets/91911269/d9a0d978-c923-4eff-b18a-4627659e65b1)


- SHAP for Breast Cancer Classification: Shows how to use SHAP values for interpreting a breast cancer classification model. It describes the model's behavior and how to interpret SHAP plots.
<img width="925" alt="Force" src="https://github.com/kirudang/Explainable_ML/assets/91911269/4e5ec7d5-0f49-4ffd-bc1a-9a62c7088646">

![Waterfall](https://github.com/kirudang/Explainable_ML/assets/91911269/4d1e395a-95fc-4a01-9f6f-5af59957dab7)

- Comparative Analysis: Offers a comparative analysis of PDP, LIME, and SHAP, summarizing the strengths and weaknesses of each method for model interpretability.

## Comparative Analysis

The project concludes with a comparative analysis table, summarizing the key differences and benefits of using PDP, LIME, and SHAP for interpretability in machine learning.

## Repository Structure

The repository contains the following files and folders:

- `data/`: Folder containing datasets used in the notebook.
- `notebook.ipynb`: Jupyter Notebook with step-by-step demonstrations of PDP, LIME, and SHAP techniques.
- `requirements.txt`: A list of required Python packages for this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize the README to better suit your project's specific details and structure. Add more information or sections as needed. The README should provide clear and concise instructions for users to understand, install, and utilize your project.
