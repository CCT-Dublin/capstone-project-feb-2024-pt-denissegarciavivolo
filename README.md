
**Student ID:** SBS24050

**Author:** Denisse Garcia  
**Program:** Higher Diploma in Science in Artificial Intelligence – CCT College Dublin

# Capstone Project: Customer Satisfaction Prediction Using Machine Learning

This project aims to predict Customer Satisfaction (CSAT) scores using machine learning techniques applied to two distinct datasets: a structured dataset and a text-based support dataset. The goal is to explore how different types of data influence the predictive performance and to identify the most viable model for real-world deployment.
This capstone project navigates complex ethical considerations, ensuring compliance with global data protection regulations and prioritizing user privacy. By employing fairness-aware machine learning techniques and promoting transparency and accountability, the project aims to develop a predictive model that optimizes resource allocation. 

## Problem Statement

The objective is to build classification models that accurately predict CSAT ratings (1 to 5 scale), comparing performance across two different types of datasets:
- **Dataset 1:** Text-based customer support interactions
- **Dataset 2:** Structured enterprise data with metrics like response time, ticket channel, and priority

## Tech Stack

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- LightGBM
- Seaborn & Matplotlib (for data visualization)

## Visualizations

The project includes:
- Count plots and boxplots for ticket volume and resolution time
- Confusion matrices for each model
- Model performance comparison bar charts using `viridis`, `plasma`, and `cividis` palettes
- Missing value heatmaps and pie charts
- Radar (spider) plots for overall model metrics

## Models Compared

| Model         | Accuracy (Data2 - Structured) | Accuracy (Data1 - Text) |
|---------------|------------------------|------------------|
| LightGBM      | 62.16% ✅               | 20.25%           |
| Random Forest | 55.62%                 | 21.13%           |
| Decision Tree | 48.43%                 | 20.90%           |

> LightGBM on structured data showed the best overall performance and is recommended for production use.

## Methodology

1. Business Understanding
2. Data Exploration & Cleaning
3. Feature Engineering
4. Model Training & Evaluation
5. Visualization & Reporting
6. Future Work Recommendations

## Future Work

- Integrate BERT embeddings for unstructured data.
- Combine both structured + NLP features for hybrid modeling.

## Insights

- Structured data delivered 3× better performance than text-based inputs.
- LightGBM was the most accurate and efficient model.
- Data quality and balance significantly impacted results.

## Data Sources

- Kaggle Customer Support Dataset  
- Synthetic Structured Dataset (anonymized enterprise data)

## 🧾 License

This project is for educational and academic use only. Please contact the author for permission to use in a commercial setting.



