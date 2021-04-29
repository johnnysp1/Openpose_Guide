# Guide for using OpenPose: https://github.com/CMU-Perceptual-Computing-Lab/openpose<br>
Requirements:
Cuda 11.0<br>
Cudnn 8.0.5<br>
`sudo apt-get install essential-build cmake`<br>
other requirement will be installed in the following steps automatically<br>
Install prerequisites of Caffe:<br>
`sudo bash ./scripts/ubuntu/install_deps.sh`<br>
Install opencv:<br>
`sudo apt-get install libopencv-dev`<br>

OpenPose Configuration and Building:<br>
Configuration:<br>
`mkdir build`<br>
`cd build`<br>
`cmake ..`<br>

Building:<br>
`make`<br>

Demo (Terminal command can be found in /doc/01_demo.md):<br>
`./build/examples/openpose/openpose.bin --video examples/media/video.avi`<br>
