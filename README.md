# Deep Learning Challenge

## Overview of the analysis 
    The purpose of this analysis is to provide the nonprofit foundation, 
    Alphabet Soup, a tool that will aid in the selection of funding 
    applicants who may have the best chance of success in their ventures.

## Task
   The analyst will use the features in the provided dataset and apply machine learning and neural networks functions to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Data Engineering: Libraries and Dependencies
  1. Pandas
  2. TensorFlow 
  3. KerasTuner
  4. Sklearn
  5. Matplotlib.pyplot
  6. Google Colab
   
Results: Using bulleted lists and images to support your answers, address the following questions:

## Data Preprocessing

1. What variable(s) are the target(s) for your model? 
   - IS_SUCCESSFUL
2. What variable(s) are the features for your model?
   - EIN	
   - NAME
   - APPLICATION_TYPE 
   - AFFILIATION
   - CLASSIFICATION
   - USE_CASE 
   - ORGANIZATION	
   - STATUS	
   - INCOME_AMT	
   - SPECIAL_CONSIDERATIONS	
   - ASK_AMT

3. What variable(s) should be removed from the input data because they are neither targets nor features?

## Compiling, Training, and Evaluating the Model
The results of the initial bianry classification model yielded the following accuracy and loss results: Accuracy: 0.7331 /  Loss: 0.5480

Model and  Plots
- Initial structure model (See image folder)
- Plot of the initial model accuracy data (See image folder)
- Plot of the initial model loss data (See image folder)

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Number of neurons: 10, layers: 3, and activation function: ReLU and sigmoid 
- The why. 
    1. Neurons and Layers. 
       - The number of neurons is equal to the number of features in input layer, 10
       - The hidden layer, 32. It is recommeded to use either 32, 64, or 128  for simple tasks
       - The output layer, 1 
       - Its common practice is to start with 1–3 hidden layers, and adjust depending on the model performance
    2. Activation
       - ReLU is a common choice, especially for deep learning models due to its efficiency 
       - Sigmoid to support binary classification.

## optimizization of the model 
The goal of the optimization is to to achieve a target predictive accuracy higher than 75%.

1. What steps did you take in your attempts to increase model performance?
2. Were you able to achieve the target model performance?

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

