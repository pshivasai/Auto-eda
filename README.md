# Auto-EDA: Interactive Exploratory Data Analysis Tool

An interactive web application built with Streamlit that automates the Exploratory Data Analysis (EDA) process. Upload your dataset and instantly generate key summaries and visualizations without writing a single line of code.

---

## 🌟 Overview

**Auto-EDA** is designed to accelerate the initial data analysis workflow for data scientists, analysts, and students. Instead of manually writing repetitive code in a notebook for every new dataset, this tool provides an interactive interface to perform common EDA tasks, from basic data summaries to complex multivariate analysis.

The project is built with a modular `eda_engine` backend, allowing its functions to be directly imported and used in any Python script or Jupyter Notebook for more customized analysis.

>

---

## ✨ Key Features

### 📊 Data Summary:
- DataFrame shape and column data types.
- Descriptive statistics (`.describe()`).
- Missing value counts and percentages.

### 📈 Univariate Analysis:
- Histograms  
- Kernel Density Plots (KDE)  
- Box Plots  

### 📉 Bivariate Analysis:
- Scatter Plots  

### 🌐 Multivariate Analysis:
- Pearson Correlation Heatmaps  
- Spearman Rank Correlation Heatmaps  

### ⚙️ Dual-Use Design:
- **Interactive App**: A user-friendly Streamlit interface for no-code analysis.  
- **Importable Library**: A modular `eda_engine` that can be imported into notebooks for code-based workflows.

---

## 🛠️ Technologies Used

- **Backend**: Python  
- **Web Framework**: Streamlit  
- **Data Manipulation**: Pandas  
- **Data Visualization**: Plotly, Seaborn  

---

## 🚀 Getting Started

### Prerequisites
Make sure you have **Python 3.9 or higher** installed on your system.

### Installation

Clone the repository:

```bash
git clone https://github.com/pshivasai/Auto-eda.git
cd Auto-eda
