# Computer-Vision-Assignments | SBU CSE 527

## HomeWork 5 (Pix2Pix paper Implementation):
Implemented Pix2Pix Paper in PyTorch, cGAN Architecture was according to the paper (U-Net).

**Generator**:<br/>
**U-Net encoder**:<br/>
**C64-C128-C256-C512-C512-C512-C512-C512**<br/>
**U-Net Decoder**:<br/>
**CD512-CD1024-CD1024-C1024-C1024-C512-C256-C128**<br/>
**Discriminator**:<br/>
**C64−C128−C256−C512**<br/>

Trained the Generator with adversarial and L1 Loss. Got better results in fewer epcoh with Spectral Normalization.<br/>
Finally, Evaulted the model using Inception Score.<br/>

## HomeWork 1<br/>
Gaussian Noise, Salt and pepper Noise<br/>
Gaussian convolution Kernel<br/>
Median Filter<br/>
Laplacian of Gaussian(LoG)<br/>
Histogram equalization <br/>

## HomeWork 2<br/>
Match transformed images using SURF features<br/>
Scene stitching with SURF features<br/>
Object Recognition with HOG features<br/>

## HomeWork 3<br/>
Problems on Camera Tranformation<br/>
Tiny Image Representation + Nearest Neighbor Classifier<br/>
Bag of SURF Representation + Nearest Neighbor Classifer<br/>
Bag of SURF Representation + one-vs-all SVMs<br/>

## HomeWork 4 (PyTorch)<br/>
Training a Network From Scratch<br/>
Data Augmentation, Data Normalization, Network Regularization<br/>
Fine Tuning a Pre-Trained Deep Network(AlexNet and VGG16)<br/>


