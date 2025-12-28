# Greencell_Assignment


# 📊 Voltage Trend Analysis

This project focuses on analyzing and visualizing voltage data over time using Python and Jupyter Notebook.  
The analysis includes data preprocessing, trend identification using moving averages, and detection of peaks and lows.

---

## 📁 Project Files

- **greencell.ipynb**  
  Jupyter Notebook containing the complete analysis, including data loading, preprocessing, visualization, moving averages, and peak detection.

- **sample_data.csv**  
  Sample dataset used for voltage trend analysis.

---

## 📊 Dataset Description

The dataset consists of two columns:

- **Timestamp** – Records the exact time of each voltage measurement.  
- **Values** – Represents the voltage readings.

A large number of observations are recorded over time, making the dataset suitable for time-series analysis.

---

## 🔧 Data Processing and Analysis

The following steps were performed in the notebook:

- Verified data loading using `df.head()`, `df.shape()`, and `df.info()`
- Converted timestamp values from object type to datetime format
- Converted voltage values to numeric format
- Calculated moving averages with window sizes **1000** and **5000**
- Identified local peaks and lows using `scipy.signal.find_peaks`
- Visualized voltage trends with clear axis labels and legends

---

## 📈 Visualization

- Voltage values plotted against time
- Moving Average (1000) highlights medium-term trends
- Moving Average (5000) highlights long-term trends
- X-axis timestamps optimized for readability

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- SciPy  
- Jupyter Notebook  

---

## ▶️ How to Run the Notebook

### Install required libraries:
```bash
pip install pandas numpy matplotlib scipy
```

### Open the notebook:
```bash
jupyter notebook greencell.ipynb
```

### Run all cells to reproduce the analysis.

---

## 📌 Conclusion

This project demonstrates effective time-series analysis of voltage data using Python, highlighting trends, stability, and fluctuations through visualization and statistical techniques.
