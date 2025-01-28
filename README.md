# Image segmentation using U-Net model with insight into learning process via _captum.ai_

This code written in Python for Google Colaboratory performs image segmentation with the U-Net model described in _https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28_.

An examplary dataset, containing 1000 classes with 10 images in each, was taken from _https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/fss1000-a-1000-class-fewshot-segmentation_.

_captum.ai_ utilities provide an insight into the learning process of the model; namely, they show which attributes (pixels) the model focuses on in order to make segmentation decisions.
