# DSCI 632 Final Project Analysis

## Project Overview
This project utilizes PySpark to analyze a dataset focusing on penalties in football games. The goal is to identify patterns related to player positions, teams, and penalty types to predict which players or teams are more likely to incur penalties. The analysis includes data cleaning, transformation, and a detailed exploration of penalty occurrences, culminating in the development of a logistic regression model to predict high penalty counts.

## Installation
To run this notebook, you need:
- Python 3.6 or later
- Apache PySpark
- Jupyter Notebook or JupyterLab

You can install the required libraries using pip:
pip install pyspark jupyterlab


## Usage
1. Clone the repository or download the Jupyter notebook file to your local machine.
2. Open the notebook in JupyterLab or Jupyter Notebook.
3. Run the cells in order to reproduce the analysis.

Ensure that you have Spark installed and configured correctly to run PySpark in Jupyter notebooks.

## Model Explanation and Justification
The choice of logistic regression for this analysis stems from its efficacy in handling binary classification problems, such as predicting whether a player's penalty count exceeds a certain threshold. Logistic regression is advantageous for its simplicity, interpretability, and the ability to estimate probabilities. However, its limitation lies in assuming a linear relationship between the independent variables and the log odds of the dependent variable, which might not always hold true. Alternative models were considered, but logistic regression was deemed most appropriate for the initial analysis due to its straightforward applicability to the problem at hand.

## Results
The logistic regression model provided insights into factors influencing penalty counts in football games. The analysis revealed that certain positions and teams have a higher likelihood of incurring penalties, supporting the hypothesis that specific patterns exist. The model's performance was evaluated using accuracy, precision, recall, F1 score, and ROC AUC score, offering a comprehensive understanding of its predictive capabilities.

## Future Work
Future analyses could improve upon this project by incorporating more granular data, such as specific game situations or player behavior patterns. Additionally, experimenting with more complex models or machine learning algorithms could refine the predictions and offer deeper insights.
