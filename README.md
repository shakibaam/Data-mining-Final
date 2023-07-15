# Diabetes Prediction Project

The objective of this project is to build a classifier to detect signs of diabetes or prediabetes in the given dataset. The dataset contains information from over 70,000 patients who have filled out questionnaires. The dataset consists of 22 columns, including various health-related features and target labels indicating the presence or absence of diabetes.

## Dataset Columns
- `y_Diabetes`: Indicates whether the individual has diabetes or prediabetes (yes or no)
- `HighBP`: High blood pressure
- `High Cholesterol`: High cholesterol level
- `Check Cholesterol`: Whether the individual has undergone cholesterol checkup or not
- `BMI`: Body Mass Index
- `Smoker`: Smoking status
- `Stroke`: Occurrence of stroke
- `HeartDiseaseorAttack`: History of heart disease or heart attack
- `Physical Activity`: Level of physical activity
- `Fruits`: Consumption of fruits
- `Vegetables`: Consumption of vegetables
- `Heavy Alcohol Consumption`: Heavy alcohol consumption
- `Care Health Any`: Health insurance coverage
- `Cost of because Doctor No`: Avoidance of doctor visits due to cost concerns
- `General Health`: General health condition
- `Mental Health`: Mental health condition
- `Physical Health`: Physical health condition
- `Walking Difficulty`: Difficulty in walking
- `Sex`: Gender
- `Age`: Age of the individual
- `Education`: Education level
- `Income`: Income level

## Preprocessing Steps
1. Removing missing data
2. Normalizing features
3. Feature engineering

## Building the Classifier Model
To build the classifier, we will be using the XGBoost library. The classifier will be trained on the dataset to predict the presence or absence of diabetes.

## Hyperparameter Tuning
We will perform hyperparameter tuning to optimize the performance of the classifier.

## Hyperparameter Visualization
Visualizing the changes in hyperparameters during the tuning process.


## Results
After training the classifier, we achieved an accuracy of 75% on the test set.
The picture below shows the confusion matrix.

Please refer to the code files for more detailed implementation and usage instructions.


![confusion matrix](https://github.com/shakibaam/Data-mining-Final/blob/main/confusion%20matrix.png)


