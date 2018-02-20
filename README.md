# jetson-inference-gv
modified files for jetson-inference-gv

The files in this folder have been copied from ross-abaco (https://github.com/Abaco-Systems/jetson-inference-gv) and updated according to dusty-nv as described in his changelog (https://github.com/dusty-nv/jetson-inference/commit/e40bd6abe9f07992f65dffeaa19e4d32eef78778).

These updates were necessary for the jetson-inference-gv (which also supports GigE-cameras) to work with Jetpack 3.1 and RensorRT2.

In gstCamera.cpp the path of the include for helper_math.h has been changed from cuda-8.0 to cuda-9.0.
In imagenet-camera.cpp an include for iostream has been added.
