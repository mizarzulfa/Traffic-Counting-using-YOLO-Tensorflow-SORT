# Python Traffic Counter

The purpose of this project is to detect and track vehicles on a webcam or video stream and count those going through a defined line. 

It uses:

* [YOLO](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv) to detect objects on each of the video frames.

* [SORT](https://github.com/abewley/sort) to track those objects over different frames.

Once the objects are detected and tracked over different frames a simple mathematical calculation is applied to count the intersections between the vehicles previous and current frame positions with a defined line.

The code on this prototype uses the code structure developed by Adrian Rosebrock for his article [YOLO object detection with OpenCV](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv).

## Quick Start
 - You can use weight from YOLO website (http://pjreddie.com/darknet/yolo/) or use your own trained weight
 - Change lines coordinate with your own video in main.py
 - Set path file with your own path
 - run main.py 

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/FDZiLg3_S64" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
