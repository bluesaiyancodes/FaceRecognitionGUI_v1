# Face Recognition ft _WxPython_
I have used the image reconition that i learned from Coursera - Convolutional Networks and a Wxpython interface to make it more intuitive.
In this model of face recognition inception network model is used. The network architecture follows the Inception model from [Szegedy *et al.*](https://arxiv.org/abs/1409.4842). 
This face recogntion is also inspired from from [FaceNet](https://arxiv.org/pdf/1503.03832.pdf)

I have added a interface using WxPython. 

<img src="images/img1.png">

* For testing or training new images you need a 96x96 image
* I have used [Autocrop](https://pypi.org/project/autocrop/). It automatically identifies face in an image and crops it to custom size.I have used it in the Notebook (ln 11). 
  * in order to use it,
    * First place image that you want to 
