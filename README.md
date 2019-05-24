# ASC-SISR
Validation imges for ASC19 preliminary single image super resolution challenge

# Task

Single image super-resolution (SR), a very attractive research topic over the last two decades, is a highly challenging task that estimating a high-resolution (HR) image form its low-resolution (LR) counterpart. It has found practical applications in many real-world problems in different fields, from satellite and aerial imaging to medical image processing, to facial image analysis, text image analysis, sign and number plates reading, and biometrics recognition [1]. 

Nowadays, following the renaissance of deep learning, there is promising research on using deep convolutional neural networks (CNN) to perform super-resolution [2]. One of the ultimate goals in super-resolution is to produce outputs with high visual quality, as perceived by human observers. However, current state-of-the-art (SOTA) optimization-based super-resolution methods are largely focused on minimizing the mean squared reconstruction error and have high peak signal-to-noise ratios (PSNR), but they are often lacking high-frequency details and are perceptually unsatisfying in the sense that they fail to match the fidelity expected at the higher resolution [3]. In order to over this weakness, generative adversarial network (GAN) is introduced to SR[3] to encourage the network favor solutions that look more like natural images.

In this competition, the participant should design a deep learning model using SOTA strategies like CNN/GAN to do the 4x SR upscaling for images which were down-sampled with a bicubic kernel. The evaluation will be done in a perceptual-quality aware manner. The perceptual index (PI) defined in pirm2018 [4] will be used to calculate the quality of the reconstructed high-resolution images. Lower PI means higher quality of the reconstructed image. Ma and NIQE are two no-reference image quality measures [5-6].

# Dataset 

# Reference

[1]. K. Nasrollahi and T. B. Moeslund. Super-resolution: A comprehensive survey. In Machine Vision and Applications, volume 25, pages 1423–1468. 2014.

[2]. Johnson, Justin; Alahi, Alexandre; Fei-Fei, Li (2016-03-26). "Perceptual Losses for Real-Time Style Transfer and Super-Resolution". arXiv:1603.08155

[3]. Ledig, C., Theis,L., Huszar,F., Caballero,J., Cunningham,A.,Acosta,A., Aitken, A.P., Tejani, A., Totz, J., Wang, Z., et al.: Photo-realistic single image super- resolution using a generative adversarial network. In: Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. pp. 4681–4690 (2017)

[4]. https://www.pirm2018.org/PIRM-SR.html 

[5]. A. Mittal, R. Soundararajan and A. C. Bovik, "Making a “Completely Blind” Image Quality Analyzer," in IEEE Signal Processing Letters, vol. 20, no. 3, pp. 209-212, March 2013.

[6]. Ma C , Yang C Y , Yang X , et al. Learning a No-Reference Quality Metric for Single-Image Super-Resolution[J]. Computer Vision & Image Understanding, 2016.


