# birds_classification_with_ViT

This project is part of a data challenge that was introduced in the Image Recognition & Computer Vision (RecVis) MVA class. 

The project aims to classify a 20 classes birds dataset. The dataset is composed of 1082 training images, 103 validation and 517 test images.
I chose to explore the use of Vision Transformers (ViT) for this task. I fine-tuned a pretrained ViT model on our augmented dataset using a HuggingFace hosted ViT model that was pretrained on the large ImageNet-21k (14 million images, 21,843 classes). I also attempted to visualize and interpret self-attention on the last layer of the ViT model. Please refer to the assignment report for more details. 
