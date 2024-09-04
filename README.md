# Heart_Attack_Analysis_Prediction
About this dataset:

age : Age of the patient

Sex : Sex of the patient

cp : Chest Pain type chest pain type: Value 0: typical angina, Value 1: atypical angina, Value 2: non-anginal pain, Value 3: asymptomatic

trtbps : resting blood pressure (in mm Hg)

chol : cholestoral in mg/dl fetched via BMI sensor

fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

restecg : resting electrocardiographic results: Value 0: normal, Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria.

thalachh : maximum heart rate achieved

exng: exercise induced angina (1 = yes; 0 = no)

oldpeak: ST depression induced by exercise relative to rest (S-T segment, segment on the ECG that lies between the end of the S wave and the start of the T wave).

slp: the slope of the peak exercise ST segment, 0 = unsloping, 1 = flat, 2 = downsloping.

caa: number of major vessels (0-3).

thall: thalassemia: 0 = null, 1 = fixed defect, 2 = normal, 3 = reversable defect

target : 0= less chance of heart attack 1= more chance of heart attack
This is an imbalanced dataset, a slightly moderate one. The models build and trained are: Logistic Regression, Random Forest Classifier, XGBoost Classifier, SVC, Gaussian Naive Bayes Classifier, KNN classifier. Since good scores of Precision, Recall, and F1 scores were obtained by all the models for both the majority and the minority classes, hence average precision score was not considered here. Out of all these, SVC yielded the best results in terms of accuracy, precision (for both the majority and the minority classes), recall (for both the majority and the minority classes), f1 score (for both the majority and the minority classes)
