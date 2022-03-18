<h1 align="center">Face Mask Detection</h1>

<h1 align= "center"><img src="https://user-images.githubusercontent.com/81526639/158228829-e0f3d24e-23ec-47cf-99e6-1a0f2709ec93.png" width="200" height="200"/>
  <h4 align= "center">Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Live Demo](https://github.com/zapup4lk/FaceMaskDetection/blob/main/Examples/720%20(1).gif)

## Motivation
With the COVID-19 pandemic worldwide, the entire world population was forced to wear personal protective equipment (medical masks, rubber gloves, etc.) to protect themselves and others. But, unfortunately, many people neglect these rules.
  
<p align="center"><img src="https://github.com/zapup4lk/FaceMaskDetection/blob/main/Examples/Ex%20No.%203.png">
  
### :warning: TechStack/Frameworks used

- [TensorFlow](https://www.tensorflow.org/)
- [keras](https://keras.io/)
- [imutils](https://pypi.org/project/imutils/)
- [NumPy](https://numpy.org/)
- [OpenCV](https://opencv.org/)
- [Matplotlib](https://matplotlib.org/)
- [SciPy](https://scipy.org/)
  
### :star: Features
  
Our face-mask detector doesn't use any morphed masked images dataset and the model is relatively accurate. 

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools and public places to ensure that public safety guidelines are followed.
  
In the future it is planned to rebuild the model on the basis of MobileNetV2 architecture, it is computationally efficient, this making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).
  
### :file_folder: Dataset
  
The dataset can be downloaded here - [Click to Download](https://www.kaggle.com/vijaykumar1799/face-mask-detection)
  
This dataset consists of __6886 images__ belonging to three classes:
*	__with_mask: 5886 images__
*	__without_mask: 1000 images__
  
The images were collected from [Kaggle](https://www.kaggle.com/)
  
### :key: Prerequisites

All required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/zapup4lk/FaceMaskDetection/blob/main/requirements.txt)
 
### Installation

1. Clone the repo
```
$ git clone https://github.com/zapup4lk/FaceMaskDetection.git
```
  
2. Change your derictory to the cloned repo
```
$ cd FaceMaskDetection
```

3. Create a python virtual environment named 'test' and activate it
```
$ virtualenv test
```
```
$ source test/bin/activate
```
  
4. Now, run the following command in your terminal to install the libs
```
$ pip3 install -r requirements.txt
```


### :bulb: Working
  
1. Open terminal. Go into the cloned project directory and type the following command:
```
$ python3 train_mask_detector.py --dataset dataset
```
  
2. To detect face masks in real-time video streams type the following command:
```
$ python3 detect_mask_video.py
```
  
3. To detect face masks in an image type the following command:
```
$ python detect_mask_image --image /path_to_file
```
  
### :key: Results
  
### We got the following accuracy/loss training curve plot
<p align ="center"><img src="https://github.com/zapup4lk/FaceMaskDetection/blob/main/plot.png">
