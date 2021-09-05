# Cancer Cell Prediction using Deep Learning
Data presented as RGB images of T1-T6 cancer cells and their respective counts. 

# Dataset
Contact me on brand.spiteri@gmail.com for the dataset file.

# Feature Engineering
Images are transformed to HED space for better visualisation of cancer cells. 

# Regression Approach
A reduced PCA reprensation and its mean and variance for the RGB and HED space images is extracted as new features. 
Other features include equalising the input images.

Models trained:
1. Ordinary Least Squares (OLS) regression
2. Multilayer Perceptron (in Keras)
3. Support Vector Regression

# Convolution Neural Network
A CNN is trained to learn:
1. The convolved filter to identify the repsective T1-T6 cancer cells, and
2. The regressor at the NN's output

A ResNet50 CNN pre-trained model is also used for prediction. 



