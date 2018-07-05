# Single Image Super-Resolution
This project aims at improving the resolution of an image using Single Image Super Resolution (SISR) techniques. 
SISR works by either exploiting the internal similarities of the same image or by learning the correspondences between low-resolution(LR) and high-resolution(HR) patches from external exemplar pairs.

Deep CNN models exploit the relationship between LR and HR patches better than other traditional approaches like neighbor embedding or sparse coding methods. Residual learning increases the convergence rate. 

Implemented a deep residual network with skip connections to improve the performance of predicting HR details of an image. Our model performed better than the state-of-the-art SISR models.

Tools used: Python, Numpy, Tensorflow, Caffe, Matlab, Matcaffe
