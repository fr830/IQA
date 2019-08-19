# IQA
使用opencv进行图像质量监测

本程序(detect_blur.py)实现了如何用 OpenCV、Python 和拉普拉斯算子来计算图片中的模糊量，并根据模糊量判断图片是否模糊

核心代码
cv2.Laplacian(image, cv2.CV_64F).var()

实现效果
清晰图片
<img src="https://github.com/iAmBrid/IQA/blob/master/image/readme/caopin.jpg">
<img src="https://github.com/iAmBrid/IQA/blob/master/image/readme/caopin2.jpg">
<img src="https://github.com/iAmBrid/IQA/blob/master/image/readme/lena.jpg" width='256' hegith='256'>
<img src="https://github.com/iAmBrid/IQA/blob/master/image/readme/lena2.jpg" width='256' hegith='256'>

模糊图片

![image](https://github.com/iAmBrid/IQA/blob/master/image/readme/person.jpg)
![image](https://github.com/iAmBrid/IQA/blob/master/image/readme/person2.jpg)

<img src="https://github.com/iAmBrid/IQA/blob/master/image/readme/run.jpg" width='250'>
<img src="https://github.com/iAmBrid/IQA/blob/master/image/readme/run2.jpg" width='250'>
