# Urban Bliss Index – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the **Urban Bliss Index dataset**, which captures city-level indicators related to **happiness, healthcare, environmental quality, cost of living, traffic density, and noise levels**.
The objective is to understand the structure, quality, and relationships within the data before proceeding to advanced analysis or modeling.

---

## 📥 Dataset Source
The dataset used in this project is publicly available on Kaggle:

🔗 https://www.kaggle.com/datasets/willianoliveiragibin/2024-urban-bliss-index

---

## 📊 Dataset Description
The dataset contains information about multiple cities across different time periods and includes both **numerical and categorical variables**.

### Key Features:
- **City** – Name of the city  
- **Month, Year** – Temporal indicators  
- **Happiness_Score** – Target variable representing overall well-being  
- **Healthcare_Index** – Quality of healthcare infrastructure  
- **Cost_of_Living_Index** – Relative living cost  
- **Air_Quality_Index** – Air pollution indicator  
- **Green_Space_Area** – Availability of green spaces  
- **Decibel_Level** – Noise pollution level  
- **Traffic_Density** – Categorical traffic congestion level  

---

## 🧩 Project Structure
```
├── 2024 Urban Bliss Index.ipynb   # Final Jupyter Notebook
├── README.md                     # Project documentation
└── data/                         # Dataset files (if applicable)
```

---

## 🔍 Phase 1: Data Understanding & Initial Assessment
- Loaded and inspected the dataset using `pandas`
- Reviewed dataset shape, structure, and data types
- Analyzed summary statistics for numerical columns
- Checked for missing values and duplicates
- Examined categorical distributions using `value_counts()`

**Outcome:**  
The dataset was found to be clean, well-structured, and suitable for further analysis.

---

## 🧹 Phase 2: Data Cleaning & Manipulation
- Verified absence of missing values and duplicates
- Standardized categorical fields to prevent inconsistencies
- Converted appropriate columns to categorical data types
- Ensured correct numerical and temporal data handling
- Performed **non-visual bivariate analysis** to understand relationships without plots

**Outcome:**  
The dataset is consistent, standardized, and analysis-ready.

---

## 📈 Exploratory Data Analysis (EDA)

### Univariate Analysis
- Distribution analysis of key numerical variables
- Frequency analysis of categorical variables
- Identification of skewness, spread, and dominant categories

### Bivariate Analysis
- **Numerical vs Numerical:** Scatter plots with trend lines
- **Categorical vs Numerical:** Box plots and bar charts (Top 20 cities)
- **Categorical vs Categorical:** Count plots for temporal and traffic patterns

Visualizations were designed to ensure clarity, interpretability, and reproducibility.

---

## 🏙️ Key Insights
- Cities with strong **healthcare infrastructure** and balanced **environmental conditions** tend to report higher happiness scores.
- **Traffic density and environmental indicators** show measurable influence on urban well-being.
- Top-performing cities maintain consistently high happiness scores with relatively small variation.
- High cost of living does not necessarily correspond to higher happiness levels.

---

## ✅ Final Conclusion
The Urban Bliss Index dataset has been thoroughly explored and cleaned.
All variables were analyzed using appropriate statistical and visualization techniques.
The dataset is now **fully prepared for Phase 3**, including predictive modeling or advanced analytical tasks.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 👤 Author
M Muddu Krishna

---

## 📄 License
This project is intended for educational and academic purposes only.

