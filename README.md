# Housing_price_prediction
## Overview
This repository contains a machine learning project focused on predicting housing prices based on multiple features of houses. The project employs several advanced statistical methods and machine learning techniques to ensure accurate predictions and robust model performance.

## Key Features
### Recursive Feature Elimination (RFE): 
Utilized to identify and retain the most significant features, thereby improving model accuracy and computational efficiency.
### Variance Inflation Factor (VIF): 
Analyzed to detect multicollinearity among features, ensuring that our model estimates are reliable and stable.
### Coefficient of Determination (R² Score): 
Employed to quantify the model's explanatory power, reflecting the percentage of the target variance that our model can explain.
### Interquartile Range (IQR): 
Used for robust scaling and outlier detection, enhancing the model's performance by normalizing feature distributions and mitigating the impact of outliers.
### MinMax Scaling: 
Applied to normalize the feature set, which facilitates faster convergence during model training and prevents biases associated with the scale of features.
### Exploratory Data Analysis (EDA): 
Conducted to understand distributions, relationships, and potential anomalies within the data, informing preprocessing and modeling strategies.
## Technical Stack
Python: Primary programming language.
Pandas/NumPy: Data manipulation and numerical analysis.
Statsmodels: Regression analysis to build the Ordinary Least Squares (OLS) model.
Seaborn/Matplotlib: Data visualization.
Scikit-Learn: Additional machine learning utilities.
Model
The core of the project is the OLS regression model, chosen for its simplicity and interpretability. The model is built using the statsmodels library, which provides extensive statistical diagnostics.

## Data
The dataset comprises several features related to housing such as area, number of bedrooms, proximity to key locations, and others. These features were rigorously cleaned, scaled, and transformed to be suitable for regression analysis.


## Results
The model achieved a high R² score, indicating strong predictive performance. Plots and statistical summaries from the EDA are available in the notebooks/ directory, providing insights into the dataset and modeling process.

## Future Work
Explore more sophisticated regression models like Ridge or Lasso.
Implement machine learning pipelines for live data predictions.
Enhance the model's ability to handle new, unseen data through additional feature engineering and cross-validation techniques.
## Contributors
Garimella Narasimha Sai Varun
