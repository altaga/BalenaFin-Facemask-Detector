

All the information about the BalenaFin will be in this link:

https://www.balena.io/fin/

To train the model, a Notebook in Google Colab is used in order to facilitate the training of the model.

[LINK](https://colab.research.google.com/github/altaga/BalenaFin-Facemask-Detector/blob/main/Train/Balena_Train_Models.ipynb)

The operating system that was installed on the BalenaFin was Raspberry OS:

https://www.raspberrypi.org/downloads/raspberry-pi-os/

NOTE: The code was made to work with the raspberry's built-in camera.

To install the libraries except TFlite Interpreter:
    sudo apt-get install libatlas-base-dev python3-opencv

To install TFlite Interpreter:

    pip3 install https://dl.google.com/coral/python/tflite_runtime-2.1.0.post1-cp37-cp37m-linux_armv7l.whl

NOTE: the code for the training already contains the command to download the dataset on the Google Colab platform, however, here I leave you the two options to download the dataset.

- Github: [Link](https://github.com/altaga/BalenaFin-Facemask-Detector/tree/main/Train/facemask-dataset)
- Kaggle: [Link](https://www.kaggle.com/altaga/facemaskdataset)

Model running:

<kbd>
<img src="./Images/20201212_174315.jpg" width="600" />
</kbd>

# BalenaFin-Facemask-Detector

BalenaFin board-based face mask detector.

<img src="https://i.ibb.co/qRkPHDn/ezgif-com-gif-maker.gif" width="800">

# Table of contents

- [BalenaFin-Facemask-Detector](#balenafin-facemask-detector)
- [Table of contents](#table-of-contents)
  - [Introduction:](#introduction)
- [Materials:](#materials)
- [Diagram:](#diagram)
- [Training:](#training)
- [Testing:](#testing)
- [Demo:](#demo)
    - [1](#1)
    - [2](#2)
    - [3](#3)

## Introduction:

The Covid19 pandemic has been an event that has affected not only the life of each person, but the coexistence of people in all aspects of life and one of these aspects has clearly been the way in which all people coexist.

One of the main measures to combat the pandemic is use a face mask.

I want to create a EDGE face mask detector BalenaFin board-based.

<img src="https://i.ibb.co/5ndwL6K/drone.png" width="800">

# Materials:

List the hardware and software you will use to build this.

Hardware: 
- BalenaFin.
- USB Camera.

Software: 
- Python 3.8. 

Libraries:

- [OpenCV. ](https://opencv.org/)
- [TensorFlow Lite Interpreter. ](https://www.tensorflow.org/lite/guide/python)

# Diagram:

<img src="https://i.ibb.co/VjNvMp3/Esquema.png" width="1000">

# Training:

# Testing:



# Demo:

Video: Click on the image:

[![CoviDrone](https://i.ibb.co/5ndwL6K/drone.png)](https://youtu.be/0S2LLVwh60M)

Sorry github does not allow embed videos.

* [Table of contents](#table-of-contents)

Articles:

### 1
https://covid19.cdc.gov.sa/community-public/preventive-measures-in-workplaces/
### 2
https://tectales.com/bionics-robotics/9-disinfection-robots-fighting-the-coronavirus.html
### 3
https://www.researchgate.net/publication/339887436_2020_COVID-19_Coronavirus_Ultraviolet_Susceptibility
