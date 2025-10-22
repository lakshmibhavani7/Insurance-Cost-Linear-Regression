# Insurance-Cost-Linear-Regression
Predicting medical insurance costs using Linear Regression by analyzing the effect of demographic and lifestyle factors.
# 🏥 Insurance Cost Prediction using Linear Regression  

## 🌟 Project Overview  
This project focuses on predicting **medical insurance charges** based on individual attributes such as age, BMI, smoking status, number of children, and residential region using **Linear Regression**.  
By analyzing patterns in the 'new_insurance_data' dataset, the project aims to uncover how lifestyle and demographic factors impact healthcare costs.  
It provides actionable insights for **insurance companies** to design fair pricing models and for **customers** to understand cost influencers.  

---

## 🎯 Objective  
The main goal of this project is to build a reliable **predictive model** that estimates individual medical insurance costs.  
It also aims to interpret the contribution of each variable — such as **smoking habits, BMI, and age** — to understand what drives higher premiums and overall healthcare costs.  

---

## 🔑 Key Features  
💾 **End-to-End Workflow** – Includes data preprocessing, feature encoding, model training, and performance evaluation.  
📊 **Detailed EDA** – Visualizes relationships between predictors and medical charges through heatmaps, scatter plots, and pairplots.  
🧩 **Feature Engineering** – Encodes categorical variables like `sex`, `region`, and `smoker` for better ML compatibility.  
⚙️ **Model Training** – Implements **Linear Regression** using scikit-learn to capture linear dependencies.  
📈 **Performance Metrics** – Evaluates the model using R², MAE, and MSE to ensure robust predictions.  

---

## 💻 Technical Implementation  
- **Data Source:** `new_insurance_data.csv`  
- **Data Cleaning:** Verified data consistency and checked for missing or extreme values.  
- **EDA:** Used Seaborn and Matplotlib to identify correlations and visualize feature trends.  
- **Feature Encoding:** Applied label encoding for categorical variables.  
- **Model Building:** Built a Linear Regression model using Scikit-learn’s `LinearRegression()` class.  
- **Evaluation:** Compared predicted vs. actual insurance charges using regression metrics.  
- **Interpretation:** Examined coefficients to interpret how each factor affects insurance costs.  

---

## 🧠 Technologies Used  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques:** Linear Regression, Feature Encoding, Data Visualization  
- **Environment:** Jupyter Notebook  

---

## 📊 Dataset  
The `new_insurance_data` dataset includes demographic and lifestyle details affecting insurance charges:  

- `age`: Age of the insured person  
- `sex`: Gender of the individual  
- `bmi`: Body Mass Index (indicator of body fat)  
- `children`: Number of dependents covered  
- `smoker`: Smoking status (yes/no)  
- `region`: Residential area  
- `charges`: Insurance cost (target variable)  

This dataset helps analyze how lifestyle and demographic variables contribute to medical expenses.  

---

## 🔬 Methodology  
🪜 **Step 1:** Load and explore the dataset to understand structure and summary statistics.  
📊 **Step 2:** Conduct EDA to visualize relationships and detect multicollinearity.  
🧩 **Step 3:** Encode categorical features using label encoding.  
⚙️ **Step 4:** Train the Linear Regression model and evaluate with regression metrics.  
📈 **Step 5:** Interpret model coefficients to identify major cost influencers.  

---

## 💡 Key Findings  
💥 **Smoking** emerged as the most significant factor influencing insurance charges.  
📈 **BMI** and **Age** positively correlate with higher medical costs.  
⚖️ **Gender** and **Region** show minimal influence on cost variation.  
📊 The model achieved strong R² performance, showing reliable predictive power.  

---

## 🧾 Top Predictive Features  
✨ Smoking Status  
✨ BMI  
✨ Age  
✨ Number of Children  

These factors collectively explain the majority of insurance charge variations.  

---

## 🧹 Data Quality Insights  
✅ No missing or invalid entries found.  
✅ Proper encoding ensured smooth model compatibility.  
✅ Feature scaling and variable distribution aligned well with regression assumptions.  

---

## 💼 Business Applications  
💡 Helps insurers predict fair premium amounts based on lifestyle and demographic risk factors.  
💡 Enables **data-driven decision-making** for underwriting and pricing.  
💡 Supports **healthcare analytics** by identifying trends in risk contributors.  
💡 Can be integrated into a **pricing recommendation engine** for automated predictions.  

---
## ⚙️ How to Use  
1️⃣ Clone the repository:
      git clone https://github.com/yourusername/Insurance-Cost-Prediction.git
2️⃣ Open the notebook:
      jupyter notebook Linear_Regression_Handson.ipynb
3️⃣ Run all cells sequentially to view results and visualizations.
4️⃣ Modify inputs (e.g., smoker status or BMI) to simulate new predictions.

📂 File Structure

Insurance-Cost-Prediction/
│
├── Linear_Regression_Handson.ipynb     # Complete model and analysis
├── new_insurance_data.csv              # Dataset
├── visuals/                            # Plots & charts (optional)
└── README.md                           # Project documentation

📖 Results Interpretation

📉 The regression line accurately represents relationships between predictors and insurance costs.
💨 Smoking significantly increases the predicted charges, validating domain logic.
📊 Evaluation metrics (R², MAE, MSE) indicate strong model performance and generalization.

🔮 Future Enhancements

🚀 Explore Polynomial Regression for non-linear relationships.
📊 Integrate Power BI or Streamlit dashboards for business visualization.
🤖 Compare results with ensemble models like Random Forest or XGBoost.
🌐 Deploy model using Flask or FastAPI for real-time use.

👨‍💻 Author
Lakshmi Bhavani Reddy 

lakshmibhavani071200@gmail.com | https://www.linkedin.com/in/lakshmibhavanireddy37/


🧩 Conclusion

This project demonstrates how Linear Regression can effectively model and interpret medical insurance charges using demographic and lifestyle factors.

