# Exploratory-Data-Analysis-EDA-

## 📌 Task Overview
**Task 5**: Exploratory Data Analysis (EDA)  
**Objective**: Extract meaningful insights from the Titanic dataset using statistical and visual analysis.

---

## 🛠️ Tools Used
- **Python Libraries**:
  - `Pandas` – for data manipulation
  - `Matplotlib` & `Seaborn` – for data visualization

---

## 📂 Dataset
- **Source**: Titanic dataset (`train.csv`)
- **Features**: Includes details such as `Survived`, `Pclass`, `Sex`, `Age`, `Fare`, `SibSp`, `Parch`, etc.

---

## 🔍 Approach

### 1. Data Loading & Inspection
- Loaded the dataset using Pandas.
- Used `.info()`, `.describe()`, and `.value_counts()` to understand the structure and summary statistics.

### 2. Univariate Analysis
- Plotted histograms and countplots for:
  - Age
  - Survival
  - Passenger Class
  - Gender

### 3. Bivariate Analysis
- Used boxplots and countplots to analyze relationships between:
  - Survival & Gender
  - Age & Survival
  - Fare & Class
  - Class & Survival
  - Fare & Survival

### 4. Multivariate Analysis
- Created:
  - **Pairplot** to analyze interactions between `Pclass`, `Age`, `Fare`, and `Survived`.
  - **Correlation Heatmap** to observe numerical relationships between features.

---

## 📊 Summary of Findings

### 🔹 Univariate Analysis
- Age distribution is right-skewed, with more young and mid-aged passengers.
- The number of non-survivors is greater than survivors.
- Most passengers belonged to the 3rd class.
- There were significantly more male passengers than female passengers.

### 🔹 Bivariate Analysis
- Females had a much higher survival rate than males.
- Survivors and non-survivors had similar median ages, but non-survivors had more older outliers.
- Passengers in higher classes paid higher fares.
- 1st-class passengers had the highest survival rate, while 3rd class had the lowest.
- Survivors generally paid higher fares than non-survivors.

### 🔹 Multivariate Analysis
- **Pairplot**: Survivors were more often in higher classes and paid more. No clear relationship between Age and Fare.
- **Correlation Heatmap**: Survival correlates positively with Fare and negatively with Pclass. SibSp and Parch are moderately correlated.

---

## ✅ Outcome
This EDA helped uncover patterns and trends in the Titanic dataset, especially how **class, gender, and fare** influenced **survival**. These insights can be used to inform predictive models or deeper analysis.

