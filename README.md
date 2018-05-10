# fruit-classification
Fruit classification in the sense of non-person market.
# The Original imges is as follow:
![img_10](https://github.com/Laviyy/fruit-classification/blob/master/originalImgSamples/img_10.jpg)
![20170307170522](https://github.com/Laviyy/fruit-classification/blob/master/originalImgSamples/20170307170522.jpg)
# The Segmented images  is as follow:
![Seg20170307144225](https://github.com/Laviyy/fruit-classification/blob/master/ROIImgSamples/Seg20170307144225.jpg)
# Dataset
There are totally have 26 classes. Every class have 81 to 148 samples. The resolution is 720 * 1280.
# Main ideal
1.Segment foreground from the image. We will use Matlab complete this task.
2.Extract features from segmented iamges. The color features are more important. We will use python complete this task.
3.Classification. We will use python complete this task.
# The Result
The accuracy of SVM:
0.744196256117
             precision    recall  f1-score   support

          0       0.75      0.92      0.83        26
          1       0.73      0.93      0.82        44
          2       1.00      0.93      0.96        28
          3       0.62      0.84      0.71        37
          4       0.47      0.81      0.59        27
          5       0.79      0.77      0.78        48
          6       0.72      0.81      0.76        42
          7       0.73      0.78      0.75        45
          8       0.77      0.97      0.86        31
          9       0.64      0.60      0.62        35
         10       1.00      0.94      0.97        32
         11       0.95      0.90      0.92        41
         12       0.73      0.35      0.48        31
         13       0.40      0.10      0.16        41
         14       0.97      1.00      0.99        34
         15       0.65      0.57      0.61        53
         16       0.62      1.00      0.77        20
         17       0.96      1.00      0.98        44
         18       1.00      0.91      0.96        35
         19       1.00      1.00      1.00        23
         20       0.51      0.44      0.47        55
         21       0.59      0.53      0.56        36
         22       0.73      0.77      0.75        31
         23       0.66      0.52      0.58        52
         24       0.42      0.59      0.49        34
         25       0.79      0.61      0.69        38

avg / total       0.73      0.73      0.72       963

accuracy_score: 0.730010384216
