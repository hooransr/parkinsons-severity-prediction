
# Parkinson’s Disease Severity Prediction Using Voice Biomarkers

Machine learning regression project exploring computational approaches for neurological disease assessment using acoustic voice biomarkers.

---

## Overview

Parkinson’s disease (PD) is a progressive neurodegenerative disorder that affects motor control, coordination, and speech production. Vocal impairments are among the most common non-motor manifestations of Parkinson’s disease and may provide valuable insight into disease progression.

This project investigates whether quantitative voice measurements can be used to predict Parkinson’s disease severity using machine learning regression models.

The goal of this work is to explore the relationship between speech-derived biomedical features and clinical severity scores, with a focus on computational neuroscience and digital neurological biomarkers.

---

## Clinical Motivation

Neurological disorders frequently produce subtle changes in speech and motor behavior before severe clinical symptoms emerge. In Parkinson’s disease, impaired motor regulation can affect vocal fold vibration, speech stability, respiratory coordination, and phonation dynamics.

Analyzing these acoustic changes computationally may contribute to:

- Non-invasive neurological assessment
- Remote disease monitoring
- Digital biomarker development
- AI-assisted clinical decision support
- Translational neurotechnology research

This project is inspired by the growing intersection of:
- Computational neuroscience
- Machine learning
- Biomedical signal analysis
- Neurotechnology
- Digital health

---

## Dataset

### UCI Parkinson’s Telemonitoring Dataset

The dataset contains biomedical voice measurements collected from individuals diagnosed with Parkinson’s disease.

### Example Features

- Fundamental frequency measurements
- Jitter
- Shimmer
- Harmonics-to-noise ratio
- Nonlinear vocal variation metrics

### Target Variable

The regression target is:

```python
total_UPDRS
````

UPDRS (Unified Parkinson’s Disease Rating Scale) is a widely used clinical metric for evaluating Parkinson’s disease severity and progression.

---

## Project Structure

```text
parkinsons-severity-prediction/
│
├── data/
│   └── parkinsons_updrs.csv
│
├── figures/
│   ├── correlation_heatmap.png
│   └── prediction_vs_actual.png
│
├── notebooks/
│   └── parkinsons_analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

## Methodology

### 1. Data Preprocessing

* Data cleaning
* Feature selection
* Missing value inspection
* Feature normalization

### 2. Exploratory Data Analysis

* Correlation heatmap visualization
* Statistical feature analysis
* Clinical interpretation of acoustic biomarkers

### 3. Machine Learning Model

Regression model used:

* Linear Regression

### 4. Evaluation Metrics

* Mean Squared Error (MSE)
* R² Score

---

## Example Visualizations

### Correlation Heatmap

![Correlation Heatmap](figures/correlation_heatmap.png)

### Prediction vs Actual Values

![Prediction vs Actual](figures/prediction_vs_actual.png)

---

## Results

The regression model demonstrated moderate predictive performance, highlighting the complexity and variability of neurological biomarkers in Parkinson’s disease.

The findings suggest that acoustic voice measurements may contain clinically relevant information associated with disease severity, while also reflecting the inherent noise and heterogeneity of biological data.

---

## Key Insights

* Certain voice biomarkers exhibit measurable correlation with Parkinson’s severity scores.
* Neurological speech impairments may provide meaningful computational biomarkers.
* Predicting disease severity from behavioral and biological signals remains a challenging problem due to patient variability and disease heterogeneity.

---

## Future Directions

Potential future improvements include:

* Advanced ensemble regression models
* Deep learning approaches
* Speech signal processing pipelines
* Longitudinal disease progression analysis
* Multimodal neurological biomarkers
* Integration with wearable and digital health systems

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Research Context

This project was developed as part of a self-driven transition toward computational neuroscience, neurotechnology, and AI-assisted biomedical research.

---

## Disclaimer

This project is intended solely for educational and research purposes.

It is not a clinical diagnostic system or medical decision-making tool.

---

## Author

Dentist transitioning toward computational neuroscience and interdisciplinary machine learning research.

```
```
