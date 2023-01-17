# Heart Disease Prediction
Heart Disease Prediction using LogisticRegression(Binary Classification)

## Logistic Regression
Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.In Logistic regression, instead of fitting a regression line, we fit an "S" shaped logistic function, which predicts two maximum values (0 or 1).
The curve from the logistic function indicates the likelihood of something such as whether the cells are cancerous or not, a mouse is obese or not based on its weight, etc.

For this project, a traget value of 1 will indicate that the patient is sufferring from a heart disease and a 0 will indicate a healthy heart.

## Input tuple 

The input tuple will have the following:

There are 13 attributes

1.age: age in years

2.sex: sex (1 = male; 0 = female)

3.cp: chest pain type

-- Value 0: typical angina

-- Value 1: atypical angina

-- Value 2: non-anginal pain

-- Value 3: asymptomatic

4.trestbps: resting blood pressure (in mm Hg on admission to the hospital)

5.chol: serum cholestoral in mg/dl

6.fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

7.restecg: resting electrocardiographic results

-- Value 0: normal

-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)

-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

8.thalach: maximum heart rate achieved

9.exang: exercise induced angina (1 = yes; 0 = no)

10.oldpeak = ST depression induced by exercise relative to rest

11.slope: the slope of the peak exercise ST segment

-- Value 0: upsloping

-- Value 1: flat

-- Value 2: downsloping

12.ca: number of major vessels (0-3) colored by flourosopy

13.thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

and the label

## To be Predicted
target:

-- 0 = no disease

-- 1 = disease
