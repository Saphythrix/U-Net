# U-Net
This project implements the U-Net architecture, a convolutional neural network designed for image segmentation tasks. U-Net follows an encoder–decoder structure where the contracting path captures contextual information, and the expansive path enables precise localization through upsampling.

The architecture leverages skip connections to combine low-level spatial features with high-level semantic information, improving segmentation accuracy. This project demonstrates the complete pipeline including data preprocessing, model building, training, and evaluation.

It is particularly useful for applications such as medical image segmentation, object boundary detection, and pixel-wise classification tasks.

References

- Olaf Ronneberger, Philipp Fischer, Thomas Brox  
  *U-Net: Convolutional Networks for Biomedical Image Segmentation*  
https://arxiv.org/abs/1505.04597
