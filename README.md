# Flowers_Classification
 Vision computing for flowers, using Tensorflow

## Preprocess

In this dataset, the color is really important, so i have rescale all the images to 160x160x3. Also i have applied some data augmentation to reduce overfitting and get a better accuracy and lossy. 

## Model

For this project i wanted to use transfer learning from `MobileNetV2`, and also `fine tunning` it to this dataset so i have added some layers in order to improve it for this dataset

## Results

80% of accuracy in tests