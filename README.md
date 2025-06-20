
# 🔐 Hybrid Anomaly and Signature-Based Intrusion Detection System (IDS)

This project implements a **hybrid IDS model** combining both anomaly detection (using LSTM and Isolation Forest) and signature-based methods to detect network intrusions effectively.

## 📁 Project Structure

```
Hybrid Anomaly and Signature-Based IDS/
│
├── archive/                              # Directory for archived models or data
├── content/                              # Directory possibly for Colab or related content
│
├── cic_final.ipynb                       # Final integrated notebook for CIC dataset
├── dataset.txt                           # Dataset or metadata description
│
├── initial_lstm+isolation.ipynb          # Hybrid model using LSTM and Isolation Forest
├── LSTM_KFold_Domain_Adaptation.ipynb    # Domain adaptation + K-Fold validation using LSTM
├── lstm.ipynb                            # Pure LSTM-based anomaly detection
├── Modified_Untitled3.ipynb              # Variant of model or experimental notebook
├── unsw_try_1.ipynb                      # IDS model on UNSW-NB15 dataset
├── Untitled3.ipynb                       # Base version or exploratory notebook
└── Updated_Untitled3 (1).ipynb           # Updated version of previous experiments
```

## 🎯 Objective

To build an efficient intrusion detection system that leverages both:
- **Anomaly-based detection** (LSTM, Isolation Forest)
- **Signature-based detection** (known attack patterns)

This hybrid strategy aims to improve detection rates and reduce false positives.

## 🧠 Technologies Used

- **Language**: Python
- **Frameworks**: TensorFlow / Keras, Scikit-learn
- **Tools**: Jupyter Notebooks, Pandas, NumPy, Matplotlib

## 📊 Datasets

- **CICIDS**, **UNSW-NB15** and **NSLKDD** datasets used for training and evaluation.
- Files like `dataset.txt` and `cic_final.ipynb` likely contain dataset handling logic.

## 🚀 How to Run

1. Open any `.ipynb` file in Jupyter Notebook or VS Code with Jupyter extension.
2. Run the notebook cells sequentially.
3. Ensure required libraries are installed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn tensorflow
   ```

## 📈 Key Features

- Preprocessing and feature engineering from raw network data
- Anomaly detection with LSTM (sequence modeling)
- Isolation Forest for unsupervised outlier detection
- Hybrid model for improved performance
- Experimentation with domain adaptation and K-Fold cross-validation

## 📄 License

This project is developed for research and academic use.
#
