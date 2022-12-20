# Traffic-Sign-Classification
With the rise of advanced driver assistance systems (ADAS)
and self-driving vehicles, the need for computer vision to
quickly detect and classify traffic signs has increased. There
are several challenges in processing traffic sign images including
blurring, warping, and full or partial obstruction.
Haloi (2015) proposed a convolutional neural network (CNN)
model for classification of the German Traffic Sign Recognition
Benchmark (GTSRB) dataset [1]. For our project, we
have reconstructed Haloi’s model as a baseline, improved the
baseline model performance by adding Bayesian inference,
and implemented the following five transfer learning models
for comparison: VGG16, ResNet50, GoogleNet(inceptionV3),
MobileNet, EfficientNet, and Vision Transformer. We compared
the test accuracy for all these models with hyperparameters
tuning via Bayesian optimization and some without
tuning on both the full test dataset and a subset of 50 blurry
images from the test dataset.
