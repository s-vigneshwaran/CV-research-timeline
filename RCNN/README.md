# Rich feature hierarchies for accurate object detection and semantic segmentation

### Girshick, R., Donahue, J., Darrell, T. & Malik, J. (2014). Rich Feature Hierarchies for Accurate Object Detection and Semantic Segmentation. 2014 IEEE Conference on Computer Vision and Pattern Recognition (CVPR) (p./pp. 580-587), June, .

https://arxiv.org/abs/1311.2524

![RCNN Architecture](https://neurohive.io/wp-content/uploads/2018/11/Capture-16.jpg)

- 2000 regions are proposed from the image by running Selective Search Segmentaion[J. Uijlings, K. van de Sande, T. Gevers, and A. Smeulders.
Selective search for object recognition. IJCV, 2013]
- These proposed regions are feeded to a pre-trained AlexNet but instead of the softmax layer, it used Support Vector Machine to classify the image.
