# Neural_Network_Charity_Analysis
Preprocessing Data for a Neural Network model with optimization

## Overview:
Create a binary classifier to tell if applicants will be successfully funded by a charitable orginization called alphabet soup. This dataset has over 34,000 organizations funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as organization type, the use of funding amongst others. This project compromised of the following 3 steps: 
- Preprocessing the data for the neural network 
- Compile, Train, and Evaluate the Model 
- Model optimization

## Results:

### Data Preprocessing 
- Variable that was considered the target for the model: IS_SUCCESSFUL Column
- Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL 
- Columns dropped are EIN, NAME 

### Compiling, Training, and Evaluating the Model

- I selected 80 neurons with a relu function for my first layer, 30 nuerons with a relu function for the second, and a sigmoid function for the outer layer.  
- This model has an accuracy of 72.6 % which is below the target model performance.
- I tried to increase the model performance by increasing the bin size from 500 to 800, by using 3 hidden layers, and by changing activation from relu to tanh.

## Summary: 

The three attempts to optimize the model accuracy ended up being less accurate that the initial model. This could mean that the initial model was fairly optimized to begin with
