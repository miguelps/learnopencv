To use code, please download:

1. [haarcascade_frontalface_alt2.xml](https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_frontalface_alt2.xml)
2. [lbfmodel.yaml](https://raw.githubusercontent.com/kurnianggoro/GSOC2017/master/data/lbfmodel.yaml)

Compile:

```shell
g++ -o facemarks facialLandmarkDetection.cpp -Wall -std=c++11 -O2 -DNDEBUG `pkg-config opencv --cflags --libs`
```