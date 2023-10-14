# WineClassificationbySimpleNeuralNetwork

Classify Wine Type (White[1] or Red[0]) after learning from Red Wine Quality Dataset and White Wine Quality Dataset 

## Dataset
Both datasets had ```"fixed acidity"; "volatile acidity"; "citric acid"; "residual sugar" ; "chlorides" ; "free sulfur dioxide" ; "total sulfur dioxide" ; "density" ; "pH" ; "sulphates" ; "alcohol" ; "quality"
**Red Wine Quality Dataset** contained 1599 samples 


## Technologies Used
- Jupyter ```Notebook
- Numpy
- Pandas
- Scikit Learn
- Matplotlib

## Outcome
There are two expected outcomes: Malignant(1) and Benign(0).

### Models and Accuracy Scores

{'Ridge Classifier': 0.956140350877193,
 'SVC': 0.9736842105263158,
 'Decision Tree': 0.9122807017543859,
 'Random Forest': 0.9736842105263158}

**SVC and Random Forest perform the best and Decision Tree performs the worst!** 



## Conclusion
I randomly chose one of the test samples and predicted, using all four models by the **voting method**, if the person has breast cancer or not.




