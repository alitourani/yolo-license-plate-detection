# License-plate Detection by YOLO

This application is a deep-learning based license-plate detection to localize the correct location of vehicles' license-plate with a high rate of accuracy.
This project is a License-Plate Detection (LPD) application for vision-based Intelligent Transportation Systems (ITS). These systems utilize roadway camera outputs (images/video-frames) to apply video processing techniques and extract the desired information, which is vehicles' license-plates in this special case. We have utilized YOLO v3 in this project to achive the license-plates with high accuracy and in almost realtime.

![Sample Output](http://alitourani.ir/wp-content/uploads/Deep-LPD-AliTourani-SajjadSoroori.png "Sample Output")

## Environment

- Python v.3
- You Only Look Once (YOLO) v.3

## Usage

Download weight file from [this](https://drive.google.com/file/d/1vXjIoRWY0aIpYfhj3TnPUGdmJoHnWaOc/ "this") link.

Testing on single image file:

```
python object_detection_yolo.py --image=bird.jpg
```

Testing on single video file:

```
python object_detection_yolo.py --video=cars.mp4
```

Testing on webcam:

```
python object_detection_yolo.py
```

## Citation

1. S. Khazaee, A. Tourani, S. Soroori, A. Shahbahrami, and C. Y. Suen, “**A Real-time License-Plate Detection Method using a Deep Learning Approach**,” 2nd International Conference on Pattern Recognition and Artificial Intelligence, Zhongshan, 2020. ([link](https://users.encs.concordia.ca/~icprai20/ "link"))

## Contributors

- [Sajjad Soroori](https://github.com/SajjadSo "Sajjad Soroori")
- [Ali Tourani](https://github.com/alitourani "Ali Tourani")
