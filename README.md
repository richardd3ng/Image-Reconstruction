# Image Reconstruction

This Image Reconstruction project explores the process of recovering digital images that contain missing or corrupted pixels using statistical learning approaches such as  regression and regularization. The general approach taken is to divide the corrupted image into blocks, then reconstruct each individual block, and finally concatenate all reconstructed blocks back into a full image. The reconstruction algorithm involves fitting a Lasso-regularized model with Discrete Cosine Transform (DCT) basis vectors as features. Due to the relative sparcity of DCT coefficients in naturally-occuring images, Lasso regularization can effectively to drive model coefficients to zero before predicting missing pixel values from existing neighboring values.

![image](https://github.com/richardd3ng/Image-Reconstruction/assets/73263775/8aa75426-6913-4927-9220-5fe96e482530)

