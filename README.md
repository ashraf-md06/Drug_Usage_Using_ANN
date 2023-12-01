# Drug_Usage_Using_ANN
An Artificial Neural Network (ANN) comprises interconnected layers of neurons, including
an input layer, hidden layers, and an output layer. The input layer receives data, which is then
processed through the hidden layers with the help of activation functions, introducing non-linearity.
During training, weights and biases are adjusted through backpropagation to minimize the prediction
error (loss). ANNs employ various activation functions such as sigmoid, ReLU, and tanh to capture
complex data patterns. The training process involves forward propagation, loss calculation,
backpropagation, weight updates, and multiple epochs to optimize the model. Once trained, ANNs
can make predictions on new data. The choice to use ANNs depends on the problem and dataset, as
they offer flexibility and applicability in various domains .
In this model, an Artificial Neural Network (ANN) is utilized to classify drug consumption
frequencies based on a diverse range of individual characteristics and personality traits. The process
begins by loading a dataset and expanding it by generating additional data samples to augment the
dataset&#39;s size. Subsequently, the data is prepared for analysis through standardization of input features
and mapping of drug consumption frequencies to numerical values.
The ANN is then constructed and trained for each drug category individually within the
model. The ANN architecture is composed of an input layer with neurons, representing the input
features. It is followed by two hidden layers, each applying the Rectified Linear Unit (ReLU)
activation function. The output layer comprises, which correspond to different drug consumption
frequency classes, and it uses the softmax activation function.
The ANN models are trained using the &#39;adam&#39; optimizer and the sparse categorical cross
entropy loss function for some training epochs. The performance of each model is assessed based on
its accuracy when tested with the provided data. The code iterates through multiple drug categories,
constructing and training individual models for each drug. The final accuracy results for each drug
category are displayed, and this information can be further employed for analysis and decision-
making. In summary, this model leverages ANN architectures to predict drug consumption
frequencies for various drugs, relying on a combination of personal traits and behaviours for
classification.
