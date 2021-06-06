# Going Deeper with Convolutions

### Szegedy, C., Wei Liu, Yangqing Jia, Sermanet, P., Reed, S., Anguelov, D., Erhan, D., Vanhoucke, V. & Rabinovich, A. (2015). Going deeper with convolutions. 2015 IEEE Conference on Computer Vision and Pattern Recognition (CVPR) (p./pp. 1-9), June, .

![Inspiration](https://i.kym-cdn.com/photos/images/newsfeed/000/531/557/a88.jpg)

https://arxiv.org/abs/1409.4842

![GoogLeNet Architecture](https://miro.medium.com/max/5176/1*ZFPOSAted10TPd3hBQU8iQ.png)

GoogLeNet is famously known as inception_v1.

- This model is implemented using the tensorflow Functional API as it is not possible to implement using the Sequential models due to its limitaions.
- Data Generators use flow from directory. So before running the cells after model.compile() please update the variables TRAIN, TEST and VALIDATION to the location of ImageNet dataset
