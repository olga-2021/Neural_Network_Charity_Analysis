## Analysis Overview

The purpose of this project is to use Neural networks with the TensorFlow platform in Python, in order to analyze and classify the success of charitable donations. For this analysis Alphabet Soup  has provided a dataset that contains various measures on 34,000 organizations. 
We use the following methods for the analysis:
•	Preprocessing the data for the neural network
•	Compile, Train and Evaluate the Model
•	Optimizing the model

## Results

### Data Preprocessing
•	Variable that was considered as the target for my model: IS_SUCCESSFUL column.
•	Variables that were considered features for my model:  All columns except IS_SUCCESSFUL column that has been dropped. 
•	Variable that were neither targets or features for the dataset: EIN and NAME columns have been dropped because they have little to no impact on the outcome.

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model
The model is made with an input features & two hidden layers. 
•	First hidden layer has 80 neurons and a relu activation function
•	Second hidden layer has 30 neurons and a relu activation function
•	The output layer has a sigmoind function
<img src="https://i.ibb.co/W2kn1dd/1-relu.png" alt="1-relu" border="0"> 
Was the model able to achieve the target model performance?
The target performance was 75%. The accuracy of my model is 72%. 
<img src="https://i.ibb.co/VTDJ02L/2-accuracy.png" alt="2-accuracy" border="0">

<img src="https://i.ibb.co/JBySPSY/3-sigmoind.png" alt="3-sigmoind" border="0">
<img src="https://i.ibb.co/txm8FDG/4-accuracy.png" alt="4-accuracy" border="0">
