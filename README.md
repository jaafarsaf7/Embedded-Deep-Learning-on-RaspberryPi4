# Deep learning using Tensorflow Lite on Raspberry Pi

![alt text](https://github.com/jaafarsaf7/Embedded-Deep-Learning-on-RaspberryPi4/blob/main/IMG_1619.jpeg)


# About this Repository
Dive into Embedded Deep Learning using Python with Raspberry Pi 4. Here, we're building a unique Computer Vision project using custom data. Specifically:
- A calculator that processes images, forms equations, and provides results. It's crafted using a convolution network architecture, ideal for categorical classification.

- Learn about Post Quantization on TensorFlow models. The model is trained on Google Colab and is optimized — it's 3 times smaller with an inference speed of just 0.024 seconds per input.

**Note**: This repository is your guide, detailing each step of the project.


---
## Features
-
- **Real-Time Number Detection**
- **Visual Calculator Equation Solving**
- 
    - <img src="https://github.com/jaafarsaf7/Embedded-Deep-Learning-on-RaspberryPi4/blob/main/ezgif.com-video-to-gif.gif" width="1000" height="600">
    
---
## Installations
- Laptop/PC Installations
    - Rpi-Imager for installing RPI OS on SD CARD
        ```
        sudo apt install rpi-imager
        ```
    - Tensorflow
        ```
        pip install tensorflow
        ```

- Raspberry PI 4 installations
    - TensorFlow Lite Interpreter
        ```
        python3 -m pip install tflite-runtime
        ```
    - Install tightvnc server
        ```
        sudo apt-get install tightvncserver
        ```
- Common Installations
    - OPENCV
        ```
        pip3 install opencv-python
        sudo apt-get install libcblas-dev
        sudo apt-get install libhdf5-dev
        sudo apt-get install libhdf5-serial-dev
        sudo apt-get install libatlas-base-dev
        sudo apt-get install libjasper-dev
        sudo apt-get install libqtgui4
        sudo apt-get install libqt4-test
        sudo apt-get install libatlas-base-dev
        ```
    - Upgrade Numpy
        ```
        pip install -U numpy
        ```

----
## Using Repository
- Obtain the code using Git
    ```
    git clone --single-branch --branch Development https://github.com/jaafarsaf7/Embedded-Deep-Learning-on-RaspberryPi4.git
    ```
- SSH into your RPI
    ```
    ssh pi@<IP_of_RPI>
    ```
- Turn on the TightVNC Server to enable screen sharing
    ```
    tightvncserver :1
    ```
- Access RPI through VNC-Viwer on PC
---
## Pre-Course Requirments
- PC   : Ubuntu 22.04
- RPI4 : RPI Full OS
    - SD-CARD 16GB
    - RPI Camera V2
    - Power Bank with Type C cable
    - 3D printed Parts for Camera Holding
    - Fan on RPI for better thermals

----



  ## Jaafar Safar
