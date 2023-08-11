![Cover image](https://github.com/nileshparab42/Naruto-Vs-Sasuke-Image-Classifier/blob/main/assets/cover-image.png)

# Naruto Vs Sasuke Image Classifier(Using ResNet50)

The Naruto vs Sasuke Image Classifier using ResNet50 is a deep learning model that employs the ResNet50 architecture to distinguish and categorize images depicting the iconic battles between the characters Naruto and Sasuke from the popular anime series "Naruto." The classifier is trained to accurately identify and classify these specific character' from scenes.

## Bing Image Downloader for Creating Dataset

A "Bing Image Downloader" is a software tool or program designed to facilitate the downloading of images from the Bing search engine. Users can input keywords or search queries, and the downloader retrieves and saves images matching those criteria from the Bing image search results. This tool can be useful for collecting visual content for various purposes, such as creating presentations, designing projects, or building personal image collections. It simplifies the process of gathering images by automating the downloading process and providing a convenient way to access and save images from the Bing search engine.

## ResNet50 architecture 

![Cover image](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*rPktw9-nz-dy9CFcddMBdQ.jpeg)

The ResNet50 architecture is a deep convolutional neural network (CNN) architecture that was introduced as part of the "Deep Residual Learning for Image Recognition" paper by Kaiming He, Xiangyu Zhang, Shaoqing Ren, and Jian Sun in 2015. ResNet stands for "Residual Network," and it addresses the challenge of training very deep neural networks by introducing residual blocks.

Key features and concepts of the ResNet50 architecture include:

Deep Architecture: ResNet50 is a deep CNN with 50 layers, making it significantly deeper than earlier architectures like VGG16.

**Skip Connections (Residual Blocks):** ResNet introduces the concept of residual blocks, which allow information to "skip" layers. This is done by adding a shortcut connection (also known as a skip connection or identity mapping) that directly passes the input from one layer to a later layer in the network. This helps mitigate the vanishing gradient problem and enables the training of deeper networks.

**Convolutional Layers:** ResNet50 uses convolutional layers for feature extraction. Each residual block consists of multiple convolutional layers, which are responsible for learning and extracting hierarchical features from input images.

**Global Average Pooling (GAP):** Instead of using fully connected layers at the end of the network, ResNet50 employs global average pooling to reduce the spatial dimensions of the features while retaining their depth. This helps reduce the risk of overfitting and results in a more compact network.

**Pre-trained Models:** ResNet50 is often used as a pre-trained model for transfer learning. Pre-trained versions of ResNet50 have been trained on large datasets (e.g., ImageNet) and can be fine-tuned for specific tasks with smaller datasets.

**Architectural Variations:** ResNet50 is just one variant of the ResNet architecture. There are other versions with varying depths, such as ResNet18, ResNet34, ResNet101, ResNet152, and more, each with a different number of layers.

The ResNet50 architecture and its variations have had a significant impact on the field of computer vision and deep learning. They have been widely adopted and achieved state-of-the-art performance on various image recognition tasks, including object detection, image classification, and more.

![Cover image](https://github.com/nileshparab42/Naruto-Vs-Sasuke-Image-Classifier/blob/main/assets/graph.png)

**Model Summary**                                           
Total params: 23,688,065
Trainable params: 100,353
Non-trainable params: 23,587,712


### Optimizers Parameters

loss='binary_crossentropy'
optimizer='adam'
metrics=['accuracy']

## Contributing

We appreciate contributions from the community to enhance Sneaky. If you'd like to contribute, please follow these steps:

1. Fork the repository on GitHub.

2. Create a new branch from the "main" branch.

3. Make your desired changes and improvements in the code.

4. Test your changes thoroughly.

5. Create a pull request and provide a detailed description of the changes you made.

6. Our team will review your pull request, and if everything looks good, we'll merge it into the main repository.


## Installation

### Get the Naruto Vs Sasuke Image Classifier Repository now.

To download a Amadeus project, you can use the git clone command. This command creates a copy of the repository in a new directory on your local machine.
```
git clone https://github.com/nileshparab42/Car-Dekho-Selling-Price-Prediction.git
```
To set up the project, you can use the pip command to install the required packages specified in the requirements.txt file.
```
pip install -r requirements.txt
```
This will install all of the required packages for the project. If you are using a virtual environment for the project, you should activate the environment before running this command.
```
pip install virtualenv
virtualenv myenv
source myenv/bin/activate
pip install -r requirements.txt
```
This will create a new virtual environment called myenv, activate it, and then install the required packages.

You can also specify the notebook file location or the working directory, after the command "jupyter notebook" or "jupyter lab" like:
```
jupyter notebook /path/to/notebook/directory
```
or
```
jupyter lab /path/to/notebook/directory
```
It will open the Jupyter notebook or lab in the specified directory, making it easier to navigate to the notebook you want to open.


## Authors

- [Nilesh Parab](https://github.com/nileshparab42) (Project Lead) - [Website](https://nileshparab10.blogspot.com/)
  

## Acknowledgements

- This project was inspired by the work of the [CodeWthHarry](https://www.youtube.com/@CodeWithHarry).
- We also used resources and tools from the [GeeksforGeeks](https://www.geeksforgeeks.org/speech-recognition-in-python-using-google-speech-api/) to develop and test our project.