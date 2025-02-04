If you are looking to explore a dataset in the healthcare industry, this is a great beginner-level dataset to start with. This dataset is used to predict the 10-year risk of CHD (Coronary Heart Disease). The dependent variables in this dataset are the risk factors of heart disease, including diabetes, smoking, high blood pressure, and high cholesterol levels.

The independent variable is the 10-year risk of CHD. It is a binary classification problem, and the target variable is either 0 or 1–0 for the patients who never developed heart disease and 1 for the patients who did. You can perform some feature selection on this dataset to identify features that most contribute towards heart risk. Then, you can fit a classification model onto the independent variables.

This dataset is highly imbalanced because many of the patients in this dataset did not develop heart disease. An imbalanced dataset needs to be handled using the right feature engineering techniques like oversampling, weight-tuning, or undersampling. If not dealt with properly, you will end up with a model that simply predicts the majority class for each data point and cannot identify patients who did develop heart disease. This is an excellent dataset for you to practice your feature engineering and machine learning skills.

Dataset: (Kaggle Heart Disease Dataset)[https://archive.ics.uci.edu/dataset/45/heart+disease]

## About the Dataset
Only 14 attributes used:

      1. #3  (age)       

      2. #4  (sex)       

      3. #9  (cp)        

      4. #10 (trestbps)  

      5. #12 (chol)      

      6. #16 (fbs)       

      7. #19 (restecg)   

      8. #32 (thalach)   

      9. #38 (exang)     

      10. #40 (oldpeak)   

      11. #41 (slope)     

      12. #44 (ca)        

      13. #51 (thal)      

      14. #58 (num)       (the predicted attribute)



Complete attribute documentation:

      1 id: patient identification number

      2 ccf: social security number (I replaced this with a dummy value of 0)

      3 age: age in years

      4 sex: sex (1 = male; 0 = female)

      5 painloc: chest pain location (1 = substernal; 0 = otherwise)

      6 painexer (1 = provoked by exertion; 0 = otherwise)

      7 relrest (1 = relieved after rest; 0 = otherwise)

      8 pncaden (sum of 5, 6, and 7)

      9 cp: chest pain type

        -- Value 1: typical angina

        -- Value 2: atypical angina

        -- Value 3: non-anginal pain

        -- Value 4: asymptomatic

     10 trestbps: resting blood pressure (in mm Hg on admission to the hospital)

     11 htn

     12 chol: serum cholestoral in mg/dl


References:
Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989). Heart Disease [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X.