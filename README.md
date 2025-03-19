# CREDIT-CARD-FRAUD-DETECTION

## **Objective**
The goal of this project is to build a machine learning model that can distinguish fraudulent transactions from legitimate ones using historical transaction data.

## **Dataset**
The dataset consists of transaction records, including:
- Transaction amount
- User ID
- Merchant information
- Transaction timestamps
- Transaction category
- Fraud label (`is_fraud`)

##Project Structure
📂 Credit-Card-Fraud-Detection/
│── 📂 data/                # Directory for dataset files
│   ├── fraudTrain.csv      # Training dataset
│   ├── fraudTest.csv       # Test dataset
│
│── 📂 models/              # Stores trained models and scalers
│   ├── fraud_model.pkl     # Saved fraud detection model
│   ├── scaler.pkl          # Saved scaler for preprocessing
│   ├── trained_columns.pkl # Stores feature names for consistent predictions
│
│── 📂 notebooks/           # Jupyter notebooks for EDA and experiments
│   ├── exploratory_analysis.ipynb  # Notebook for data exploration and visualization
│
│── 📂 scripts/             # Python scripts for data preprocessing and utilities
│   ├── preprocess.py       # Data preprocessing script
│
│── 📜 train_model.py       # Script to train the machine learning model
│── 📜 predict.py           # Script to make predictions on new transactions
│── 📜 requirements.txt     # List of dependencies
│── 📜 README.md            # Documentation for the project
│── 📜 .gitignore           # Files to ignore in Git repository


## **Installation**
### **1. Clone the Repository**
```sh
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection

```
##Install Dependencies
pip install -r requirements.txt

## Train the model
python train_model.py


##Make Predictions
python predict.py --amt 50.0 --category "gas_transport" --merchant "fraud_Kirlin and Sons"

