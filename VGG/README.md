# Very Deep Convolutional Networks for Large-Scale Image Recognition

### Simonyan, K. & Zisserman, A. (2014). Very deep convolutional networks for large-scale image recognition. arXiv preprint arXiv:1409.1556, .

https://arxiv.org/abs/1409.1556

![Alexnet Architecture](https://miro.medium.com/max/2628/1*lZTWFT36PXsZZK3HjZ3jFQ.png)

Total of six models were created as part of the paper.

- Even though Adam optimizer was published in the year 2014, it is a well known fact that adam fails due to large number of parameters
- The 11 layer(A-LRU), 13 Layer(B), 16 Layer(D), 10 Layer(E) are implemented.
- Data Generators use flow from directory. So before running the cells after model.compile() please update the variables TRAIN, TEST and VALIDATION to the location of ImageNet dataset
