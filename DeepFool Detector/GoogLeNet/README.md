In [DeepFool project](https://github.com/LTS4/deepfool), authors of the paper [《DeepFool: a simple and accurate method to fool deep neural networks》](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Moosavi-Dezfooli_DeepFool_A_Simple_CVPR_2016_paper.pdf) remove model's final softmax layer to craft adversarial examples.<br> 
<br> We adopt the same softmax-absent model to craft effectual adversarial examples. File deploy_removeSoftmax.prototxt is the GoogLeNet model without the final softmax layer. However, it is not practical to modify the target model in the wild. Thus, for classifying as well as detecting an image, we use the original model (deploy_original.prototxt).