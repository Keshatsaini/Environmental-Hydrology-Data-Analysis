# 🌾 AI-Enabled Water Resource & Crop Selection Framework  
### Climate-Adaptive Farming Using Machine Learning & Environmental Data

---

## 📌 1. Problem Overview  
Agriculture in India depends heavily on rainfall, groundwater levels, and soil quality. Farmers often select crops based on guesswork or outdated recommendations, leading to:

- ❌ Poor yield and crop failure  
- ❌ High water wastage  
- ❌ Low profitability  
- ❌ No unified AI-based decision system  

🔍 **Goal:** Build an AI-driven system that recommends water-smart crops based on environmental conditions and market demand.

---

## 🎯 2. Project Objective  
To integrate multi-source environmental and market datasets and use machine learning to **recommend the top 3 most suitable crops** for a region based on:

- Rainfall  
- Groundwater depth  
- Soil characteristics  
- Market demand  

✅ Outputs actionable insights for farmers  
✅ Helps optimize water usage & improve yield  

---

## 📝 3. Abstract  
This project presents a **Climate-Adaptive Crop Recommendation Model** using machine learning and data analytics.  
It integrates:

| Dataset | Description |
|---------|-------------|
| 🌧️ Rainfall | Annual average rainfall per district |
| 💧 Groundwater | Depth & availability levels |
| 🌱 Soil | Texture, quality, fertility data |
| 📈 Market | MANDI demand & crop price trends |

A **Random Forest classifier (~85% accuracy)** predicts the top 3 recommended crops for a region.  
The framework includes:  

✔️ Water Feasibility Score  
✔️ Multi-model evaluation (RF, LR, DT, NN, LightGBM, XGBoost, CatBoost)  
✔️ Gradio web app for user interaction  
✔️ Feature importance & visual analytics  

---

## ✨ 4. Key Features  

| Feature | Description |
|---------|-------------|
| 🔗 Data Integration | Merges rainfall, groundwater, soil & market data |
| 💦 Water Feasibility Scoring | Computes crop suitability based on rainfall + groundwater |
| 🌾 Top Crop Prediction | ML predicts top 3 crops with high accuracy |
| 🧠 Multi-Model Comparison | RF, Logistic Regression, NN, LightGBM, XGBoost, CatBoost etc. |
| 🖥️ Interactive UI | Gradio app for user input & recommendations |
| 📊 Visual Analytics | Heatmaps, pair plots, ROC curves, feature importance |
| 💡 Actionable Insights | Helps improve yield & reduce water consumption |

---

## 🛠️ 5. Tech Stack  

| Category | Tools / Libraries |
|----------|-------------------|
| Language | Python |
| ML & Data | Pandas, NumPy, Scikit-learn, XGBoost, CatBoost, LightGBM |
| Visualization | Matplotlib, Seaborn |
| Deployment / UI | Gradio |
| Dataset Format | CSV, Excel |

---

## 📂 6. Project Structure  
