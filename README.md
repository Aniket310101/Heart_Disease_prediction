# Heart_Disease_prediction
**Goal:**<br/>
Markup:-Predict whether a patient should be diagnosed with Heart Disease. This is a binary outcome.<br/>
-Positive (+) = 1, patient diagnosed with Heart Disease<br/>
-Negative (-) = 0, patient not diagnosed with Heart Disease<br/>
-Experiment with various Classification Models & see which yields greatest accuracy.<br/>
-Examine trends & correlations within our data<br/>
-Determine which features are most important to Positive/Negative Heart Disease diagnosis<br/><br/>
**Features & Predictor:**<br/>
Our Predictor (Y, Positive or Negative diagnosis of Heart Disease) is determined by 13 features (X):<br/>
1. age (#)
2. sex : 1= Male, 0= Female (Binary)
3. (cp)chest pain type (4 values -Ordinal):Value 1: typical angina ,Value 2: atypical angina, Value 3: non-anginal pain , Value 4: asymptomatic
4. (trestbps) resting blood pressure (#)
5. (chol) serum cholesterol in mg/dl (#)
6. (fbs)fasting blood sugar > 120 mg/dl(Binary)(1 = true; 0 = false)
7. (restecg) resting electrocardiography results(values 0,1,2)
8. (thalach) maximum heart rate achieved (#)
9. (exang) exercise induced angina (binary) (1 = yes; 0 = no)
10. (oldpeak) = ST depression induced by exercise relative to rest (#)
11. (slope) of the peak exercise ST segment (Ordinal) (Value 1: up sloping , Value 2: flat , Value 3: down sloping )
12. (ca) number of major vessels (0–3, Ordinal) colored by fluoroscopy
13. (thal) maximum heart rate achieved — (Ordinal): 3 = normal; 6 = fixed defect; 7 = reversible defect<br/><br/>
**Note:** Our data has 3 types of data:<br/>
Continuous (#): which is quantitative data that can be measured<br/>
Ordinal Data: Categorical data that has a order to it (0,1,2,3, etc)<br/>
Binary Data: data whose unit can take on only two possible states ( 0 &1 )<br/>
