# VDDS

## ABOUT

<p> Virtual Disease Diagnosis System is a web application that enables the user to do multiple disease prediction in a single app. The existing frameworks were studied and improvements were done in terms of exactness, dependability and productivity.Once the user inputs his symptoms, the system predicts the disease after which it also analyses the same inputs and gives suggestions to prevent the risk of future complications.</p>

This webapp was developed using Flask Web Framework and was deployed on Heroku server. The webapp can predict following Diseases:

- Diabetes
- Breast Cancer
- Heart Disease
- Kidney Disease
- Liver Disease
- General Disease Predictor

## Models with their Accuracy of Prediction

| Disease        | Type of Model            | Accuracy |
| -------------- | ------------------------ | -------- |
| Diabetes       | Machine Learning Model   | 96.0%    |
| Breast Cancer  | Machine Learning Model   | 97.37%   |
| Heart Disease  | Machine Learning Model   | 88.5%    |
| Kidney Disease | Machine Learning Model   | 100%     |
| Liver Disease  | Machine Learning Model   | 83.7%    |

## Dataset Links

- [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
- [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
- [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
- [General Disease Dataset](https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning)

## The models used for the disease prediction are listed below:

<ul>
<li><p><b>Cancer model = model</b></p></li>
<li><p><b>Diabetes model = model1</b></p></li>
<li><p><b>Heart model = model2</b></p></li>
<li><p><b>Liver model = model4</b></p></li>
<li><p><b>Kidney model = model3</b></p></li>
<li><p><b>General Disease model = trained_model</b></p></li>
You can find all the models in [models] (https://github.com/ayushii019/Virtual-Disease-Diagnosis-System/tree/main/models) folder.


</ul>

## Install

This project requires **Python 3.6**  and the libraries used are included in [Requirements](https://github.com/ayushii019/Virtual-Disease-Diagnosis-System/blob/main/requirements.txt)

## Steps to run this application in your system

1. Clone or download the repository.
2. Open command prompt in the downloaded folder.
3. Create a virtual environment

```
mkvirtualenv environment_name
```

4. Install all the dependencies:
```
pip install -r requirements.txt
```
5. Run the application

```
python app.py
```
