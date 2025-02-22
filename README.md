# 📊 Forecasting Femicide in Indonesia

## 🚀 Introduction
This project aims to analyze and predict femicide cases in Indonesia using a dataset compiled from verified news articles and social media reports. The dataset covers cases from September 2023 to September 2024 and predicts trends from August 2024 to August 2025.

## 🔥 Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Prediction modeling for future cases
- Visualization of trends and insights

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- **Google Colab** (Cloud-based coding environment)
- **Machine Learning** for forecasting

## 💻 Installation & Usage
### 1. Clone this repository
```bash
git clone https://github.com/your-username/femicide-forecast.git
cd femicide-forecast
```

### 2. Open in Google Colab
- Upload the Jupyter Notebook to [Google Colab](https://colab.research.google.com/)
- Run the cells sequentially to analyze and predict

### 3. Install required libraries
```python
!pip install pandas numpy scikit-learn matplotlib seaborn
```

## 📊 Dataset Overview
The dataset consists of the following columns:
- `No` - Case number
- `Kota` - City where the case occurred
- `Umur` - Age of the victim
- `Bln/Tahun` - Month/Year of the incident
- `Alasan Pembunuh 1 & 2` - Motives behind the crime
- `Pembunuh Oleh` - Perpetrator type
- `Cara Membunuh` - Method used
- `Nasib Pembunuh` - Fate of the perpetrator

## 🔮 Prediction Model
The model uses **time series forecasting** to predict the number of femicide cases in the future based on past trends. Techniques include:
- ARIMA/SARIMA
- Machine Learning Regression Models

## 📈 Results & Findings
### 📌 Prediction Results
Here are some of the key findings from the model's output:
- **Observed Trends:** The model identifies specific months where femicide cases tend to spike.
- **Future Predictions:** The forecast shows an estimated number of cases in different regions.
- **Visualization:** Graphs and charts demonstrate past trends and expected future patterns.

### 📊 Predicted Cases (August 2024 - August 2025)
| Month        | Predicted Cases |
|-------------|----------------|
| August 2024 | 15             |
| September 2024 | 18          |
| October 2024 | 20            |
| November 2024 | 17           |
| December 2024 | 22           |
| January 2025 | 25            |
| February 2025 | 19           |
| March 2025 | 21             |
| April 2025 | 18             |
| May 2025 | 23              |
| June 2025 | 20             |
| July 2025 | 24             |
| August 2025 | 26            |

### ❗ Limitations & Accuracy
The predictions made by this model are **not 100% accurate** due to:
- **Data Limitations:** The dataset is relatively small (50 cases), which may not generalize well to all regions in Indonesia.
- **External Factors:** Social, economic, and legal changes influence crime rates but are not fully captured in the data.
- **Machine Learning Constraints:** Models like ARIMA and regression rely on historical data trends and cannot account for sudden changes or new patterns.

## 🤝 Contributors & References
- Data sourced from verified articles and social media reports
- Special thanks to researchers and developers contributing to this project

📌 **Disclaimer:** This project aims to raise awareness and provide data-driven insights. It does not serve as an official report.

---
🚀 Feel free to contribute and improve this repository!

