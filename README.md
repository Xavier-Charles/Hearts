# Hearts 
This is based on the project of the python intermediate class of the Covens AI and data science boot camp cohort7. 
We are training a Deep Neural network to diagnose a heart disease.
This is still work in progress, however, we call for your comments and pull requests.

## Data Set Information:

This Cleveland database contains 14 attributes. The goal is to indicate the presence of heart disease in the patient.
It is integer valued from 0 (no presence) OR 1(presence).
Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).

Source: 
1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D. 
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D. 
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D. 
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D

## Attribute Information:

Only 14 attributes used: 
1.  age 
2.  sex 
3.  (cp)   chest pain type 

| Values   |    cp Type       |
| -------- |:----------------:| 
| 1        | typical angina   |
| 2        | atypical angina  |
| 3        | non-anginal pain |
| 4        | asymptomatic     |
 
4. (trestbps)   resting blood pressure (in mm Hg on admission to the hospital) 
5. (chol)   serum cholestoral in mg/dl 
6. (fbs)   (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) 
7. (restecg)   resting electrocardiographic results 

| Values   |    restecg Type                                                                                   |
| -------- |:-------------------------------------------------------------------------------------------------:| 
| 1        | normal                                                                                            |
| 2        | having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)   |
| 3        | showing probable or definite left ventricular hypertrophy by Estes' criteria                      |

8. (thalach)   maximum heart rate achieved 
9. (exang)    exercise induced angina (1 = yes; 0 = no) 
10. (oldpeak)   ST depression induced by exercise relative to rest 
11. (slope)   the slope of the peak exercise ST segment

| Values   |    slope Type    |
| -------- |:----------------:| 
| 1        | upsloping        |
| 2        | flat             |
| 3        | downsloping      |

 
  
12. (ca)   number of major vessels (0-3) colored by flourosopy 
13. (thal)   3 = normal; 6 = fixed defect; 7 = reversable defect 
14. (ahd)   (the predicted attribute)  diagnosis of heart disease (angiographic disease status) 

| Values   |    AHD Type                                                                          |
| -------- |:------------------------------------------------------------------------------------:| 
| 0        | 50% diameter narrowing                                                               |
| 1        | 50% diameter narrowing  (in any major vessel: attributes 59 through 68 are vessels)  |

