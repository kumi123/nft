# 图像风格迁移
基于吴恩达在 Coursera 上《深度学习》课程讲义实现图像风格迁移。

## 依赖

- [NumPy](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)
- [Tensorflow](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [Keras](https://keras.io/#installation)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/)

## 用法

下载预训练的 VGG19 [模型](https://github.com/foamliu/Neural-Style-Transfer/releases/download/v1.0/imagenet-vgg-verydeep-19.mat)放入 pretrained-model 目录，然后执行：

```bash
$ python demo.py
```

### 内容图片
![image](https://github.com/foamliu/Neural-Style-Transfer/raw/master/images/content.jpg)

### 风格图片
![image](https://github.com/foamliu/Neural-Style-Transfer/raw/master/images/style.jpg)

### 合成图片
![image](https://github.com/foamliu/Neural-Style-Transfer/raw/master/images/output.png)