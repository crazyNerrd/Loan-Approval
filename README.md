---

# Loan Approval Prediction Project

## Overview
This project focuses on predicting loan approvals using a dataset with various applicant details. The process includes data preprocessing, feature engineering, model training, and evaluation using Decision Tree and Naive Bayes classifiers.

## Project Structure
- `loan-train.csv`: Training dataset
- `loan-test.csv`: Test dataset
- `loan_approval_prediction.ipynb`: Jupyter notebook with detailed analysis and code

## Skills and Technologies Used
- **Data Preprocessing**
  - Handling missing values
  - Data normalization (log transformation)
- **Feature Engineering**
  - Categorical data encoding
  - Feature scaling
- **Model Training**
  - Decision Tree Classifier
  - Naive Bayes Classifier
- **Model Evaluation**
  - Accuracy calculation
  - Performance metrics analysis
- **Data Manipulation**
  - pandas for data manipulation
  - numpy for numerical operations
- **Machine Learning**
  - sklearn for model training, evaluation, and preprocessing
- **Data Visualization**
  - Matplotlib for histogram plotting of transformed features

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-approval-prediction.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Navigate to the project directory:
   ```bash
   cd loan-approval-prediction
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook loan_approval_prediction.ipynb
   ```

## Data Preprocessing
- Handle missing values using mode and mean imputation.
- Apply log transformation to `LoanAmount` and `TotalIncome` for normalization.
- Encode categorical variables using LabelEncoder.
- Scale features using StandardScaler.

## Model Training and Evaluation
- Split the dataset into training and testing sets using `train_test_split`.
- Train Decision Tree and Naive Bayes classifiers.
- Evaluate models' accuracy using metrics from sklearn.

## Test Data Preparation
- Apply the same preprocessing steps to the test dataset.
- Make predictions using the trained Naive Bayes classifier.

## Results
- Display accuracy scores for both Decision Tree and Naive Bayes classifiers.
- Provide insights on model performance and potential improvements.

## Contributing
Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.

---

Feel free to adjust the sections and content according to your specific project details.
