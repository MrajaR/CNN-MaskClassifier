# Mask Detection Classification with CNN and TensorFlow

## Description

Mask Detection Classification with CNN and TensorFlow is a computer vision application that addresses the critical problem of mask detection in images. Leveraging the power of Convolutional Neural Networks (CNNs) implemented with TensorFlow, this project classifies whether a person is wearing a mask or not. Two versions of the model are available: one using transfer learning and the other without.

## Dataset

The project utilizes a comprehensive dataset from Kaggle, consisting of 11,792 images of individuals wearing masks and not wearing masks. The dataset is thoughtfully divided into three sets: 10,000 images for training, 800 images for validation, and 992 images for testing. Each image is labeled appropriately for supervised learning. The dataset can be accessed here: [Face Mask 12k Images Dataset](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset).

## Image Augmentation

To enhance the model's ability to generalize, the project employs the ImageDataGenerator API provided by TensorFlow for image augmentation. Data augmentation techniques, such as rotation, zooming, and horizontal flipping, are applied during training to create additional variations of the original images. This approach enriches the dataset and enables the model to perform better on unseen data.

## Features

- **TensorFlow and CNNs:** The project utilizes TensorFlow, a leading deep learning library, along with Convolutional Neural Networks to build a robust image classification model.

- **Image Data Augmentation:** ImageDataGenerator API is leveraged to perform image augmentation during training, enhancing the model's ability to generalize to new data.

- **Transfer Learning with InceptionV3:** Transfer learning is implemented using pre-trained InceptionV3 models. This approach accelerates training and improves the model's performance significantly.

- **Keras API:** For streamlined and efficient model construction, the project utilizes the Keras API, making it easy to build, train, and evaluate the CNN model.

## How to Use the Project

To use and experiment with the project, follow these steps:

1. Clone this repository to your local machine.

2. Download the Face Mask 12k Images Dataset from Kaggle using the provided link.

3. Set up the required dependencies, including TensorFlow and Keras, by following the instructions in the project's README file.

4. Run the notebook or script to train the model on the masked and unmasked images.

5. After training, you can test the model's performance on the validation and test sets, and even try it with your own images.

## Contribution and Future Enhancements

Contributions to this project are most welcome! If you find any bugs, or have ideas to enhance the model or its performance, feel free to create a pull request or open an issue.

In the future, I plan to explore additional techniques, such as fine-tuning other pre-trained models, and incorporating real-time mask detection using webcam feeds.

## Acknowledgments

I want to express my appreciation to the Kaggle community for providing the Face Mask 12k Images Dataset, which played a crucial role in the success of this project.

Thank you for visiting my GitHub portfolio and exploring this project! I hope you find it informative and valuable.
