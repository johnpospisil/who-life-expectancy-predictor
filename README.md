# 🌍 WHO Life Expectancy Prediction
![globe-7510104_1920](https://github.com/user-attachments/assets/f773c280-cd86-4f9d-8058-b2a2be1d493c)
Image by <a href="https://pixabay.com/users/lucasgeorgewendt-15638399/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7510104">Lucas Wendt</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7510104">Pixabay</a>

## 🔍 Overview
This repository contains a comprehensive analysis and predictive modeling project based on the WHO Life Expectancy dataset. The goal of this project is to predict life expectancy using a range of health, economic, and demographic indicators. The analysis includes extensive exploratory data analysis (EDA), feature engineering, and multiple linear regression modeling, with additional techniques such as regularization and interaction terms to improve model performance.

## 🗂️ Dataset
The dataset includes the following key features:
- **Country**: Names of the countries.
- **Region**: Geographic regions, highlighting global disparities.
- **Year**: Observation year.
- **Health Indicators**: Infant deaths, 0-5yrs deaths, adult mortality.
- **Economic & Social Metrics**: GDP per capita, schooling, population.
- **Vaccination Rates**: Hepatitis B, Polio, Diphtheria.
- **Development Status**: Binary indicator for developed vs. developing nations.

## 🧪 Methodology
The project follows these main steps:
- **Exploratory Data Analysis (EDA)**:  
  Detailed visualizations (histograms, scatter plots, pair plots) were used to uncover relationships and trends among the features.
- **Feature Engineering**:  
  Transformations such as log scaling, interaction terms (e.g., Developed × GDP per capita), and polynomial expansions were applied to capture non-linear effects and reduce multicollinearity.
- **Modeling**:  
  A multiple linear regression model was developed and evaluated using cross-validation and test set performance. Regularization techniques like Ridge and Lasso were explored to address multicollinearity.
- **Results**:  
  The final model achieved an exceptional test R² of approximately 0.99, demonstrating that the selected predictors explain nearly all the variance in life expectancy.

## 🚀 Results
- **Key Predictors**:  
  - **GDP per Capita**: Shows a strong positive and non-linear relationship with life expectancy (log transform applied).
  - **Schooling**: Higher educational attainment is associated with higher life expectancy.
  - **Adult Mortality**: A critical negative predictor.
  - **Development Status**: Developed countries consistently exhibit higher life expectancy.
- **Model Performance**:  
  The regression model achieved a test R² near 0.99, indicating outstanding predictive power.

## 🔧 Installation
To run the analysis locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/who-life-expectancy-prediction.git
   cd who-life-expectancy-prediction
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 💻 Usage
Open and run the Jupyter Notebook `who-life-expectancy-prediction.ipynb` to reproduce the full analysis, including:
- Data loading and preprocessing.
- Exploratory data analysis (EDA) with visualizations.
- Feature engineering and model building.
- Evaluation of multiple linear regression models.

## 🎯 Future Work
Future improvements may include:
- Incorporating advanced ensemble methods.
- Utilizing panel data techniques for longitudinal analysis.
- Further enhancing feature engineering with additional interaction and non-linear terms.
- Applying robust regression methods to mitigate the impact of outliers.

## 📜 License
This project is licensed under the [MIT License](LICENSE).

## 📫 Contact
For any questions or collaboration opportunities, please contact [Your Name](mailto:john@johnpospisil.com).

Enjoy exploring the data and uncovering insights that can help inform global public health strategies!
