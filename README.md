# IQA
使用opencv进行图像质量监测

本程序(detect_blur.py)实现了如何用 OpenCV、Python 和拉普拉斯算子来计算图片中的模糊量，并根据模糊量判断图片是否模糊

核心代码
cv2.Laplacian(image, cv2.CV_64F).var()

实现效果
![image](https://github.com/iAmBrid/IQA/image/readme/caopin.jpg)

