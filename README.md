# WineClassificationbySimpleNeuralNetwork

Classify Wine Type (White[1] or Red[0]) after learning from the Red Wine Quality Dataset and White Wine Quality Dataset 

## Dataset
Both datasets had **12** Features :
fixed acidity"; "volatile acidity"; "citric acid"; "residual sugar" ; "chlorides" ; "free sulfur dioxide" ; "total sulfur dioxide" ; "density" ; "pH" ; "sulphates" ; "alcohol" ; "quality"
**Red Wine Quality Dataset** contained 1599 samples 
**White Wine Quality Dataset** contained 4898 samples

## Technologies Used
- Jupyter Notebook
- Numpy
- Pandas
- Scikit Learn
- Matplotlib
- Tensorflow
- Keras

## Process Overview: 

- **5** Models are created using different architectures LSTM, different numbers of Dense Layers
- Activation functions like *relu* and *sigmoid* are used
- For Loss Measurement *Binary Cross-Entropy* is chosen
- The model is optimized using *Adam optimizer*
- The accuracy is shown finally in a bar chart.
- **Model 4** had the highest accuracy score.
- Tuned Hyperparameters for the best model. 

## Outcome
There are two expected outcomes: White(1) and Red(0).

### Models and Accuracy Scores

Accuracy of 5 models: {0: 0.9892307692307692, 1: 0.9923076923076923, 2: 0.9923076923076923, 3: 0.9969230769230769, 4: 0.9938461538461538}


