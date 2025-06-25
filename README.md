# **Image Multi-Classification Using PyTorch and CNN** <br/>

**Tools Used:** Convolutional Neural Network (CNN), PyTorch, Torchvision Libraries, Stochastic Gradient Descent (SGD)<br/>
**Result:** Creates a Convolutional Neural Network (CNN) which multi classifies images from a dataset<br/><br/>

**Description:** <br/>

The project begins by importing required PyTorch and torchvision libraries for dataset handling and model building.<br/>
An animal dataset is loaded using torchvision.datasets, with training and testing sets defined separately.<br/>
Basic image transformations such as ToTensor and normalization are applied to scale image pixel values.<br/>
Data is batched and shuffled using DataLoader to optimize the training loop.<br/>
A Convolutional Neural Network (CNN) class is defined by subclassing nn.Module.<br/>
The model includes two convolutional layers with ReLU activations and max-pooling operations.<br/>
Feature maps are flattened before passing through three fully connected (linear) layers.<br/>
The final output layer maps to 10 classes corresponding to labels.<br/>
Cross-entropy loss is chosen as the loss function for classification tasks.<br/>
The optimizer used is Stochastic Gradient Descent (SGD) with momentum.<br/>
The training loop iterates over several epochs, performing forward and backward passes.<br/>
After each epoch, the model’s performance is evaluated on the test dataset.<br/>
Accuracy and loss metrics are printed to monitor learning progress.<br/>
Finally, the model’s predictions on sample test images are visualized to validate output.<br/>

