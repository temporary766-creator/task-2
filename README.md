# Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Objective
Perform Exploratory Data Analysis (EDA) to understand the Titanic dataset using **statistics and visualizations**.

## 📂 Dataset
- **Source:** Titanic Dataset (Kaggle)
- **Rows:** 891
- **Columns:** 12
- Key columns: `Survived`, `Pclass`, `Sex`, `Age`, `Fare`, `SibSp`, `Parch`, `Embarked`

## 🔍 Steps Performed
1. **Data Overview**
   - Checked shape (891 rows × 12 columns).
   - Identified missing values: `Age` (177 missing), `Cabin` (687 missing), `Embarked` (2 missing).

2. **Summary Statistics**
   - Calculated mean, median, standard deviation, min/max for numeric features.
   - Example: Average Age ~ 30 years, Average Fare ~ 32.2.

3. **Histograms**
   - Age distribution shows many young adults, with skew towards younger passengers.
   - Fare distribution is right-skewed (few very high fares).

4. **Boxplots**
   - Age has outliers at both ends.
   - Fare has significant outliers (very expensive tickets).

5. **Correlation Heatmap**
   - Strong positive correlation: `Pclass` vs `Fare` (-0.55) → Higher class, higher fare.
   - `SibSp` and `Parch` correlated with family size.
   - Survival (`Survived`) is slightly correlated with `Fare` and negatively with `Pclass`.

## 📈 Insights
- **Class & Survival:** Higher-class passengers (Pclass 1) had higher survival chances.
- **Gender:** Females survived at a much higher rate than males.
- **Fare:** Passengers paying higher fares were more likely to survive.
- **Age:** Younger children had relatively better survival chances.

## 🛠 Tools Used
- **Pandas** for data handling  
- **Matplotlib & Seaborn** for visualization  

## 🚀 How to Run
```bash
pip install pandas matplotlib seaborn
