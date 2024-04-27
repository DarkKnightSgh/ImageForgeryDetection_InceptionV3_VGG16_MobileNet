**IMAGE FORGERY DETECTION USING InceptionV3,VGG16, MobileNetV2**


DATASET:
The Dataset used for training purposes is CASIA 2.0. It contains 12560 images, out of which 7437 are authentic and 5123 are forged or tampered. We have also created a dataset , consisting of 202 images, similar to the CASIA dataset in order to test the model. The domain chosen for generating the dataset is Wildlife. We have taken 101 Authentic Wildlife images and used the images to create 101 Tampered images by applying the Splicing method, using Photopea Software.

https://www.kaggle.com/datasets/divg07/casia-20-image-tampering-detection-dataset

METHODOLOGY:
The proposed methodology involves leveraging the power of CNN based architectures like InceptionV3, VGG16, and MobileNetV2 for Image Forgery Detection. Error Level Analysis (ELA) serves as an initial screening mechanism, offering insights into potential image tampering and manipulation.

RESULT:
Technique        -    Fusion Model (InceptionV3 + VGG16 + MobileNetV2)
Test Accuracy    -    85%
Test Loss        -    33.9%

The model is tested on a subset of the CASIA 2.0 Dataset, containing only images pertaining to Wildlife and Nature, as an experiment to understand whether it can be used for detecting forgery or tampering in Wildlife photography. The results are promising with the model performing very well with a test accuracy of 85%.
The Fusion Model uses transfer learning from three pre-trained CNN based models: InceptionV3 (GoogleNet), VGG16, and MobileNetV2. This has proved to be a powerful approach for leveraging the feature extraction capabilities of these models. Overall, the proposed methodology with deep feature fusion shows promise for image forgery detection based on the high validation and test accuracy.
