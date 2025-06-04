# cnn_fashionmnist_regularization.ipynb
A convolutional neural network (CNN) trained on Fashion MNIST with and without regularization techniques like batch normalization and dropout.

##  CNN with Regularization on Fashion MNIST

I trained a convolutional neural network (CNN) to classify clothing items from the Fashion MNIST dataset.  
But instead of just building a model and calling it a day, I wanted to explore how **regularization** affects performance.

---

### I did:
- Used the Fashion MNIST dataset (28x28 grayscale clothing images)
- Built two models:
  - One basic CNN
  - Another with **batch normalization** and **dropout**
- Trained both on the same data and compared their accuracy on training and validation sets

---

### I found:
The regularized model was slightly slower to train at first, but it handled overfitting much better.  
Validation accuracy stayed more stable, and the model generalized better to unseen data.

A few tweaks like batch normalization and dropout can make a big difference, especially when you're dealing with small or noisy datasets.


Tools used: `TensorFlow`, `Keras`, `Matplotlib`, `NumPy`

