# Social Distance Detector
An ANN project on social distancing. 

The main aim of the project is to detect whether the people are maintaining social distancing or not so that we can alert the specified area that is crowded in order to reduce the social distancing. In Real-time scenario, this application can be useful especially in this pandemic situation in the specified areas such as Shopping malls, Food Courts, Offices, Universities etc., where CC cameras are available. 

# Flowchart of the application
<img src="/socialdistancing flowchart.png" alt="flowchart"> 

# Working of application in realtime scenario
<img src="/SocialDistancingReal.jpeg" alt="real"> 

### SSD Object Detection in Real Time (Deep Learning and Caffe)
Single Shot MultiBox Detector (SSD)
SSD Object Detection extracts feature map using a base deep learning network, which are CNN based classifiers, and applies convolution filters to finally detect objects. Our implementation uses MobileNet as the base network (others might include- VGGNet, ResNet, DenseNet).

### What is Caffe?
Caffe is a deep learning framework developed by Berkeley AI Research and community contributors. Caffe was developed as a faster and far more efficient alternative to other frameworks to perform object detection. Caffe can process 60 million images per day with a single NVIDIA K-40 GPU. That is 1 ms/image for inference and 4 ms/image for learning.

### What alternative object detection frameworks can be used?
Apart from SSD, there are other frameworks which can be implemented in object detection, the more popular ones being YOLO and Fast/Faster-R CNN. The three have their own set of pros and cons, however the SSD method has been found to be the fastest and most efficient among these.

### Tools
```
Software: Python 3
Requirements: OpenCV, NumPy, argparse, Caffe MobileNet SSD model weights, and prototxt 
To run the application: python social_distance_detector.py --videopath “videoname.mp4”. 
```

