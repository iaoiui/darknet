![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Darknet #
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

# Quickstart

Clone this repository

```
git clone https://github.com/iaoiui/darknet
cd darknet
```

Install dependencies

```
wget https://pjreddie.com/media/files/yolov3-tiny.weights

python3 -m venv .env
source .env/bin/activate
pip install -r requirements.txt

make
```

Launch 

```
python python/darknet.py
```