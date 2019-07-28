# Sementic-Segmentation
Kitti Road dataset and VGG16 model was used for this project.

Implemented Skip Connection to improve segmentation accuracy (The authors of [this paper](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) highly suggest to use the skip layers.
![skip layers](https://github.com/kangcshin/Semantic-Segmentation/blob/master/skip.png)

Adam Optimizer was used in this model with the learning rate of 0.0009.

The model labels most pixels of the road close to the best solution and achieves over 80% accuracy which was my initial goal. 
#### Training Image
![train](https://github.com/kangcshin/Semantic-Segmentation/blob/master/um_000009.png)
#### Segmented Image
![1](https://github.com/kangcshin/Semantic-Segmentation/blob/master/uu_000025.png) ![2](https://github.com/kangcshin/Semantic-Segmentation/blob/master/uu_000031.png)
