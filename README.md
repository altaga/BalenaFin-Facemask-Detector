# BalenaFin-Facemask-Detector

All the information about the RPi4 will be in this link:

https://www.balena.io/fin/

To train the model, a Notebook in Google Colab is used in order to facilitate the training of the model.

PONER LINK

The operating system that was installed on the BalenaFin was Raspberry OS:

https://www.raspberrypi.org/downloads/raspberry-pi-os/

NOTE: The code was made to work with the raspberry's built-in camera.

To install the libraries except TFlite Interpreter:
    sudo apt-get install libatlas-base-dev python3-opencv

To install TFlite Interpreter:

    pip3 install https://dl.google.com/coral/python/tflite_runtime-2.1.0.post1-cp37-cp37m-linux_armv7l.whl

NOTE: the code for the training already contains the command to download the dataset on the Google Colab platform, however, here I leave you the two options to download the dataset.

- Github: PONER LINK
- Kaggle: https://www.kaggle.com/altaga/facemaskdataset

Model running:

<kbd>
<img src="https://i.ibb.co/6J7kty6/RPi-Opt-Model-2.jpg" width="600" />
</kbd>
