# Grokking Deep Learning

Code reproduction and theory summaries for each chapter of *Grokking Deep Learning* (Andrew W. Trask, Manning). Every notebook contains a chapter summary, theory explanations, and runnable NumPy code.

## Contents

| # | Notebook | Topic | General explanation |
|---|---|---|---|
| 1 | [01.intro.ipynb](01.intro.ipynb) | Introducing Deep Learning | Why learn deep learning, relation to ML/AI, why build from scratch. |
| 2 | [02.fundamentalconc.ipynb](02.fundamentalconc.ipynb) | Fundamental Concepts | Supervised/unsupervised/reinforcement learning; parametric vs non-parametric; predict-compare-learn. |
| 3 | [03.neuralprediction.ipynb](03.neuralprediction.ipynb) | Neural Prediction | Forward propagation: weighted sums, multiple inputs/outputs, hidden layers. |
| 4 | [04.gradientdescent.ipynb](04.gradientdescent.ipynb) | Gradient Descent | Error measures, hot-and-cold learning, derivatives, learning rate, divergence. |
| 5 | [05.generalazinggradient.ipynb](05.generalazinggradient.ipynb) | Generalizing Gradient Descent | Learning many weights at once; multi-input/output updates; freezing weights. |
| 6 | [06.backpropagation.ipynb](06.backpropagation.ipynb) | Backpropagation | Streetlight problem, correlation, ReLU, hidden layers, backprop algorithm. |
| 7 | [07.visualizingnn.ipynb](07.visualizingnn.ipynb) | Visualizing Neural Networks | Layers as vectors, weights as matrices, shape rules, drawing networks. |
| 8 | [08.regularizationbatching.ipynb](08.regularizationbatching.ipynb) | Regularization and Batching | Overfitting, early stopping, dropout, mini-batch gradient descent. |
| 9 | [09.activationfunctions.ipynb](09.activationfunctions.ipynb) | Activation Functions | ReLU/sigmoid/tanh, softmax output, probabilities, cross-entropy gradient. |
| 10 | [10.convolutionalnn.ipynb](10.convolutionalnn.ipynb) | Intro to Convolutional Neural Networks | Weight sharing, kernels, feature maps, edge/corner detection. |

Chapters 8-10 use scikit-learn's bundled 8x8 digits dataset (offline) as a stand-in for MNIST.

## Running
```
pip install numpy matplotlib scikit-learn jupyter
jupyter notebook
```
