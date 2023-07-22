# Bank-Marketing

This repository contains a Python script that analyzes and models the `bank.csv` dataset. The script uses `pandas`, `seaborn`, `matplotlib`, `scikit-learn` libraries to perform data preprocessing, feature engineering, and model selection. 

## Dependencies

- pandas
- seaborn
- matplotlib
- scikit-learn

## Installation

1. Clone the repository: 

   ```
   git clone https://github.com/Nishef/bank-marketing.git
   ```

## Usage

1. Load the dataset by running the `main.py` script:

   ````
   python main.py
   ````

2. The script will output the summary statistics of numerical variables, create a correlation matrix using seaborn's heatmap function, check for duplicated values, encode categorical columns, split the data into train and test sets, and create two machine learning models: a logistic regression model and a random forest classifier model.

3. The script will output the classification report and confusion matrix for each model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
