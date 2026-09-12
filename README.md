# Fraud Transaction Detection ML Model

This repository contains an implementation of a Fraud Transaction Detection Machine Learning (ML) model using the given dataset.The model is designed to identify potentially fraudulent activities based on historical transaction data.
The dataset contains the following columns:

- `step`: Represents the unit of time in the real-world, ranging from 1 to 743.
- `type`: Represents the type of transaction (e.g., payment, transfer, cash out, etc.).
- `amount`: Represents the transaction amount.
- `nameOrig`: Represents the customer who initiated the transaction.
- `oldbalanceOrg`: Represents the initial balance of the customer before the transaction.
- `newbalanceOrig`: Represents the new balance of the customer after the transaction.
- `nameDest`: Represents the recipient of the transaction.
- `oldbalanceDest`: Represents the initial balance of the recipient before the transaction.
- `newbalanceDest`: Represents the new balance of the recipient after the transaction.
- `isFraud`: Represents whether the transaction is fraudulent (1 if fraudulent, 0 otherwise).
- `isFlaggedFraud`: Represents whether the transaction is flagged as fraudulent (1 if flagged, 0 otherwise).

## Prerequisites

To run the Fraud Transaction Detection ML Model, you need to have the following prerequisites:

- Python (version X.X.X)
- Pandas (version X.X.X)
- Scikit-learn (version X.X.X)
- Jupyter Notebook (version X.X.X)

## Installation

1. Clone this repository to your local machine using the following command:

```
git clone https://github.com/your-username/fraud-transaction-detection-ml-model.git
```

2. Change into the project directory:

```
cd fraud-transaction-detection-ml-model
```

3. Install the required dependencies using pip:

```
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter Notebook file `fraud_transaction_detection.ipynb` using Jupyter Notebook.
2. Follow the instructions and run the cells in the notebook to train and evaluate the Fraud Transaction Detection ML model using the provided dataset.



