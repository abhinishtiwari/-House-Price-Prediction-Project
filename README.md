# 🏡 House Price Prediction Project



Welcome to the **House Price Prediction** project repository! This project implements **end-to-end machine learning** to predict house prices based on features like median income, house age, and more. 📈

---

## ✨ Project Overview
Leverages the **California Housing dataset** for building a regression model to predict median house prices. Key highlights:

- Data preprocessing and feature selection.
- Exploratory Data Analysis (EDA) with visualizations.
- Linear regression modeling and evaluation.
- Model saving for future predictions.

---

## 📊 Features Used
Dataset features include:

- **💸 MedInc**: Median income in the block.
- **🏡 HouseAge**: Age of the house.
- **🔾 AveRooms**: Average number of rooms.
- **🏟 AveBedrms**: Average number of bedrooms.
- **📊 Population**: Block population.
- **🔬 AveOccup**: Average household size.
- **🌍 Latitude**: Geographical latitude.
- **🌎 Longitude**: Geographical longitude.

---

## 🔁 Workflow
1. **🔧 Problem Definition**: Predict median house prices.
2. **🔼 Data Preprocessing**: 
   - Handle missing values, scale features, detect multicollinearity.
3. **🔬 EDA**: Correlation heatmap, scatter plots.
4. **⚖️ Feature Selection**: Retain `MedInc`, `HouseAge`, `Population`, `AveOccup`.
5. **📊 Model Training**: Train-test split (80/20) with Linear Regression.
6. **📊 Model Evaluation**:
   - **MAE**: 0.683, **MSE**: 0.844, **RMSE**: 0.919, **R²**: 37.6%.
7. **🔒 Deployment**: Save models via `pickle`/`joblib`.

---

## 🔄 Installation and Setup
**Prerequisites**: Python 3.8+, Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`, `pickle`.

**Steps**:
1. Clone repo: `git clone https://github.com/your_username/house-price-prediction.git`
2. Navigate: `cd house-price-prediction`
3. Install dependencies: `pip install -r requirements.txt`
4. Run script: `python main.py`

---

## 🌐 Project Structure
```
.
|-- data/                # Dataset
|-- models/              # Saved models
|-- notebooks/           # Prototyping notebooks
|-- src/                 # Model training scripts
|-- README.md            # Documentation
|-- requirements.txt     # Dependencies
```

---

## 🎨 Visualizations
### 1. **Correlation Heatmap**
![Correlation Heatmap](https://github.com/abhinishtiwari/-House-Price-Prediction-Project/blob/616fbf018fa008be15bc218898c7b5ef5c3a2679/Image/Varsualize%20the%20Correlation%20matrix.png)


### 2. **Q-Q Plot of Residuals**
![Q-Q Plot of Residuals](https://github.com/abhinishtiwari/-House-Price-Prediction-Project/blob/616fbf018fa008be15bc218898c7b5ef5c3a2679/Image/Q-Q%20Plot.png)


### 3. **Residuals vs. Predicted Values Plot**
![Residuals vs. Predicted Values Plot](https://github.com/abhinishtiwari/-House-Price-Prediction-Project/blob/616fbf018fa008be15bc218898c7b5ef5c3a2679/Image/Residuals%20vs.%20Predicted%20values.png)

---

## 🛠️ Contributing
Contributions are welcome! Fork the repository, create a new branch, and submit a pull request.

---

## 📢 Contact
- **Name**: Abhinish Tiwari  
- **Email**: [abhinishtiwari02@gmail.com](abhinishtiwari02@gmail.com)  
- **GitHub**: [Abhinish Tiwari](https://github.com/abhinishtiwari)
