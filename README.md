# Image Caption Generation

This is a personal project I am working on, to help me expand my knowledge on: 
- feature extraction from images (CNN)
- Text preprocessing
- Vocabulary extraction
- Text Tokenization
- Sequence modeling (LSTM)
- Data generation

The idea of the project is to use a pretrained model Xception based on the CNN architecture in order to extract features from images.

Then we will use the LSTM for sequence modeling. LSTM will help us predict the next word to put on a caption based on the previous text hence predicting the caption.

The Data set I used is Called the Flicker_8k_dataset which contains 8000+ images with their descriptions.

###### Big thanks To Jason Brownlee for providing the Dataset.

The are Links to download the Datasets:
- [Flicker8k_dataset](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip): contains the images
- [Flicker_8k_text](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip): contains the description for each images

###### This personal project is inspired by [this Tutorial](https://data-flair.training/blogs/python-based-project-image-caption-generator-cnn/)

