<h1 align="center">Face Mask Detection</h1>

<div align= "center"><img src="https://user-images.githubusercontent.com/81526639/158228829-e0f3d24e-23ec-47cf-99e6-1a0f2709ec93.png" width="200" height="200"/>
  <h4>Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>

## Motivation
With the COVID-19 pandemic worldwide, the entire world population was forced to wear personal protective equipment (medical masks, rubber gloves, etc.) to protect themselves and others. But, unfortunately, many people neglect these rules.
  
<p align="center"><img src="https://github.com/zapup4lk/FaceMaskDetection/blob/main/Examples/Ex%20No.%203" width="700" height="400"></p>
  
## :warning: TechStack/Frameworks used

- [TensorFlow](https://www.tensorflow.org/)
- [keras](https://keras.io/)
- [imutils](https://pypi.org/project/imutils/)
- [NumPy](https://numpy.org/)
- [OpenCV](https://opencv.org/)
- [Matplotlib](https://matplotlib.org/)
- [SciPy](https://scipy.org/)
  
## :star: Features
  
Our face mask detector doesn't use any morphed masked images dataset and the model is relatively accurate. 

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.
  
In the future it is planned to rebuild the model on the basis of MobileNetV2 architecture, it is computationally efficient, thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).
  
## :file_folder: Dataset
  
The dataset can be downloaded here - [Click to Download]()
  
This dataset consists of __6000 images__ belonging to two classes:
*	__with_mask: 3000 images__
*	__without_mask: 3000 images__
  
## :key: Prerequisites

All required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/zapup4lk/FaceMaskDetection/blob/main/requirements.txt)

## :key: Results
  
#### We got the following accuracy/loss training curve plot
![](https://github.com/zapup4lk/FaceMaskDetection/blob/main/plot.png)
