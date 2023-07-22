**Mask Detection Classification with CNN and TensorFlow**

**Description**: 
This project is a computer vision application that addresses the problem of mask detection in images. It utilizes Convolutional Neural Networks (CNNs) implemented with TensorFlow, a powerful deep learning library, to classify whether a person is wearing a mask or not. There are two versions of this, mask detection using transfer-learning method and non transfer-learning

**Dataset**: 
The project utilizes a dataset from Kaggle, consisting of 11,792 images of individuals wearing masks and not wearing masks. The dataset is split into three sets: 10,000 images for training, 800 images for validation, and 992 images for testing. Each image is labeled accordingly for supervised learning. you can look for the dataset here https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset

**Image Augmentation**: 
To enhance the model's ability to generalize, the project leverages the ImageDataGenerator API provided by TensorFlow for image augmentation. Data augmentation techniques, such as rotation, zooming, and horizontal flipping, are applied during training to create additional variations of the original images.

**Features**:

- Uses TensorFlow and CNNs to build a robust image classification model.
- Employs image data augmentation techniques to enhance model generalization.
- Implements transfer learning with pre-trained InceptionV3 models for better performance.
- Utilizes Keras API for simple and efficient model construction.
