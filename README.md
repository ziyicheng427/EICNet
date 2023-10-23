# Deep Learning-Based Image Compression

## Introduction

In the age of big data, images have become indispensable. They play a pivotal role, and as data volumes surge, the significance of image compression technology becomes increasingly clear. Image compression significantly boosts the efficiency of image processing, transmission, and storage, leading to a more efficient and high-quality user experience.

Traditionally, image compression methods have encountered limitations during the century-long development of this field. To overcome these challenges, researchers have begun exploring innovative approaches, capitalizing on the rise and evolution of deep learning techniques. Deep learning-based image compression algorithms have recently outperformed traditional methods, both in objective metrics and subjective image quality.

However, deep learning-based image compression approaches still grapple with certain drawbacks, including:

1. **Insufficient Attention to Key Features** 
2. **Imperfect Probabilistic Models** 
3. **Low Image Quality after Compression and Reconstruction** 
4. **Decoding Latency** 

In summary, this project introduces several key innovations to address the challenges in deep learning-based end-to-end image compression:

- The *Fast Deep Residual Attention Module*.
- The *Mixture of Gaussian Models*.
- The *Post-Processing Module*.
- The *Chessboard Context Model*.

Our research indicates that, on average, at a BPP (Bits Per Pixel) of 0.15:

- The *Fast Deep Residual Attention Module* improves PSNR by approximately 0.23 dB.
- The *Mixture of Gaussian Models* contributes an improvement of 0.25 dB.
- The *Post-Processing Module* enhances image quality by approximately 0.13 dB.
- The combined effects of these innovations lead to an overall improvement of around 0.37 dB.

Additionally, the introduction of the *Chessboard Context Model* significantly reduces decoding time, making the image compression process more efficient.

This project collectively addresses these challenges and aims to enhance deep learning-based image compression techniques for a more effective and high-quality image processing experience.
