---
title: "EasyVisa"
emoji: 🛂
colorFrom: red
colorTo: indigo
sdk: static
app_file: easyvisa_project.html
license: mit
tags:
  - python
  - machine-learning
  - classification
  - immigration
  - predictive-modeling
  - notebook
---

# EasyVisa  
**Classification Modeling | Python | Immigration Services | Predictive Analytics**

## Project Overview  
This project presents a classification problem inspired by real-world immigration services. The objective is to develop a machine learning model that predicts the approval likelihood of visa applications, streamlining the decision-making process and aiding organizations in resource planning and applicant support.

This notebook was completed as part of the supervised machine learning module in the AI/ML Post Graduate Certification Program from the University of Texas at Austin.

## Business Objective  
An immigration consulting agency wants to improve the efficiency of their operations by predicting visa approval outcomes. With historical application data, the goal is to classify future applicants into approval-likely or denial-likely categories, enabling preemptive documentation support or client advisement.

## Tech Stack  
The analysis is conducted in **Python**, using the following libraries:

- `pandas` – data manipulation  
- `numpy` – numerical operations  
- `matplotlib` & `seaborn` – data visualization  
- `scikit-learn` – model development and evaluation  
- `imbalanced-learn` – addressing class imbalance  
- `plotly` – interactive visualizations

Files included:
- `easyvisa_project.ipynb` (Jupyter Notebook version)  
- `easyvisa_project.html` (rendered notebook)  
- `Visa_Applications.csv` (dataset)

## Key Insights

1. **High-Impact Features Identified:**  
   Variables such as applicant education, income bracket, and visa type significantly influenced approval outcomes.

2. **Model Accuracy Optimization:**  
   Random Forest Classifier and Decision Tree models demonstrated high accuracy and interpretability, achieving strong F1 and ROC-AUC scores.

3. **Practical Application:**  
   The model can help immigration consultants better assess client profiles, proactively recommend supporting documents, and reduce application denials.

## Sample Visualizations  
*Note: These are automatically generated from the notebook.*

- Feature importance plots  
- Decision tree visualizations  
- Confusion matrices  
- ROC curves  
- t-SNE projections of applicant clusters

## Getting Started

To reproduce the analysis locally:

```bash
# Clone the repository
git clone https://github.com/cslivingstoniii/aiml_ut_easyvisa.git
cd aiml_ut_easyvisa

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook easyvisa_project.ipynb
```

## What You’ll Learn by Reviewing This Project

- How to apply supervised learning to classification in legal/immigration contexts
- Model evaluation for imbalanced classification problems
- Data-driven decision support for business operations
- End-to-end ML pipeline development in Python

## About the Author

Hi, I’m Steve Livingston, a software engineer and AI/ML practitioner focused on using data to improve real-world systems. This project is part of my portfolio showcasing machine learning solutions that bridge technical innovation and operational value.

- Predictive modeling
- Classification workflows
- Real-world business intelligence
- Applied Python for decision-making

## My Links

- LinkedIn Profile: https://www.linkedin.com/in/cslivingstoniii
- GitHub Repos: https://github.com/cslivingstoniii
- HuggingFace Spaces: https://huggingface.co/cslivingstoniii
- Great Learning: https://www.mygreatlearning.com/eportfolio/carl-s-livingston

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Data and context adapted from the University of Texas AI/ML Post Graduate Certification Program.
- Notebook inspired by best practices from industry-grade classification modeling workflows.