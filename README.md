## DcGAN人脸修复
My individual project as a B.S student in Tongji University.
### Deep learning for image inpainting
### Environment
* Tensorflow 1.0.0
* Cuda 8.0
* Cudnn 5.1
* python 2.7
* Openface
* Scipy
* Pillow
* Numpy
* OpenCv
* Dlib

### Flow chart  
![](https://i.imgur.com/etRDMTD.png)

### Dataset
* CelebA: 10177 people’s 20599 face images, for face images training
![](https://i.imgur.com/yxEqA2B.png)
* LFW: 5000 people’s 10000+ face images, for face image testing
![](https://i.imgur.com/wH8O20z.png)
* Oxford Building: 5062 buildings, in which 1024 as testset, others are trainset
![](https://i.imgur.com/70YdYo6.png)
* INRIA: 1491 images of different kind, in which 496 as testset, others are trainset
![](https://i.imgur.com/jwFweos.png)

### Assessment Value
Use the following values to compare the similarity of original images and completed images, which can tell the performance of repairing.

* MSE(Mean Square Error)
* PSNR(Peak signal-to-noise ratio)
* SSIM(Structural Similarity)

### Some test results on LFW
![](https://i.imgur.com/oc21e7G.jpg)

![](https://i.imgur.com/pnGEeKt.png)

### Some test results on nature images (INRIA and Oxford Buildings)

![](https://i.imgur.com/SmssiwM.jpg)
![](https://i.imgur.com/VvWtozb.png)

### Different damaged area
* different damaged type
![](https://i.imgur.com/jF2flge.png)
![](https://i.imgur.com/akUnSTu.png)

* different damaged size
![](https://i.imgur.com/3ybAwFZ.png) 

* And so on...

### Expections
Here are some expections during my master career at King's College London

* optimise model
![](https://i.imgur.com/G0GgW5G.png)
* build an API and deploy online
![](https://i.imgur.com/WizfHxN.png)