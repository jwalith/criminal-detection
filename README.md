# criminal-detection

The methodology depicted in the following is used for criminal detection
 Steps in COnvolution Neural Networks
1.Convolution
2.Max pooling
3.Flattening
4.Full Connection

# 1.Convolution
convolution is done to an image using feature dectector
when input image is convolveed with the feature detector then we get a feature map
by applying convolution operation size of the image is reduced so we may lose some information. but features detector is one which stores the features and unwanted features are removed.
WE will apply no of feature detectors(filter) to a single image so we will be getting nof features detectors. SO using no of feature detectors we get max no of features in an image so we will be getting no of feature maps
Group of feature map is called CONVOLUTION layer
# 2.MAX POOLING:
Types of pooling-Max pooling,Mean Pooling, Sum pooling  Max Pooling:By applyimg max pooling we ar neglecting 75% of unwanted features and we are reducing spacial invariance this will avoid over fitting of the data .

# 3. Flattening
flattening is converting n dimension to 1 dimension and applying ann to that 1 dimension array which just acts like inputs to the neurons.
When output is not correct then in the backward propogation along with the weights feature detector(filter) is also optimized.

# 4. Full Connection
Full connection is dense layers
This flatten layer taken as input layer to the Artificial Neural Networks and we give one hidden layer and output layer.
In compilation we use batch gradient descent and binary cross entropty as loss function. 
