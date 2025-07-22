# 🔋 Short-Term Energy Forecasting using Deep Learning Models

This project focuses on forecasting short-term residential energy consumption using advanced deep learning and machine learning models. It was developed as part of a Master's thesis on **"User-Centric Load Forecasting in Smart Homes"** at the University of Freiburg.

---

## 📌 Objective

To design and implement a forecasting pipeline capable of predicting short-term residential energy loads with high accuracy using smart meter data and provide explainable insights aligned with EU AI regulations.

---

## 📂 Project Structure

```
├── Masters_final_code_DNN.ipynb         # Main notebook for model training and evaluation
├── dashboard.py                         # Script for building a monitoring dashboard
├── Results/                             # Contains model predictions, graphs, and evaluation reports
├── Peak_shaving.ipynb                   # Peak shaving application notebook
├── Regressor_Final.ipynb                # Surrogate modelling for Post-hoc explainations (XAI)
├── ...
```

---

## 🧠 Models Used

- **Deep Learning**
  - LSTM (Long Short-Term Memory)
  - TCN (Temporal Convolutional Networks)
  - N-BEATSx
  - TS-Mixerx
  - KAN (Kernel Attention Network)

- **Machine Learning**
  - XGBoost
  - LightGBM
  - Random Forest
  - Desicion Trees
  - ElasticNet

---

## ⚙️ Key Features

- Implements a deep learning-based forecasting pipeline.
- Time series data preprocessing and feature selection using Nixtla.
- Hyperparameter tuning with **Optuna**.
- Implements **sliding window** forecasting strategy.
- Visualizes performance with actual vs predicted plots.
- Provides explainable outputs using surrogate models.
- Includes simulation of **battery models** for energy cost evaluation and transalting the model acciuracy in terms of actual savings.

---

## 📊 Results Snapshot

- Models tested: 9 (DL and ML)
- Highest performance model: **TSMixersx**
- RMSE and MAE metrics computed for comparison
- Visualizations: line plots, dashboard modules, CSV outputs

---

## 💾 Requirements

Install required packages with:

```bash
pip install -r requirements.txt
```

(You can generate `requirements.txt` using `pip freeze > requirements.txt`)

---

## 📍 Location of Results

Final predictions are saved in:

```
Results/Optimization/TSMixerx/
Results/DNN/TEST/KAN/...
```

---

## 📈 Visualization

The repo includes plots comparing **actual vs predicted values**, example:

![KAN Prediction](./Results/DNN/TEST/KAN/KAN_final_predictions.png)

---

## 🧠 Explainability

Surrogate models like XGBoost and LightGBM are integrated for interpreting deep learning predictions as per **EU AI Act (2024/1689)**.

---

## 🏁 How to Run

1. Clone the repo  
2. Open `Masters_final_code_DNN.ipynb` in Jupyter or VSCode  
3. Set file paths accordingly  
4. Run all cells  

---

## 📚 Citation

If you use this code, please cite:

> Ashutosh Gadhade, "User-Centric Load Forecasting with Deep Learning", MSc Thesis, University of Freiburg, 2025.

---

## 📧 Contact

Ashutosh Gadhade  
📬 ashgadhade@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/ashutoshgadhade)
