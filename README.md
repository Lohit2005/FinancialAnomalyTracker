# Efficient Data Stream Anomaly Detection

## Overview
This project focuses on detecting anomalies in financial transactions, particularly credit card transactions, using advanced machine learning techniques. By simulating a continuous data stream, the goal is to identify unusual patterns that may indicate fraudulent activity.

## Objectives
- Develop a Python script that utilizes **Isolation Forest** and **Local Outlier Factor (LOF)** to detect anomalies.
- Analyze the effectiveness of both algorithms in identifying fraudulent transactions.
- Generate detailed statistics on the detected anomalies for better insights.

## Dataset
The project employs the **Credit Card Fraud Detection** dataset from Kaggle. It contains various features representing transactions, with labels indicating whether they are fraudulent or legitimate.

### Data Preview
Sample data format:
Time, V1, V2, ..., V28, Amount, Class 0, -1.35980713, 1.19185711, ..., -0.05395037, 149.62, 0 1, -1.35835305, 2.29212882, ..., 0.25542586, 2.69, 0 ...

## Getting Started

### Requirements
Ensure that you have the following installed on your machine:
- Python 3.x
- pip (Python package manager)

### Project Structure
Efficient_Data_Stream_Anomaly_Detection/ │ ├── anomaly_detection.py # Main script for anomaly detection. ├── requirements.txt # List of required Python packages. ├── .gitignore # Files to ignore in the repository. ├── README.md # Project documentation. └── creditcard.csv # The dataset for credit card transactions.

### Setting Up the Project

1. **Download the Dataset**:
   - Navigate to the [Kaggle dataset page](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
   - Log into your account and download the dataset as a ZIP file.
   - Extract the ZIP file and place `creditcard.csv` in the project directory.

2. **Clone the Repository**:
   Use the command below to clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Efficient_Data_Stream_Anomaly_Detection.git
3. Install Dependencies: Change to the project directory and install the required packages:
   cd Efficient_Data_Stream_Anomaly_Detection
   pip install -r requirements.txt
Running the Application

Execute the anomaly detection script via the command line:
python anomaly_detection.py
Output and Results

Upon execution, the script will display the number of detected anomalies by each algorithm. The results will be formatted as:
Anomaly Detection Results:
Isolation Forest - Anomalies Detected: X
Local Outlier Factor - Anomalies Detected: Y
References

    Credit Card Fraud Detection Dataset: Kaggle Dataset
    Isolation Forest: Documentation for Isolation Forest in scikit-learn
    Local Outlier Factor: Documentation for LOF in scikit-learn
    Matplotlib: Official documentation for the Python plotting library
    Pandas: Data analysis library for Python
    NumPy: Fundamental package for numerical computing in Python
    Online Anomaly Detection for Data Streams: StreamAD GitHub Repository
    Streaming Anomaly Detection Framework in Python: pysad GitHub Repository
    Research Papers: GitHub Repository
