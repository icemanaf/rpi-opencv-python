# A rough and ready Docker image with Python 3.7 and OpenCV 4.51 for Raspberry Pis.

The images have been built on a Pi3, but the best performance is going to be on a PI4 with atleast 2GB of ram or more as the image size comes to around 438mb which is quite large by pi standards.

```
docker run -it icemanaf/rpi-opencv-python:0.1 /bin/sh
```