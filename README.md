# Wine Quality Analysis

## Research Question
Which factors are associated with higher wine quality, and what differences exist between red and white wines?

## Dataset
- **Source:** Wine Quality Dataset from the UCI Machine Learning Repository.
- **Usage Permission:** The dataset is publicly available for educational and research purposes.

## Methods and Tools
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

## Visualizations

### Visualization 1: Alcohol vs Volatile Acidity and Wine Quality
<img width="1255" height="734" alt="visualization1_WineQuality_HighQualityZone" src="https://github.com/user-attachments/assets/4d292815-38fc-4c18-a76d-fdaaa637b8cf" />
This visualization shows that higher-quality wines tend to have higher alcohol content and lower volatile acidity.

### Visualization 2: Feature Correlation Heatmap
<img width="3270" height="2963" alt="visualization2_Wine Quality Dataset Correlation Matrix" src="https://github.com/user-attachments/assets/2d2097cd-c606-42da-b2ee-af43085d2c96" />
This visualization highlights relationships among the variables and their correlations with wine quality.

## Key Findings
1. Alcohol shows the strongest positive correlation with wine quality.
2. Volatile acidity is negatively correlated with wine quality.
3. Higher-quality wines are generally located in regions with higher alcohol content and lower volatile acidity.
4. Free sulfur dioxide and total sulfur dioxide display a strong positive relationship.

## Limitation
The dataset only contains physicochemical measurements and does not include consumer preferences, regional characteristics, or production methods.

## How to Run

Install required packages:

pip install -r requirements.txt

Run the notebook:

WineQualityVisualization.ipynb
