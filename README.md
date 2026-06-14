# Hospital Patient Readmission Analysis 🏥

## Project Overview
Is project ka main goal ye predict karna hai ki kya ek patient hospital se discharge hone ke baad 30 dino ke andar wapas admit (readmit) hoga ya nahi. Yeh healthcare providers ko high-risk patients identify karne aur hospital cost kam karne mein madad karta hai.

## Dataset Details
- **Source:** Kaggle (10,000+ Patient Records)
- **Features:** Patient age, gender, admission type, time in hospital, number of lab procedures, medications, aur diagnosis details.
- **Target Variable:** `readmitted` (Yes/No or <30 days)

## Key Technical Steps
1. **Data Cleaning:** Missing values handle kiye (jaise weight, medical_specialty).
2. **Feature Engineering:** Admission aur discharge IDs ko categorize kiya aur age groups ko numerical mein badla.
3. **Exploratory Data Analysis (EDA):** Readmission rates aur comorbidities ke beech correlation find kiya.
4. **Model Building:** Logistic Regression, Random Forest, aur KNN algorithms ka use kiya.
5. **Evaluation:** Accuracy, Precision, Recall, aur F1-Score ke basis par model compare kiya.

## Results
- Best Model: **Random Forest** (ya jo bhi aapka best raha ho)
- Accuracy: **~XX%**
- Key Insight: Patients jo 7 dino se zyada hospital mein rahe unka readmission rate 20% zyada tha.

## How to Run
```bash
python src/hospital_analysis.py
```
