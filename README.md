# Image Reconstruction

This Image Reconstruction project explores the process of recovering digital images that contain missing or corrupted pixels using statistical learning approaches such as  regression and regularization. The general approach taken is to divide the corrupted image into blocks, then reconstruct each individual block, and finally concatenate all reconstructed blocks back into a full image. The reconstruction algorithm involves fitting a Lasso-regularized model with Discrete Cosine Transform (DCT) basis vectors as features. Due to the relative sparcity of DCT coefficients in naturally-occuring images, Lasso regularization can effectively to drive model coefficients to zero before predicting missing pixel values from existing neighboring values.

![image](https://github.com/richardd3ng/Image-Reconstruction/assets/73263775/b4d7930f-6783-4280-aeb1-1924f1035e73)
![image](https://github.com/richardd3ng/Image-Reconstruction/assets/73263775/e644337e-c4d8-44b9-9f7a-37fe4ddeb0e3)
![image](https://github.com/richardd3ng/Image-Reconstruction/assets/73263775/b0dd65ea-acff-454a-bb7a-73ebb4484c12)

