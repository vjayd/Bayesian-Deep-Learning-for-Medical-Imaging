# Bayesian-Deep-Learning-for-Medical-Imaging
This repository contains the detailed overview of the proposed Bayesian deep learning algorithm for Image registration.

If you think if you can improve upon this approach please cite our paper:
@InProceedings{10.1007/978-3-030-34872-4_5,
author="Deshpande, Vijay S.
and Bhatt, Jignesh S.",
editor="Deka, Bhabesh
and Maji, Pradipta
and Mitra, Sushmita
and Bhattacharyya, Dhruba Kumar
and Bora, Prabin Kumar
and Pal, Sankar Kumar",
title="Bayesian Deep Learning for Deformable Medical Image Registration",
booktitle="Pattern Recognition and Machine Intelligence",
year="2019",
publisher="Springer International Publishing",
address="Cham",
pages="41--49",
abstract="Deformable image registration is one of the challenging inverse problems in medical images due to inevitable geometric distortions during the imaging. Conventional convolutional neural networks (CNNs) are limited to the fixed weights, and require substantial examples for supervised training. In this paper, we employ Bayesian deep learning in order to register the medical images that are corrupted by nonlinear geometric distortions. Given a pair of reference and moving image, our objective is to register the moving image onto the reference image coordinates while maintaining the pixel distribution of moving image. To this end, we propose a novel Bayesian deep architecture that contains 5 downsampling and 4 upsampling layers with kernel size of 3 {\$}{\$}{\backslash}times {\$}{\$} 3 interleaved by pooling layer with tanh and rectified linear units (ReLU) as activation functions. The architecture estimates the displacement vector field (DVF) of the moving image. Finally, it undergoes the grid resampling to warp the moving image using estimated DVF. We demonstrate that the proposed Bayesian deep architecture learns the probability distribution over the weights and produce accurate registration. Experiments are performed on the publicly available Cardiac MRI and Lungs CT scan datasets. The proposed model achieves better performance when compared to state-of-the-art approaches.",
isbn="978-3-030-34872-4"
}

