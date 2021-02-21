# Neural_Network_Charity_Analysis
## Overview<br>
The purpose of the analysis was to classify the success of charitable donations. This was accomplished with deep learning neural networks using the TensorFlow platform<br>

## Results
### Data Preprocessing<br>
- Target column "IS_SUCCESSFUL" is the target for the deep learning neural network
- Feature columns for the deep learning neural network include "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"
- Features "EIN" and "NAME" are dropped 

### Compiling, Training, and Evaluating the Model<br>
- Deep learning neural network anatomy
  - Hidden layer 1: 80 neurons; Activation function: ReLu
  - Hidden layer 2: 30 neurons; Activation function: ReLu
  - Output layer: One neuron (binary classification); Activation function: Sigmoid
- The network achieved approximately 73% accuracy, falling short of the targeted outcome of 75% accuracy
- Attempts to optimize performance were made, including additional input neurons, different activation functions, and additional hidden layers<br>

#### Input: 90 neurons
<img src= "https://github.com/ChrisBarton107/Neural_Network_Charity_Analysis/blob/main/Resources/Input.png" height="300" width="600"><br>
#### Activation function: Tanh
<img src= "https://github.com/ChrisBarton107/Neural_Network_Charity_Analysis/blob/main/Resources/Activation.png" height="300" width="700"><br>
#### Hidden Layers: Three
<img src= "https://github.com/ChrisBarton107/Neural_Network_Charity_Analysis/blob/main/Resources/Hidden.png" height="300" width="600"><br>

## Summary
Our deep learning neural network didn't achieve the desired outcome of atleast 75% accuracy. The task could potentially be improved by using a Random Forest classifier, which is capable of binary classification
