# Keras-simple-face
## 简介
   我们利用keras来搭建CNN人脸识别网络模型。这里先采用最基本的卷积神经网络模型LeNet5模型，实现人脸识别任务。
我们采用的人脸数据库Olivetti Faces地址为https://cs.nyu.edu/~roweis/data/olivettifaces.gif。Olivetti Faces是纽约大学的一个比较小的人脸库，
由40个人的400张图片构成，即每个人的人脸图片为10张。每张图片的灰度级为8位，每个像素的灰度大小位于0-255之间，每张图片大小为64×64。
工程中图片的大小是1190*942，一共有20*20张人脸，故每张人脸大小是（1190/20）*（942/20）即57*47=2679。
## 使用方法
   训练模型的时候可以把已经屏蔽掉的训练模型语句和测试模型语句放出来。把后面的预言模型语句屏蔽掉。
等训练出h5模型之后，可以屏蔽掉训练和测试语句完成模型使用。模型可以直接在机器人上跑并得到应用。
    
