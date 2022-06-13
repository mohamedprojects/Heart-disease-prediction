## Heart Disease Prediction

Heart Disease is among the most prevalent chronic diseases in the world. Detecting and preventing the factors that have the greatest impact on heart disease is very important in healthcare. Computational developments, in turn, allow the application of machine learning methods to detect "patterns" from the data that can predict a patient's condition.

## Dataset
The dataset has 14 attributes:

 - age: age in years.
 - sex: sex (1 = male; 0 = female).
 - cp: chest pain type (Value 0: typical angina; Value 1: atypical angina; Value 2: non-anginal pain; Value 3: asymptomatic).
 - trestbps: resting blood pressure in mm Hg on admission to the hospital.
 - chol: serum cholestoral in mg/dl.
 - fbs: fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
 - restecg: resting electrocardiographic results (Value 0: normal; Value 1: having ST-T wave abnormality; Value 2: probable or definite left ventricular hypertrophy).
 - thalach: maximum heart rate achieved.
 - exang: exercise induced angina (1 = yes; 0 = no).
 - oldpeak: ST depression induced by exercise relative to rest.
 - slope: the slope of the peak exercise ST segment (Value 0: upsloping; Value 1: flat; Value 2: downsloping).
 - ca: number of major vessels (0-3) colored by flourosopy.
 - thal: thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect).
 - target: heart disease (1 = no, 2 = yes).


## File Descriptions 

- 'heart.csv': the dataset file.
- 'Heart_Disease_Classification.ipynb': contains the code of data exploration, preparation and modeling. 
- 'model.pkl': the classification model. 
- 'model.py' : Flask API . 
- templates ('Heart Disease Classifier.html'): a web page that contains a form for heart disease testing. 
	

	

![Interface](https://user-images.githubusercontent.com/75954544/173339905-c0861a13-2f47-4639-ac99-76b77c3d5d2a.JPG)



