# Dry Beans Classification Analysis

Dataset Link : https://drive.google.com/drive/folders/11caqwnxX107ieNCke0Xi9ur152n04p3L?usp=share_link

## Overview
This project focuses on classifying different types of dry beans using machine learning models. The dataset contains various physical attributes of beans and seven distinct classes. This project demonstrates the process of dataset analysis, preprocessing, model training, evaluation, and generating predictions.

---

## Key Features
- **Dataset Exploration**: Analyzed the Dry Beans dataset to understand feature distributions and relationships.
- **Data Preprocessing**: Handled duplicate values, normalized features, and encoded categorical data.
- **Model Training**: Built and evaluated machine learning models using scikit-learn.
  - Train/test splitting for evaluation.
  - Feature scaling to optimize model performance.
- **Evaluation**: Achieved competitive accuracy in classifying beans across seven categories.
- **Insights**:
  - `DERMASON` is the most common class in the dataset.
  - Strong correlation observed between attributes like `Area` and `ConvexArea`.
- **Future Improvements**: Experimentation with advanced models (e.g., ensemble methods or neural networks) for better accuracy.

---

## Requirements
Install the following Python libraries before running the project:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them with:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn

