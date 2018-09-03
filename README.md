# Titanic_Survivor_Prediction-using-SVM
This is in reference to the Titanic Challenge hosted on **Kaggle** website.

## Dataset
Dataset is taken on _Kaggle_ . All the information is on the website is same and considered as it is for building this model.

## About Model
- Kernel SVM - Radial Bases Fuction - **Gaussian RBF**
- Input Parameters : **'Pclass', 'Sex', 'Age', 'Fare', 'Embarked'**
- Missing values have been substituted by **column mean** (axis=1)
- The Alphabetical parameters have been substituted by **'ffill'** method.
- The model has been impoved with the help of _Grid Search_ algorithm, but the algorithm is not mentioned in the file. 

**ACCURACY : 76.468%**


