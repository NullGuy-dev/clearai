# clearai (1.0.0)<br>

is a library with which you can create a neural network in a few lines.<br>

pip install clearai==1.0.0<br>

# Documentation<br>

Methods:<br>

createNeuralNetworkForClassification<br>

arguments:<br>

saveNeuralNetwork - this is a list, under index 0, a bool value is stored that indicates whether the model of this neuron should be saved so that it is not retrained each time, under index 1, a value is stored that indicates the name of the model to be saved (file extension .h5). Default: [True, "fashion_mnist_dense.h5"]<br>

lossD - loss value in keras. Default: "categorical_crossentropy"<br>

optimizerD - optimizer value in keras. Default: "SGD"<br>

metricsD - metrics value in keras. Default: ["accuracy"]<br>

batchSizeD - batch_size value in keras. Default: 200<br>

epochsD - epochs value in keras. Default: 100<br>

verboseD - verbose value in keras. Default: 1<br>

activationD - activations value in keras, this is a list because these values will be in the activation of each layer according to the count you specify in neuronLayersCount. Default: ['relu','softmax']<br>

loadNeuralNetworkForClassification<br>

createNeuralNetworkForReggresion<br>

loadNeuralNetworkForReggresion<br>
