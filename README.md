# Transfer Learning with EfficientNet B0 on Food101 Dataset

In this project, i show example of transfer learning with EfficientNet B0 in PyTorch to classify images from the Food101 dataset. The Food101 dataset contains 101,000 images of 101 different types of food.

I start by loading the pre-trained EfficientNet B0 model, which was trained on ImageNet, than replace the last fully connected layer with a new layer that has the same number of output classes as the Food101 dataset. 
We tThen freeze the parameters of all layers except the new layer, and train the model on the Food101 dataset.

All code is contained in TransferLearningFoodClassificationWithFood101.ipynb file. I recomend opening file with google colab since it is made in it and comments are better displayed.

