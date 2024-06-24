# Bird or Not: Image Classification Model

## Overview
This repository contains a machine learning model that identifies whether an image consists of a bird. The model is built using the Fastai library and trained on images obtained from an online search.

## Getting Started
### Prerequisites
To run this project, you need to have the following libraries installed:
- `fastai`
- `pathlib`
- `time`
- `fastdownload`
- `duckduckgo_search`
- `fastcore`

### Downloading Images
The script downloads images for two categories: 'forest' and 'bird'. The images are obtained using the DuckDuckGo search engine. Each category is further divided into three sub-categories: photo, sun photo, and shade photo.

### Running the Script
The main script performs the following tasks:

1. Searches and downloads images for the specified categories.
2. Resizes the downloaded images.
3. Verifies the downloaded images and removes any failed ones.
4. Prepares the data for training using Fastai's DataBlock.
5. Creates and fine-tunes an image classification model using a ResNet18 architecture.
6. Makes a prediction on a new image to determine if it contains a bird.

### Example Usage
1. #### Clone the repository:
   ``` bash
   git clone https://github.com/joel0611/is-it-a-bird.git
   cd is-it-a-bird
   ```
2. #### Run the script:
   ``` bash
   python classify.py
   ```
3. #### Make a prediction on a new image:
The script includes an example of how to make a prediction on a new image. The example searches for a 'forest photo', downloads it, and then uses the trained model to predict if the image contains a bird.

## Contributing
If you would like to contribute to this project, please open an issue or submit a pull request.
   
