# Project - m3 - Ironhack Part-Time 🚀🚀

## Project Structure
* data
* EDA
* notebook
* predictions
## Introduction📢📢
In this project, we have a training dataset containing information about diamonds with various characteristics and a price column. We also have a test dataset to validate our results.

## Objective 📄
The goal is to train a model using the training data to predict the target (price) and find an effective and functional model based on MLflow.

## EDA (Diamonds) 📄
This project includes a thorough analysis of the data and its variables, which can be found in the EDA folder.

## Data Description📋
The dataset contains the following characteristics of diamonds:
- **price**: Price of the diamond.
- **carat**: Weight of the diamond.
- **depth**: Depth of the diamond.
- **table**: Width of the top of the diamond relative to its widest point.
- **x, y, z**: Dimensions of the diamond.
- **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal).
- **color**: Color of the diamond, ranging from D (best) to J (worst).
- **clarity**: Clarity of the diamond (I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF).

## Process
We used the MLflow technique:
1. Load the data.
2. Clean the data as outlined.
3. Perform feature engineering.
4. Test models and hyperparameters.
5. Review model results.
6. Return to step one until satisfied with the results.

## Best Result
### File: `cleaning-3-feature-engineering-with-outliers`

### Process Overview🛠️🛠️
In this notebook, we followed these steps:
- Loaded and reviewed the data.
- Applied feature engineering and created new features (volume, volume_per_carat, etc.).
- Used a RobustScaler to scale the data.
- Addressed outliers as they yielded better results.
- Performed one-hot encoding for categorical variables.
- Conducted grid search to identify optimal hyperparameters.
- Selected and trained the LightGBM model.
- Repeated the same process for test data.
- Generated predictions and saved them in the `predictions` folder.

## Requirements📦📦

### Python Version
plaintext
python==3.8.10

### Essential Packages
plaintext
numpy==1.21.2
pandas==1.3.3
matplotlib==3.4.3
seaborn==0.11.2

### LightGBM
plaintext
lightgbm==3.3.1

### Scikit-learn and Components
plaintext
scikit-learn==0.24.2

### Additional Libraries 
plaintext
scipy==1.7.1