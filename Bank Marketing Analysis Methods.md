## Bank Marketing Analysis Methods
This code applies various data science methods to analyze bank marketing data. The main methods used are:

### Data Loading and Exploration
- pandas.read_csv() - Load data from CSV file into DataFrame
- df.describe() - Summary statistics of DataFrame
- df.isnull().sum() - Check for missing values
- df.corr() - Calculate correlation between columns
- sns.heatmap() - Visualize correlations
### Data Preprocessing
- df.select_dtypes() - Select columns by data type
- df.duplicated() - Check for duplicate rows
- train_test_split() - Split data into train/test sets
- LabelEncoder() - Encode categorical data
### Modeling
- make_pipeline() - Combine preprocessing and model steps
- GridSearchCV() - Tune hyperparameters via cross-validation
- LogisticRegression() - Fit logistic regression model
- RandomForestClassifier() - Fit random forest model
### Evaluation
- classification_report() - Evaluate model performance
- confusion_matrix() - Generate confusion matrix
- sns.heatmap() - Plot confusion matrix heatmap
This covers the key data manipulation, preprocessing, modeling, and evaluation methods applied in the code. The README provides a quick overview of the techniques used in the analysis.
