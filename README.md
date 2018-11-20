# Sign-Language-MNIST
Classification of sign language images using Convolutional neural networks using Keras and TensorFlow

I tried to classify Sign Language Gesture using Convolutional Neural Network. I got the data from kaggle https://www.kaggle.com/datamunge/sign-language-mnist.

### Data Overview
The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2....pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255.
