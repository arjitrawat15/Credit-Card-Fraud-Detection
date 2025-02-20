# Credit-Card-Fraud-Detection
# Credit Card Fraud Detection

## Overview
Credit card fraud detection is a crucial application of machine learning in the financial sector. This project leverages **Logistic Regression** to identify fraudulent transactions based on historical transaction data. By analyzing patterns and anomalies, the model aims to differentiate between legitimate and fraudulent transactions effectively.

## Dataset
The dataset used in this project is a publicly available credit card transactions dataset, typically derived from real-world financial data. The dataset consists of multiple transaction features, including:
- Transaction amount
- Timestamp
- Various anonymized numerical features obtained via PCA
- Class label (0: Normal transaction, 1: Fraudulent transaction)

## Methodology
The project follows these key steps:
1. **Data Preprocessing**: Handling missing values, feature scaling, and balancing the dataset.
2. **Exploratory Data Analysis (EDA)**: Understanding feature distributions, correlations, and fraud patterns.
3. **Model Selection**: Implementing and evaluating **Logistic Regression** as the primary classifier.
4. **Performance Evaluation**: Using metrics like accuracy, precision, recall, F1-score, and ROC-AUC score.

## Implementation
The model is trained using **Scikit-Learn** and implemented in Python. The core steps include:
- Splitting the dataset into training and testing sets
- Applying feature scaling using **StandardScaler**
- Training the Logistic Regression model
- Evaluating performance on test data

## Results
The model’s effectiveness is evaluated using:
- **Confusion Matrix**: To visualize true positives, true negatives, false positives, and false negatives.
- **Precision & Recall**: To measure the model’s ability to correctly identify fraudulent transactions.
- **ROC-AUC Score**: To assess the overall classification performance.

## Usage
To run the project:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Future Improvements
- Experiment with advanced machine learning models such as Random Forest, SVM, or Neural Networks.
- Implement real-time fraud detection.
- Use **SMOTE (Synthetic Minority Over-sampling Technique)** to address class imbalance.

## Contributions
Contributions are welcome! Feel free to submit pull requests or report issues.

## License
This project is licensed under the MIT License.

