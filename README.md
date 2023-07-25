# Image-classification
**Image Classification using fastai and pytorch**

**About fastai**

fastai is a powerful deep learning library that offers high-level components for achieving state-of-the-art results in standard deep learning domains, making it accessible to practitioners, and also provides low-level components for researchers to experiment and develop new approaches. It excels in providing a seamless experience without compromising on ease of use, flexibility, or performance. This is made possible by its carefully layered architecture, which encapsulates common underlying patterns of various deep learning and data processing techniques through decoupled abstractions. These abstractions are expressed concisely and clearly by leveraging the dynamism of Python and the flexibility of the PyTorch library.

**Overview**

This GitHub repository contains an image classification project using fastai. The goal of this project is to classify images into the following categories: 'buildings', 'forest', 'glacier', 'mountain', 'sea', and 'street'. The trained model is deployed with Flask, and it currently achieves an impressive accuracy of over 91% after 50 epochs.

**Dataset**

The model was trained on a dataset comprising images from various categories, namely 'buildings', 'forest', 'glacier', 'mountain', 'sea', and 'street'. The dataset was preprocessed and split into training and validation sets to facilitate the training process. The data augmentation techniques provided by fastai were utilized to enrich the dataset and improve the model's generalization capabilities.

**Model Architecture**

The architecture of the deep learning model used in this project is based on fastai's high-level components. It leverages the power of convolutional neural networks (CNNs) to automatically learn features from the input images. The model is built upon the PyTorch library, which allows for efficient computation and flexible model design. The model's hyperparameters have been fine-tuned to achieve optimal performance on the given dataset and I used the resnet18 model.

**Results**

The model has been trained for 50 epochs and currently achieves an impressive accuracy of more than 91% on the validation set. This level of accuracy demonstrates the effectiveness of fastai in simplifying the deep learning workflow while still delivering state-of-the-art results.

<img width="310" alt="image" src="https://github.com/Grunt-prog/Image-classification/assets/86661317/a090e490-8cb7-4efb-a5a9-93b7c25d7d0d">

<img width="311" alt="image" src="https://github.com/Grunt-prog/Image-classification/assets/86661317/330a38e4-0e3e-4fcb-b7e4-33e3de8098d5">

<img width="404" alt="image" src="https://github.com/Grunt-prog/Image-classification/assets/86661317/c332a938-80e9-4140-a6d9-11ae31a711f7">

<img width="266" alt="image" src="https://github.com/Grunt-prog/Image-classification/assets/86661317/56713e2f-e2c0-4f40-8d8b-f4cfcfbf204b">




