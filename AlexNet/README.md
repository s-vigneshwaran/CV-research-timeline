# ImageNet Classification with Deep Convolutional Neural Networks

### Alex Krizhevsky, Ilya Sutskever, and Geoffrey E. Hinton. 2012. In Proceedings of the 25th International Conference on Neural Information Processing Systems - Volume 1 (NIPS'12). Curran Associates Inc., Red Hook, NY, USA, 1097–1105

https://proceedings.neurips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html

![Alexnet Architecture](https://miro.medium.com/max/3072/1*qyc21qM0oxWEuRaj-XJKcw.png)

The first convolutional layer filters the 224×224×3 input image with 96 kernels of size 11×11×3 with a stride of 4 pixels. The second convolutional layer takes as input the (response-normalized and pooled) output of the first convolutional layer and filters it with 256 kernels of size 5 × 5 × 48. The third, fourth, and fifth convolutional layers are connected to one another without any interveningThe pooling or normalization layers. The third convolutional layer has 384 kernels of size 3 × 3 × 256 connected to the (normalized, pooled) outputs of the second convolutional layer. The fourth convolutional layer has 384 kernels of size 3 × 3 × 192 , and the fifth convolutional layer has 256 kernels of size 3 × 3 × 192. The fully-connected layers have 4096 neurons each

### Details
- Dropout with 0.5 probability
- Learning Rate was adjusted throughout the training process."The heuristic which we followed was to divide the learning rate by 10 when the validation error rate stopped improving with the current learning rate. The learning rate was initialized at 0.01 and reduced three times prior to termination"
- Local Response Normalization was used as at the time of implementation Batch Normalization was not yet invented. (Implemented Using Lambda Layer in this notebook)
- In the original work, PCA was used to perform RGB corrections on the entire image training set.
