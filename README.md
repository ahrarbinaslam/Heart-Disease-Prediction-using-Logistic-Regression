# 💓 **Heart Disease Prediction Using Logistic Regression** 💻

## 📚 **Introduction**
Cardiovascular diseases are one of the leading causes of death globally. 🌍 According to the World Health Organization, around **12 million deaths** annually are attributed to heart-related ailments. Early detection of heart disease can save lives by enabling lifestyle changes and medical interventions. 🩺

This project uses **logistic regression** to identify key risk factors and predict the **10-year risk of coronary heart disease (CHD)**.

---

## 📊 **Dataset**

### 📥 **Source**
The dataset is sourced from the **[Framingham Heart Study](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset/data)**, an ongoing cardiovascular research project. It includes:
- **4,000+ records**
- **15 attributes** related to patient demographics, behavior, and medical history.

### 🔑 **Variables**
The dataset consists of the following:

#### 🧑‍🤝‍🧑 **Demographic Factors**:
- **Sex**: Male (1) or Female (0).
- **Age**: Age in years (Continuous).

#### 🚬 **Behavioral Factors**:
- **Current Smoker**: Yes (1) or No (0).
- **Cigs Per Day**: Average number of cigarettes smoked daily.

#### 🏥 **Medical History**:
- **BP Meds**: On blood pressure medication (1/0).
- **Prevalent Stroke**: History of stroke (1/0).
- **Prevalent Hypertension**: History of high blood pressure (1/0).
- **Diabetes**: Diagnosed diabetes (1/0).

#### 🔬 **Current Medical Status**:
- **Tot Chol**: Total cholesterol level.
- **Sys BP**: Systolic blood pressure.
- **Dia BP**: Diastolic blood pressure.
- **BMI**: Body mass index.
- **Heart Rate**: Resting heart rate.
- **Glucose**: Blood glucose level.

#### 🎯 **Target Variable**:
- **10-Year CHD Risk**: 1 (Yes) or 0 (No).

---

## ⚙️ **Implementation Steps**

### 🔨 **1. Data Preparation**
- Handle **missing values**.
- Encode **categorical variables** (e.g., Male = 1, Female = 0).

### 🔍 ***2. Data Visualization**
- Visualize key information related to the dataset using **Matplotlib** and **Seaborn**. 

### 🧮 **3. Logistic Regression**
- Use the **scikit-learn** `LogisticRegression` model.
- Split the dataset into **80% training** and **20% testing**.

### 📊 **4. Model Evaluation**
- Evaluate using metrics:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
 
### 📚 Libraries Used:  
1. **Pandas**
2. **Numpy**
3. **Matplotlib**
4. **Seaborn**
5. **Scikit-Learn**
