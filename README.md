# ⚽ FIFA20 Player Analysis, Clustering & Wage Prediction

This project analyzes the **FIFA20 player dataset** to understand player attributes, identify natural player groups via clustering, and build machine-learning models to predict player wages.  
It includes complete **EDA, preprocessing, feature engineering, clustering, modeling, evaluation, and task-specific insights**.

---

## 📌 Project Goals

- Analyze FIFA20 player attributes and trends  
- Clean & preprocess complex football-related data  
- Perform **K-Means clustering** to group similar player archetypes  
- Visualize clusters using **PCA (2D)**  
- Train ML models to **predict player wages**  
- Answer task-based questions such as:  
  - Top 10 countries by player count  
  - Comparison of defending vs attacking stats  
  - Which offensive role (ST, RW, LW) earns the highest wages  
- Compare model performances and give recommendations  

---

## 📁 Repository Structure
├── data/
│ └── fifa20.csv # (Optional — if dataset is small enough)
├── notebooks/
│ └── Fifa 20 Code.ipynb
└── README.md


---

## 🔍 Exploratory Data Analysis (EDA)

The notebook includes:

- Player demographic analysis (age, nationality, position)  
- Value, wage, and club distribution  
- Skill attribute trends (passing, shooting, pace, dribbling, etc.)  
- Correlation heatmaps  
- Outlier detection and cleaning  

---

## 🛠 Preprocessing & Feature Engineering

- Cleaning monetary columns (`Value`, `Wage`, etc.)  
- Handling missing values using median imputation  
- Removing inconsistent features  
- One-Hot encoding categorical fields  
- Creating numeric skill matrices for clustering  
- Dropping biased features (e.g., `Overall`)  
- Generated additional derived features where helpful  

---

## 🤖 Clustering (K-Means)

Tasks include:

- Scaling skill attributes  
- Running K-Means to group players  
- Understanding player archetypes  
- Visualizing clusters using **PCA (2D)**  
- Interpreting cluster characteristics  

---

## 🧠 Regression Modeling

Models trained to predict **player wages**:

- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Decision Tree Regressor  
- Other baseline models

### **Evaluation Metrics**
- R² Score  
- RMSE  
- MAE  

A final model comparison summary is included.

---

## 📈 Key Insights

- Offensive roles such as **ST/RW/LW** tend to earn more  
- Top countries produce the majority of highly-rated players  
- Player wages correlate strongly with technical skills & club reputation  
- Clustering reveals meaningful player groups (Playmakers, Defenders, Attackers, etc.)  
- Tree-based models outperform linear models in wage prediction  

---







