# tensorflow-lite-cpp
TFLite build and test

* Host: x86 Ubuntu 20.04

Download bazel from https://github.com/bazelbuild/bazel/releases?q=4.2.1

Copy and rename the download file to /usr/bin/bazel

Download tensorflow from https://github.com/tensorflow/tensorflow/releases/tag/v2.8.4

Remove the content from tflite folder in this repository and replace it with the following.

Create include/ and libs/

Put the following in include/

3rdparty/flatbuffers, tensorflow/lite, tensorflow/core