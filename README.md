# Titanic Dataset EDA and Logistic Regression Model

This repository contains the Exploratory Data Analysis (EDA) and a logistic regression model for the Titanic dataset. The goal of this analysis is to understand the underlying patterns in the data and build a model to predict the survival of passengers.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [EDA Steps](#eda-steps)
  - [Loading the Data](#loading-the-data)
  - [Data Cleaning](#data-cleaning)
  - [Data Visualization](#data-visualization)
  - [Feature Engineering](#feature-engineering)
- [Logistic Regression Model](#logistic-regression-model)
  - [Model Training](#model-training)
  - [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this analysis is the Titanic dataset, which is available on [Kaggle](https://www.kaggle.com/c/titanic/data). The dataset provides information on the passengers aboard the Titanic, including whether they survived or not.

## Installation

To run this analysis, you need to have Python and the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## EDA Steps

### Loading the Data

The first step is to load the dataset into a pandas DataFrame.

### Data Cleaning

Data cleaning involves handling missing values, converting data types, and correcting erroneous values.

- **Handling Missing Values**: Identify and fill or drop missing values.
- **Converting Data Types**: Ensure all columns are of the appropriate data type.
- **Correcting Erroneous Values**: Check for and correct any obvious data entry errors.

### Data Visualization

Visualizing the data helps in understanding the distribution of variables and the relationships between them.

- **Univariate Analysis**: Histograms, bar plots, and box plots to explore individual variables.
- **Bivariate Analysis**: Scatter plots, correlation matrices, and pair plots to examine relationships between variables.

### Feature Engineering

Feature engineering involves creating new features or modifying existing ones to improve model performance.

- **Creating New Features**: Example - Extracting the title from the 'Name' column.
- **Modifying Existing Features**: Example - Converting categorical variables to numerical ones.

## Logistic Regression Model

### Model Training

We split the dataset into training and testing sets, trained a logistic regression model, and evaluated its performance.

### Model Evaluation

We evaluated the model using accuracy, confusion matrix, and classification report.

## Results

The results of the EDA and logistic regression model include:

- Insights gained from data visualizations.
- Summary statistics of key variables.
- New features created during the feature engineering process.
- Model performance metrics: accuracy, confusion matrix, and classification report.

## Conclusion

The EDA provides a solid foundation for building machine learning models. The logistic regression model achieved promising results, and further improvements can be made by exploring additional features and more complex models.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue to discuss any changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
