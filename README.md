# Tensorflow-应用于验证码识别

深度学习框架Tensorflow的入门级学习，应用于验证码识别

根据b站视频https://www.bilibili.com/video/BV1UE411B7qK 已完成了实验01-08   

编程环境： Anaconda3  conda 4.8.3 python 3.6.13  tensorflow 1.14.0

视频1
# Tensorflow 基础介绍和安装

## Tensorflow介绍

TensorFlow 是一个端到端开源机器学习平台。它拥有一个全面而灵活的生态系统，其中包含各种工具、库和社区资源，可助力研究人员推动先进机器学习技术的发展，并使开发者能够轻松地构建和部署由机器学习提供支持的应用。

官网地址：https://www.tensorflow.org/



## 创建Tensorflow虚拟环境

安装虚拟环境的原因，参考这篇帖子的说法https://blog.csdn.net/zhanghai4155/article/details/104268737

![image-20210601114138084](C:\Users\26233\AppData\Roaming\Typora\typora-user-images\image-20210601114138084.png)

![conda env list](https://img-blog.csdn.net/20180520235206835?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L21yd3ho/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

## CPU版本安装

用pip命令安装

```
pip install tensorflow  #最新的稳定发行版本，2.0×后默认是CPU和GPU版本在一起，1.×只表示CPU版本
pip install tensorflow-gpu  #1.×的GPU版本
pip install tensorflow==1.14  # 1.×的最后一个更新版本，2019年发布
```

我使用的是第三条，安装CPU版本。这里安装tensorflow1版本。

选择tensorflow1.0的原因：1.0更适用于了解网络模型运行的机理、框架更稳定、可学习/使用的资料更丰富。

可以详细了解更多tensorflow1.0和2.0的区别：https://www.pianshen.com/article/92841995245/。
