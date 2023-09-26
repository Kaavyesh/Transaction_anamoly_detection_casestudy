# Transactions Anomaly Detection 

Anomaly detection is a critical aspect of data analysis, particularly in the context of financial transactions, where identifying fraudulent activities and outliers is paramount. This project aims to develop a robust model that accurately distinguishes legitimate financial transactions from potential anomalies. The goal is to safeguard the financial system from fraudulent activities, ensure customer trust, and minimize false positives that could inconvenience legitimate customers.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Analysis Steps](#analysis-steps)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In this project, we aim to:

- Build an effective anomaly detection model for financial transactions.
- Identify suspicious or fraudulent transactions based on the provided features.
- Minimize false positives to ensure the security of the financial system and maintain customer trust.

## Dataset

The dataset used for this analysis includes the following columns:

- `Transaction_ID`: Unique identifier for each transaction.
- `Transaction_Amount`: The monetary value of the transaction.
- `Transaction_Volume`: The quantity or number of items/actions involved in the transaction.
- `Average_Transaction_Amount`: The historical average transaction amount for the account.
- `Frequency_of_Transactions`: How often transactions are typically performed by the account.
- `Time_Since_Last_Transaction`: Time elapsed since the last transaction.
- `Day_of_Week`: The day of the week when the transaction occurred.
- `Time_of_Day`: The time of day when the transaction occurred.
- `Age`: Age of the account holder.
- `Gender`: Gender of the account holder.
- `Income`: Income of the account holder.
- `Account_Type`: Type of account (e.g., personal, business).

## Analysis Steps

1. **Data Preprocessing**: We loaded the dataset, handled missing data, and preprocessed the data to make it suitable for modeling.

2. **Model Selection**: For anomaly detection, we selected the Isolation Forest algorithm, known for its effectiveness in identifying anomalies in imbalanced datasets.

3. **Model Training**: We trained the Isolation Forest model on the preprocessed data, tuning hyperparameters to achieve the best performance.

4. **Model Evaluation**: We evaluated the model's performance using appropriate metrics, such as precision, recall, and F1-score, while considering the class imbalance.


## Usage

To run the analysis or reproduce the results, follow the steps in the Jupyter notebooks provided in the `notebooks/` directory.

## Contributing

If you have suggestions or improvements, please feel free to open an issue or submit a pull request or contact us at [your_email@example.com](mailto:kaavyeshsathuluri@gmail.com).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
