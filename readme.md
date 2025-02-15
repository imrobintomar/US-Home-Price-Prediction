## 🏡 U.S. Home Price Prediction 2025 

### 📌 Project Overview  
This project aims to develop a **machine learning model** to predict home prices in the United States using various real estate features. The model leverages **data analysis, feature engineering, and regression algorithms** to provide accurate price estimates.

### 📂 Repository Structure  
```
📁 US_Home_Price_Prediction  
 ├── 📜 US_Home_Price_Prediction.ipynb  # Jupyter Notebook with the full analysis  
 ├── 📄 README.md  # Project documentation  
 ├── 📂 data/  # (Optional) Folder for datasets  
 
 
```

### 🚀 Features  
- **Exploratory Data Analysis (EDA):** Understanding patterns, distributions, and correlations.  
- **Feature Engineering:** Selection, encoding, and transformations for optimal model performance.  
- **Machine Learning Models:**  
  - **Linear Regression (LR)** (Baseline model)  
  - **Random Forest Regressor (Best performing model)**  
- **Model Evaluation:** Performance metrics (R² Score) for accuracy assessment.  
- **Visualization:** Graphical insights into price trends and influencing factors.  

### 🔧 Installation & Setup  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/US_Home_Price_Prediction.git
   cd US_Home_Price_Prediction
   ```
2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Jupyter Notebook**  
   ```bash
   jupyter notebook US_Home_Price_Prediction.ipynb
   ```

### 🏆 Model Performance  
| Model  | Best R² Score | Average R² Score |  
|--------|-------------|-------------|  
| Linear Regression | **0.305** | Low performance due to non-linearity |  
| Random Forest Regressor | **0.9586** | ~0.522 (Baseline run) |  

- **Linear Regression** showed poor results due to the non-linear relationship in the dataset.  
- **Random Forest Regressor** significantly improved performance, achieving a **best R² score of 0.9586**.  

### 📊 Data Sources  
- [Data Source 1](https://fred.stlouisfed.org)  
 

### 📜 License  
This project is **open-source** under the [MIT License](LICENSE).  

