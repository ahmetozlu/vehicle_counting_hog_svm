# Vehicle Detection, Tracking and Counting
This project focuses "Vehicle Detection" by [Support Vector Machine(SVM)](http://docs.opencv.org/2.4/doc/tutorials/ml/introduction_to_svm/introduction_to_svm.html) with [Histogram Oriented Gradients(HOG)](http://www.learnopencv.com/histogram-of-oriented-gradients/) features. OpenCV library ([version 3.0](http://opencv.org/opencv-3-0.html)) was used for implementation. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/30512919-72a57046-9b02-11e7-8ca8-c3e4bd993497.gif">
</p>

This project has vehicle counting system, the accuray is approximately 90%. Developing of the accuracy is in progress.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/30512835-aa0eb3fa-9b00-11e7-9c49-36a18d70b76c.gif">
</p>

[Click](https://github.com/ahmetozlu/vehicle_counting) to see another vehicle counting project which is developed with "Blob Detection" method.

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
    
## Installation
**For Windows Users**
- Please, use CMAKE;
Compiling with OpenCV 3.0 and Visual Studio 2013 from CMAKE
Dependencies:
- OpenCV 3.x (tested with OpenCV 3.0)
- GIT (tested with git version 2.7.2.windows.1).
- CMAKE for Windows (tested with cmake version 3.1.1).
- Microsoft Visual Studio (tested with VS2013).
Note: the procedure is similar for OpenCV 3.x and Visual Studio 2015.

Please follow the instructions below:

1. ) Go to Windows console.

2. ) Clone git repository:
    
        git clone --recursive https://github.com/ahmetozlu/vehicle_counting_hog_svm.git
    
3. ) Go to vehicle_counting_hog_svm/build folder.

4. ) Set your OpenCV PATH:

        set OpenCV_DIR=C:\OpenCV3.0\build
    
5. ) Launch CMAKE:

        cmake -DOpenCV_DIR=%OpenCV_DIR% -G "Visual Studio 12 Win32" ..
    
6. ) Include OpenCV binaries in the system path:

        set PATH=%PATH%;%OpenCV_DIR%\x86\vc12\bin
    
7. ) Open the vehicle_counting_hog_svm.sln file in your Visual Studio and switch to 'DEBUG' mode

8. ) Click on 'ALL_BUILD' project and build!

9. ) If everything goes well, copy vehicle_counting_hog_svm.exe to vehicle_counting_hog_svm/ and run!

**For Linux Users**

For Linux and Mac users, a CMakefile is provided to compile the source code.

- Check out the latest project source code and compile it:

      ~/git clone --recursive https://github.com/ahmetozlu/vehicle_counting_hog_svm.git
      ~/cd vehicle_counting_hog_svm
      ~/vehicle_counting_hog_svm/cd build
      ~/vehicle_counting_hog_svm/build/ cmake ..
      ~/vehicle_counting_hog_svm/build/ make

- Run demo:

      ~/vehicle_counting_hog_svm/run_vehicle_counting_hog_svm.sh

## Citation
If you use this code for your publications, please cite it as:

    @ONLINE{vdtc,
        author = "Ahmet Özlü",
        title  = "Vehicle Detection, Tracking and Counting",
        year   = "2017",
        url    = "https://github.com/ahmetozlu/vehicle_counting_hog_svm"
    }

## Author
Ahmet Özlü
- Please contact for dataset or more info: ahmetozlu93@gmail.com

## License
This system is available under the MIT license. See the LICENSE file for more info.
