# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description

**Input:** Describe the inputs of your model 

Data is downloaded from here: https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones

train.csv
test.csv

The Human Activity Recognition database was built from the recordings of 30 study participants performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The objective is to classify activities into one of the six activities performed.

**Output:** Describe the output(s) of your model

Confusion matrix and Accuracy Score produced by the Model

Also, optimised hyperparameters

**Model Architecture:** Describe the model architecture you’ve used

A SVM model using default linear hyper parameters and optimised hyperparamters


## Performance

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 

Linear SVM cross-validation accuracy: 0.9366237970375098
Optimized RBF SVM cross-validation accuracy: 0.9432876889708977
Linear SVM test accuracy: 0.9613165931455717
Optimized RBF SVM test accuracy: 0.9582626399728538


## Limitations

Outline the limitations of your model.

My model is limited to the available dataset, which was produced by 30 study perticipants.

The optimised hyper parameter version of the SVM performed only slighty better on the training set and slightly less well than the linear model on the test data set.

There are only a small number of labels defining a basic description of activity.

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 
