# 🌾 Crop Yield Analysis & Forecasting using Machine Learning

A data-driven project developed during a research internship at **IDEAS – Institute of Data Engineering, Analytics and Science Foundation, ISI Kolkata**, focused on analyzing and forecasting agricultural crop yields across Indian states using Machine Learning and Deep Learning models.

## 📌 Summary

This project aims to enhance crop yield forecasting using historical agricultural and climatic data such as:
- Temperature (min/max)
- Rainfall
- Water reservoir levels
  

We implemented DL models, including **Artificial Neural Networks (ANN)** and **Long Short-Term Memory (LSTM)** networks, to predict crop yields for **Gram, Rice, Wheat, Potato, Massor**, and **Mustard** across different Indian states.

## 👨‍💻 Authors

- **Navneet Kumar Singh**, B.Tech IT – GCECT Kolkata  
- **Saksham Asopa**, B.Tech IT – GCECT Kolkata  
- **Project Guide:** Ankit Lodh  
- **Internship Duration:** May 19, 2025 – July 15, 2025

## ⚙️ Methodology

- **Data Collection:** Crop-wise yield, weather, and water data from Indian states.
- **Preprocessing:** Feature engineering, encoding, normalization.
- **EDA:** Correlation analysis, trend plots, rainfall/yield dependencies.
- **Modeling:**  
  - ANN (best performing model)  
  - LSTM (weaker generalization)
- **Evaluation:** RMSE & R² Score for model accuracy comparison.

## 📈 Highlights

- ANN generalized well across crops, yielding **low RMSE** and **high R² scores**.
- LSTM underperformed due to weak handling of non-sequential features like water levels.
- Crop yield dependencies varied:  
  - Some crops were **climate-sensitive** (e.g., rainfall, temp)  
  - Others relied more on **regional practices**.

### 🔢 Sample Results

| Crop   | Best R² Score | Best State       | Lowest RMSE |
|--------|---------------|------------------|-------------|
| Gram   | 0.550         | Andhra Pradesh   | 0.116       |
| Rice   | 0.680         | Karnataka        | 0.095       |
| Wheat  | 0.608         | Gujarat          | 0.195       |
| Potato | 0.582         | Telangana        | 0.662       |
| Massor | 0.391         | Uttar Pradesh    | 0.104       |
| Mustard| 0.605         | Gujarat          | 0.100       |

## 🧠 Key Takeaways

- ANN outperformed LSTM across crops and regions.
- Region-specific dependencies are crucial for accurate forecasting.
- Yield predictions can assist:
  - **Farmers** in resource allocation & crop selection  
  - **Governments** in policy and subsidy planning

## 🔗 Resources

- 📄 [Project Report (PDF)](https://github.com/Navneetsingh9/ISI-CROP-YIELD-ANALYSIS-AND-FORECASTING/blob/main/ISI-PROJECT%20REPORT.pdf)  
- 💻 [Google Colab Notebook](https://colab.research.google.com/drive/1QEqBkW4et6ODkaC9qijdMDDusuVoye2A?usp=sharing)  
- 📚 [Related Research 1](https://doi.org/10.1007/s40003-019-00413-x)  
- 📚 [Related Research 2](https://doi.org/10.35940/ijitee.j7491.0891020)

