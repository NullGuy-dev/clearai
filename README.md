# clearai (1.0.0)<br>
is a library with which you can create a neural network in a few lines.<br>
pip install clearai==1.0.0<br>
# Documentation<br>
Methods:<br>
createNeuralNetworkForClassification<br>
arguments:<br>
saveNeuralNetwork - this is a list, under index 0, a bool value is stored that indicates whether the model of this neuron should be saved so that it is not retrained each time, under index 1, a value is stored that indicates the name of the model to be saved (file extension .h5). Default: [True, "fashion_mnist_dense.h5"]<br>
loadNeuralNetworkForClassification<br>

createNeuralNetworkForReggresion<br>

loadNeuralNetworkForReggresion<br>
