## Analysis Overview

The purpose of this project is to use Neural networks with the TensorFlow platform in Python, in order to analyze and classify the success of charitable donations. For this analysis Alphabet Soup  has provided a dataset that contains various measures on 34,000 organizations. 
We use the following methods for the analysis:
- Preprocessing the data for the neural network
- Compile, Train and Evaluate the Model
- Optimizing the model

## Results

### Data Preprocessing

1. Variable that was considered as the target for my model: IS_SUCCESSFUL column.
2. Variables that were considered features for my model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
3. Variable that were neither targets or features for the dataset: EIN and NAME columns have been dropped because they have little to no impact on the outcome.

### Compiling, Training, and Evaluating the Model

4. How many neurons, layers, and activation functions did you select for your neural network model?

The model is made with an input features & two hidden layers. 
- First hidden layer has 80 neurons and a relu activation function
- Second hidden layer has 30 neurons and a relu activation function
- The output layer has a sigmoind function

<img src="https://i.ibb.co/W2kn1dd/1-relu.png" alt="1-relu" border="0"> 

5. Was the model able to achieve the target model performance?

The target performance was 75%. The accuracy of my model is 72%. 

<img src="https://i.ibb.co/VTDJ02L/2-accuracy.png" alt="2-accuracy" border="0">

6. What steps were taken to try and increase model performance?

I changed the activation function for first and second layers to sigmoind. Also I have increased the number of epochs to 200. 

<img src="https://i.ibb.co/JBySPSY/3-sigmoind.png" alt="3-sigmoind" border="0">

Despite of all changes that have been made the accuracy of the model hasn’t increased. It is still at 72%.

<img src="https://i.ibb.co/txm8FDG/4-accuracy.png" alt="4-accuracy" border="0">
