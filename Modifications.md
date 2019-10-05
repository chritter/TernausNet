

# STC

### Comments

* VGG11 for encoding
* 3 U-net model variants available: 
    * UNet11 (main setup)
        * VGG 11-layer model (configuration “A”) 
* Notes about loading pre-trained models from Torchvision
    * 3-channel RGB images as input,  need specialized normalization as in 
    https://pytorch.org/docs/stable/torchvision/models.html
* UNet11
    * Can load weights from training on https://www.kaggle.com/c/carvana-image-masking-challenge
    * by default network uses weights from pre-training on ImageNet
    


https://www.kaggle.com/c/carvana-image-masking-challenge