# Heart-Disease-Prediction-using-SVM
EDA and Modelling to predict likelihood of Heart Disease using SVM (Support Vector Machine) 

# Heart Disease Prediction by using Support Vector Machine

#### Analysis & Modelling done by Gaurav S. Padawe 

### Domain : Healthcare

**Download : https://archive.ics.uci.edu/ml/datasets/Heart+Disease**

### Source :

#### Creators : 

1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D. 
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D. 
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D. 
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D. 

#### Donor : 

David W. Aha (aha '@' ics.uci.edu) (714) 856-8779

#### Data Set Information :

- This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0). 

- The names and social security numbers of the patients were recently removed from the database, replaced with dummy values. 

- One file has been "processed", that one containing the Cleveland database. All four unprocessed files also exist in this directory. 

- To see Test Costs (donated by Peter Turney), please see the folder "Costs"

### Attribute Information :

Only 14 attributes used: 
<b>
1. #3 (age) 
2. #4 (sex) 
3. #9 (cp) 
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
14. #58 (num) (the predicted attribute)</b>

### Complete attribute documentation :<br>

<b>
- age: age in years


- sex: sex (1 = male; 0 = female) 


- cp: chest pain type
    - Value 1: typical angina 
    - Value 2: atypical angina 
    - Value 3: non-anginal pain 
    - Value 4: asymptomatic 


- trestbps: resting blood pressure (in mm Hg on admission to the hospital) 


- chol: serum cholestoral in mg/dl


- fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)


- restecg: resting electrocardiographic results 
    - Value 0: normal 
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) 
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria


- thalach: maximum heart rate achieved


- exang: exercise induced angina (1 = yes; 0 = no) 


- oldpeak = ST depression induced by exercise relative to rest 


- slope: the slope of the peak exercise ST segment 
    - Value 1: upsloping 
    - Value 2: flat 
    - Value 3: downsloping


- ca: number of major vessels (0-3) colored by flourosopy


- num: diagnosis of heart disease (angiographic disease status) 
    - Value 0: < 50% diameter narrowing 
    - Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 are vessels)

### Questionnaire :

- What Age group do we've in our data ?

- If we've missing values, What approach we can take ?

- Since, this is a Classification Problem will we get to see multi-class Imbalance ? If so , what approach we can take ?


### Objective :

- To analyze and make model for Switzerland dataset.
- First I'll do Data processing followed by EDA.
- My aim is to make a statistical model with the help of SVM Classifier which will predict the vulnerability of heart disease for given patient(s) data.
