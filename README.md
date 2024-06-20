# Project: Breast-Cancer-Classification

![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/3a9e4352-2394-4456-a036-4529a95b3ebf)

##### Workflow
![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/b66cfc44-9cfb-4314-87d0-1ece888eb6c2)

This project utilizes the Wisconsin breast cancer dataset to classify cancer types as benign or malignant using machine learning techniques and conducts statistical analysis to detect anomalies.

### Data Pre-processing:
  •	Initial data pre-processing involved removing unwanted information such as missing values and NaNs. Missing values were imputed using appropriate methods.

![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/4553a0b4-dc04-4f1b-b25f-52ce2086156a)

### Data Quality Analysis:
  •	Checking for NaNs: Identified and addressed missing values by either dropping them or using imputation methods.
  •	Checking for Duplicate Rows: Removed duplicate rows to avoid redundant information and reduce computational complexity.
  •	Checking for Duplicate Columns: Eliminated duplicate columns to prevent multicollinearity, ensuring features remain independent as required by parametric models.

### Statistical Analysis:
  •	Conducted various statistical analyses, including univariate and bivariate analyses, to identify outliers.
  •	Used histograms to visualize the distribution of datasets and detect outliers.
  •	Performed correlation analysis to assess relationships between features and examine the effects of correlation.
  •	Ranked features using the Shapiro-Wilk normality test and selected features based on ROC-AUC.

![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/05cea1e9-a4c0-45b8-8fd7-12ad3b7c1b97)

![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/1c9c0932-a8b9-4e23-acc1-0c676f99daf1) 

![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/34139a98-9022-4ef4-9e93-2c524006bb0c)

![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/341f675a-cb1b-4280-a901-42992b7b49cd)

### Modeling:
  •	Split the dataset into an 80/20 ratio for training and testing purposes.
  •	Utilized SGD Classifier, Decision Tree, and KNN Classifier for modeling breast cancer classification.
  •	Selected the best model from the baseline models.
  •	Optimized models through K-Fold cross-validation and grid search parameter tuning.
  • Utilized SHAP to explain the classification

![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/e46cfce1-a48c-4421-bb82-5986f6b2b703)
![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/8bf56092-f1cd-418b-8eb5-2d751c38c16f)
![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/c72936b7-e710-4e10-882c-7cb22dc1ac5a)
![image](https://github.com/Optimus-Q/Breast-Cancer-Classification/assets/46313772/a646865d-84cd-43f8-8449-04101b3f8955)
