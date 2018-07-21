# 启动简介(setup)

### Python 依赖

- Keras (>2.0.0)
- Theano(>0.9) or Tensorflow(>1.1.x)
- Numpy (>1.10)
- Scipy (0.19.1)
- OpenCV(>3.0)
- Scikit-image (0.13.0)
- PIL

### conda建立运行环境并安装依赖
需要安装Anaconda
```shell
$ conda create -n HyperLPR python=2.7
$ conda install pillow
$ conda install scikit-image
$ conda install opencv=3.3
$ conda install tensorflow
$ conda install keras
```
### pip安装依赖
先安装python, pip
```shell
$ sudo apt-get install python
$ wget https://bootstrap.pypa.io/get-pip.py 
$ sudo python get-pip.py
```
再安装依赖

类似上面的安装命令
