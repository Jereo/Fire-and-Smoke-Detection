# Fire-and-Smoke-Detection
基于视频的烟火检测

首先,对图像进行预处理：

1.对图像分块，将图像分为24*24的小块

2.对每块图像进行运动检测及颜色检测

然后,使用训练好的神经网络对图像进行分类
（计划使用3D卷积神经网络来对烟火进行特征提取识别。
  在Facebook的C3D基础上进行修改。）
  
 # 请移步新的烟雾检测方法：
 
 https://github.com/xjg0124/Video_Smoke_Detection
