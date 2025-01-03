# 🌫️ Air Quality Time Series Forecasting using RNN 🌟

## 🚀 Overview
This project focuses on building a single-variable time series forecasting model using the Air Quality dataset. The primary goal is to predict the concentration of **CO(GT)** over time using a Recurrent Neural Network (RNN).  

## 📊 Dataset
The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/360/air+quality).  
- **📂 Features**: 15 features including air quality metrics (e.g., CO(GT), PT08.21(CO), NHMC(GT)) and date/time columns.  
- **🧮 Entries**: 9471 rows of air quality data.  
- **🎯 Target Variable**: CO(GT).  

---

## 🏗️ RNN Architecture
The RNN model is designed to capture temporal dependencies in the time series data.  
### ⚙️ Architecture Details  
- **🧱 Layers**:  
  - 3 RNN layers with ReLU activation.  
  - 1 Dense layer.  

- **🛠️ Optimizer**:  
  - Adam optimizer with a learning rate of 0.001.  

- **📉 Loss Function**:  
  - Mean Squared Error (MSE).  

- **🔧 Hyperparameters**:  
  - Batch size: 32.  
  - Epochs: 10.  
---

## 📈 Model Evaluation
The model was evaluated using the following metrics:  
- **🔢 R-Squared (R²)**: Achieved a score of **76%**.  
- **🧮 Mean Absolute Error (MAE)**: Low training and validation losses of **~0.0035**.
---

## 🏆 Results
| 🏷️ Metric            | 🔢 Value       |
|-----------------------|---------------|
| **📊 R-Squared (R²)** | **76%**       |
| **📉 Training Loss**  | **0.0035**    |
| **📉 Validation Loss**| **0.0035**    |
---

### Technologies
- 🐍 Python
- 🧮 TensorFlow  
- 🛠️ NumPy  
- 📊 Pandas  
- 📈 scikit-learn  

### 📊 Plots
## 🔥Correlation Heatmap
![output](https://github.com/user-attachments/assets/a153bede-7a57-4975-8709-fd88b26fac2f)

## ⏳CO(GT) Values over time
![output](https://github.com/user-attachments/assets/bb38c1ad-5fbf-475e-9c09-98ca5743c197)

## 📈Prediction and Model Loss
![output](https://github.com/user-attachments/assets/65c51686-0ace-4675-b714-93eb2d1d3c16)
