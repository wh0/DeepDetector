# DeepDetector
DeepDetector is a straightforward method for detecting adversarial image examples. The method can effectually detect adversarial examples crafted by [Fast Gradient Sign Method](https://arxiv.org/pdf/1412.6572.pdf), [DeepFool method](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Moosavi-Dezfooli_DeepFool_A_Simple_CVPR_2016_paper.pdf) and [attacks designed by Nicholas Carlini and David Wagner](https://arxiv.org/pdf/1608.04644.pdf). Adversarial examples crafted by other attack techniques may also can be detected by this method.<br>
<br>Details of the three attack techniques mentioned above and the corresponding implementations of this detection method can be found in each subdirectory, namely, FGSM Detector, DeepFool Detector and CW Detector.<br> 
<br>Subdirectory ImageNetImages contains four classes (Zebra, Panda, Cab and Pineapple) of images from ImageNet dataset, which are used for our experiments.<br>

# Reference
Liang B, Li H, Su M, et al. Detecting Adversarial Examples in Deep Networks with Adaptive Noise Reduction[J]. arXiv preprint arXiv:1705.08378, 2017.
