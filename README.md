# Bounding-Box-Model
This notebook explains how to generage a bounding box model.
While many of the whale pictures in the dataset are already cropped tight around the whale fluke, in some images the whale fluke occupies only a small area of the picture. Zooming in the relevant part of the picture provides greater accuracy to a classification model. To automate the process, this notebook explains how to construct a convolutional neural network (CNN) capable of estimating the whale bounding box.
Using this model, whale pictures can be cropped automatically to a more uniform appearance. This facilitates training of classification models, and improves the test accuracy.
Training of the bounding box model is performed over a dataset of 1200 bounding boxes for pictures selected from the Humpback Whale Identification Challenge training set. 1000 pictures are used for training, while 200 are reserved for validation.

