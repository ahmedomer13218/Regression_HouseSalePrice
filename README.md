# House Sale Price Prediction: Regression Project  

This repository contains a comprehensive regression project focused on predicting house sale prices using the **House Sale Price Dataset** from a Kaggle competition. The dataset includes 81 features, offering a rich opportunity for data preprocessing, feature engineering, and advanced modeling techniques.  

## Table of Contents  
- [Overview](#overview)  
- [Dataset](#dataset)  
- [Key Features](#key-features)  
- [Project Workflow](#project-workflow)  
- [Project Structure](#project-structure)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

## Overview  
This project aims to predict house sale prices using a structured dataset. The workflow involves extensive preprocessing, feature engineering, dimensionality reduction, and experimentation with multiple regression models to achieve the best results.  

## Dataset  
The dataset used for this project can be accessed from the Kaggle competition: [House Prices Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).  

## Key Features  
1. **Data Cleaning**  
   - Dropped columns with more than 40% missing values.  
2. **Feature Engineering**  
   - Addressed multicollinearity.  
   - Created new features using domain-specific equations.  
   - Removed low-correlation features.  
3. **Feature Encoding**  
   - Applied Label Encoding, Frequency Encoding, Target Encoding, and One-Hot Encoding for categorical variables.  
4. **Handling Missing Values**  
   - Used KNNImputer and SimpleImputer.  
5. **Dimensionality Reduction**  
   - Leveraged PCA to simplify data without significant loss of information.  
6. **Modeling**  
   - Implemented Linear Regression, Ridge Regression (with multilinear and polynomial features), and Lasso Regression.  

## Project Workflow  
1. **Loading Data & EDA**  
   - Explored the data and visualized relationships among features.  
2. **Preprocessing**  
   - Cleaned data and filled missing values using advanced imputation techniques.  
3. **Feature Engineering**  
   - Enhanced the dataset by combining features and addressing multicollinearity.  
4. **Scaling and Transformation**  
   - Applied MinMax Scaling for standardizing feature ranges.  
5. **Modeling**  
   - Evaluated regression models to select the best-performing one.  

## Project Structure  
- `data.csv/`  
  - Contains the dataset and any related files.  
- `Regression_HouseSalePrice.ipynb/`  
  - Jupyter notebooks for data exploration, preprocessing, and modeling.  
- `README.md`  
  - Project documentation.  

## Installation  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/ahmedomer13218/Regression_HouseSalePrice  
   cd Regression_HouseSalePrice  
   ```
### Usage
Open and run the Regression_HouseSalePrice.ipynb notebook.

### Contributing
We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
