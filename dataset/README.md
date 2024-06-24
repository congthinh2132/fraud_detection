# PaySim Dataset

The PaySim dataset is a synthetic dataset created to simulate mobile money transactions. It was developed to study and detect fraudulent activities within financial transactions using machine learning algorithms. This dataset is particularly useful for researchers and practitioners working on fraud detection, financial analysis, and machine learning applications in finance.

## Dataset Description

The PaySim dataset contains a large number of simulated financial transactions, designed to reflect real-world mobile money transactions. The data includes various types of transactions, such as payments, transfers, and cash outs, along with their respective attributes.

### Features

The dataset includes the following features:

- **step**: This represents a unit of time within the simulation. Each step corresponds to a specific hour.
- **type**: Type of transaction. It can be one of the following: `PAYMENT`, `TRANSFER`, `CASH_OUT`, `DEBIT`, `CASH_IN`, `TRANSFER`, `PAYMENT`.
- **amount**: The amount of money involved in the transaction.
- **nameOrig**: The customer who initiated the transaction.
- **oldbalanceOrg**: The initial balance of the sender before the transaction.
- **newbalanceOrig**: The new balance of the sender after the transaction.
- **nameDest**: The recipient of the transaction.
- **oldbalanceDest**: The initial balance of the recipient before the transaction.
- **newbalanceDest**: The new balance of the recipient after the transaction.
- **isFraud**: This is the target variable for fraud detection. It indicates whether the transaction is fraudulent (1) or not (0).
- **isFlaggedFraud**: This indicates whether the transaction was flagged as fraudulent by the system (1) or not (0).

### File Information

The dataset is provided in CSV format and can be downloaded from Kaggle using the following link: [PaySim Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1/data).
