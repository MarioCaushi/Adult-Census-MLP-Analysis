# Adult Census MLP Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-teal?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?logo=plotly&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML%20Models-f7931e?logo=scikitlearn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)


## Project Overview
This repository hosts a detailed analysis of the Adult Census Income dataset, focusing on using advanced machine learning techniques to predict income levels. The primary goal is to explore various configurations of Multilayer Perceptrons (MLP) to determine which architectural choices optimize prediction accuracy. This project follows the full data science pipeline, from initial data collection and exploratory data analysis to complex model tuning and performance evaluation.

## Dataset Description
The dataset leverages the well-known Adult Census dataset, which captures information from the 1994 U.S. Census database. Key attributes include:

- **Age**
- **Workclass**
- **Education**
- **Marital Status**
- **Occupation**
- **Relationship**
- **Race**
- **Sex**
- **Capital Gain**
- **Capital Loss**
- **Hours per Week**
- **Native Country**

The objective is a binary classification task to predict whether an individual earns more than $50,000 annually.

### Data Source:
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)
- [Kaggle](https://www.kaggle.com/uciml/adult-census-income)

## Technical Workflow
1. **Data Collection**: Utilize Python libraries to fetch the dataset directly from public repositories.
2. **Exploratory Data Analysis (EDA)**: Perform comprehensive statistical analysis to understand the distributions and relationships of the dataset features.
3. **Preprocessing**: Standardize data handling to prepare for modeling, including dealing with missing values, encoding categorical variables, normalizing data and dimensionality reduction.
4. **Model Development**: Implement and iteratively refine multiple MLP architectures, exploring various depths and neuron configurations.
5. **Model Evaluation**: Systematically evaluate model performance using accuracy, precision, recall, and F1 scores. Detailed comparisons between baseline models and optimized versions are documented.

## Installation and Setup
Clone this repository and install required dependencies:

## Running the Notebooks
Navigate to the notebook directory within the cloned repository and launch Jupyter Notebook:

Open and run the notebooks in order to replicate the analysis and view the results.

## Results and Insights
The repository contains detailed Jupyter notebooks that provide insights into the data characteristics and the effectiveness of different MLP configurations. Results indicate that certain model architectures significantly outperform others, emphasizing the importance of hyperparameter tuning in predictive accuracy.

## How to Contribute
Interested in contributing? We welcome pull requests, bug reports, and other contributions. For major changes, please open an issue first to discuss what you would like to change.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments
- Thanks to the UCI Machine Learning Repository for providing the dataset.
- Appreciation to those who have contributed to public discussions and insights into income prediction modeling.

## Contact Information
For further inquiries, reach out via [GitHub issues](https://github.com/MarioCaushi/Adult-Census-MLP-Analysis/issues) or directly through my [GitHub Profile](https://github.com/MarioCaushi).
