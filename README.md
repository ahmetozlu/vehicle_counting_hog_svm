# Vehicle Detection and Counting by SVM with Hog Features (Front and Back Pose)
This project focuses "Vehicle Detection" by [Support Vector Machine(SVM)](http://docs.opencv.org/2.4/doc/tutorials/ml/introduction_to_svm/introduction_to_svm.html) with [Histogram Oriented Gradients(HOG)](http://www.learnopencv.com/histogram-of-oriented-gradients/) features. OpenCV library ([version 3.0](http://opencv.org/opencv-3-0.html)) was used for implementation. 

## Theory
#### What is SVM? 
A Support Vector Machine (SVM) is a discriminative classifier formally defined by a separating hyperplane. In other words, given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples.

#### What is HOG?
In the HOG feature descriptor, the distribution ( histograms ) of directions of gradients ( oriented gradients ) are used as features. Gradients ( x and y derivatives ) of an image are useful because the magnitude of gradients is large around edges and corners ( regions of abrupt intensity changes ) and we know that edges and corners pack in a lot more information about object shape than flat regions.

## Project Demo
- The demo is available on Youtube: https://www.youtube.com/watch?v=itmV7druy9Y&feature=youtu.be
- The screenshots:

    **Test Case 1:**
    ![screenshot_7](https://user-images.githubusercontent.com/22610163/29001171-19492cec-7a8a-11e7-81ea-db70cb6804d5.jpg)
    
    **Test Case 2:**
    ![screenshot_8](https://user-images.githubusercontent.com/22610163/29001176-389344ac-7a8a-11e7-9bdb-a76282e2eec3.jpg)
    


## Author
Ahmet Özlü
- Please contact for dataset or more info: ahmetozlu93@gmail.com

## License
This system is available under the MIT license. See the LICENSE file for more info.
