#  📊 Test-Data-Analysis-and-Adaptive-Limit-Setting

This project analyzes production test data from prototype optical modems and dynamically sets adaptive pass/fail thresholds using statistical techniques. It aims to improve quality control and reduce false failures during early-stage hardware testing.

## 🔍 Overview

The system performs:
- Ingestion and visualization of large-scale test data
- Statistical analysis of key electrical parameters (Voltage, SNR, Jitter, BER)
- Dynamic threshold calculation using IQR-based outlier detection
- Flagging of anomalous test entries
- Export of clean/flagged results for further review

  ## 📁 Project Structure

├── modem_test_data.csv # Sample test dataset
├── analysis.py # Python script for analysis & limit setting
├── flagged_test_data.csv # Output file with outlier flags
└── README.md # Project documentation

## 🛠 Technologies Used

- **Python**: pandas, numpy, matplotlib
- **MATLAB** (optional): visualization and limit calculation
- **CSV**: Input and output data format

  ## 📈 Key Features

- **Automated Analysis**: Processes and summarizes test data in seconds
- **Adaptive Limits**: Uses IQR-based logic to calculate dynamic thresholds
- **Visualization**: Histograms for identifying trends and anomalies
- **Exportable Reports**: Saves annotated data for QA teams
