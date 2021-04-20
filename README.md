# DeepLab-v3-models-for-waste-material-recognition
This repository contains DeepLab v3+ models trained on over 5,000 construction waste images, and checkpoints pretrained on the MINC material dataset. A PASCAL VOC format annotation of the MINC dataset is also shared.

The below figure shows some photos in the construction waste dataset, and their corresponding segmentation results predicted by our models. The research is under consideration for publication by pear-review journals. We will update the publication information once it is available. 
![alt text](https://github.com/civilServant-666/DeepLab-v3-models-for-waste-material-recognition/blob/main/photos_and_segmentation.png "model results")

## In the "models" folder
In this folder, our optimal DeepLab v3+ model trained on construction waste images and the MINC material dataset is shared. In addition, two model checkpoints with the Xception and the ResNet backbones pretrained on the MINC are also presented. 

The following table shows detailed specifications of the models:
![alt text](https://github.com/civilServant-666/DeepLab-v3-models-for-waste-material-recognition/blob/main/Model_specification.png "model specification")
* The original DeepLab model backbone before training on our datasets can be found here:  https://github.com/tensorflow/models/blob/master/research/deeplab/g3doc/model_zoo.md

## In the "dataset" folder
We processed the annotation results given by the original MINC dataset, so as to generate Pascal VOC format segmentation annotation that can be used by the Deeplab v3+ training code. 

The folder only contains the annotation. To obtain the original images, please download from the official website of the MINC dataset: http://opensurfaces.cs.cornell.edu/publications/minc/


