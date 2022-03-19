# 基于卷积神经网络的高斯朴素贝叶斯分类人脸表情识别
## 项目简介

用搭载**Keras**的**tensorflow**框架通过**卷积神经网络**训练模型，使用**高斯朴素贝叶斯分类器**识别人类的情绪。根据情绪选择相应的emoji匹配

## 项目环境

>**数据集：** Fer2013 ( kaggle挑战赛 ) ，Emoji表情集  
**神经网络框架：** Keras,Tensorflow-gpu  
**分类器：** 基于Opencv-Normal Bayes Classifier(正态贝叶斯分类)训练的贝叶斯分类器  
**python环境：** python==3.6.0 tensorflow-gpu==**1.8.0** keras-gpu==2.1.6 opencv==3.3.1

详见**environment.yaml**

环境安装：

https://blog.csdn.net/sinat_28442665/article/details/86650152


## 总流程：

+ 对训练集预处理（fer2013_process)



+ 然后用处理好的fer2013的数据集训练深度卷积神经网络构建的模型识别人脸表情(train)



+ 使用训练好的模型识别人脸的表情情绪(predict)



+ 根据识别结果，匹配合适的emoji遮住人脸


## 参考：
+ https://blog.csdn.net/qq_42995327/article/details/114548137
+ https://blog.csdn.net/zhaocj/article/details/50615049
+ https://github.com/zhouzaihang/FaceEmotionClassifie
+ https://blog.csdn.net/u013841196/article/details/84262196
+ https://blog.csdn.net/GUET_DM_LQ/article/details/103765163
+ https://www.jianshu.com/p/399e5a3c7cc5
+ https://www.jianshu.com/p/1ea2949c0056
