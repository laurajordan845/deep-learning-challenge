# Report on the Neural Network Model

## Overview of the Analysis

#### Background

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. The analysis had the primary goal of creating a binary classifier that can predict whether applicants would be successful if funded by Alphabet Soup. 

## Results

* Data Preprocessing
    * I received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 
    * To preprocess the data, I removed the fields that held no value to this analysis – EIN and Name.
    * The variables I used for the analysis were: Application Type, Affiliation, Classification, Use Case, Organization, Status, Income Amount, Special Considerations, Ask Amount and Is Successful.
    * The dependent variable for this analysis was the Is Successful since we are using it to predict an applicant’s ability to be successful.
* Compiling, Training, and Evaluating the Model
  * Model 1:
      *	2 hidden layers
      * 80 neurons in layer 1
      * 30 neurons in layer 2
      * Used Relu and Sigmoid activation functions since Sigmoid is best for binary classifications and Relu is for nonlinear datasets. 
      * The result of this model was 61.97% accuracy
  * Model 2:
      * 2 hidden layers
      * 10 neurons in layer 1
      *	20 neurons in layer 2
      *	Used Relu and Sigmoid activation functions on this model as well
      *	The result of this model was 72.38% accuracy
  *	Model 3: 
      *	2 hidden layers
      *	5 neurons in layer 1
      *	15 neurons in layer 2
      *	Used Relu and Sigmoid activation functions on this model as well
      *	The result of this model was 59.78% accuracy
*	I tried to change the model to try to achieve more than 75% accuracy but was not able to within 3 tries. 


## Summary

My 2nd model achieved the highest accuracy at 72%, which is decent considering where the other two landed. My recommendation is to improve this model to find best features to help determine what will predict applicants with the highest chances at success.
