# Diabetes and stroke Analysis

## Overview

This project investigates the relationship between diabetes and stroke using two distinct datasets. The first dataset contains information related to diabetes diagnosis, while the second focuses on stroke diagnosis. Although these datasets were collected independently, common features such as high blood pressure, smoking status, and BMI were selected for analysis.

The project consists of three main steps:
1. Distribution and Frequency Analysis: Examined the distribution and frequency of high blood pressure, smoking status, and BMI for diabetes and strokes separately.
2. Impact Analysis: Assessed how each of these factors influences diabetes and stroke outcomes individually.
3. Dataset Merging: Merged the datasets based on shared parameters to explore potential links between diabetes and strokes.

## Dataset Source

The dataset used for this project is available on Kaggle: [Health Dataset](https://www.kaggle.com/datasets/prosperchuks/health-dataset/data)

## Libraries and Modules Used

- dash: Interactive web applications
- matplotlib.pyplot: Static and interactive visualizations
- numpy: Numerical operations and array handling
- pandas: Data manipulation and analysis
- seaborn: Statistical data visualization
- bokeh: Interactive plots
- scipy: Scientific and statistical computing
- statsmodels: Statistical models and hypothesis testing
- webbrowser: Opening web pages
- threading: Concurrent code execution
- yaml: Reading and writing YAML files

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/aliakhlaghiii/diabetes_stroke.git
```

### 2. Set Up Virtual Environment
#### Windows
```bash
python -m venv venv
venv\Scripts\activate
```

#### Mac/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install dash matplotlib numpy pandas seaborn bokeh scipy statsmodels pyyaml
```

### 4. Run Jupyter Notebook
```bash
jupyter notebook
```

## Contact

- **Author:** Ali Akhlaghi
- **Email:** a.akhlaghi@st.hanze.nl
