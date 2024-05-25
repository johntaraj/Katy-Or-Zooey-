# Katy Or Zooey?
Katy Perry or Zooey Deschanel detector

# DEMO
You can try the code in Huggging Face Spaces

Link: https://huggingface.co/spaces/xota1999/Katy_Perry_or_Zooey_Deschanel

![image](https://github.com/johntaraj/Katy-Perry-or-Zooey-Deschanel-detector/assets/134852121/6b523166-60be-4b07-8346-ba1315d5ce95)


# Image Search and Classification with DuckDuckGo and FastAI

## Project Overview

This project demonstrates how to leverage the DuckDuckGo search engine to gather images, create a dataset, and train an image classification model using the FastAI library. The example focuses on downloading images of celebrities and using these images to train a simple neural network for classification tasks.

## Features

- **Image Search**: Use DuckDuckGo to search and download images based on specified search terms.
- **Dataset Creation**: Organize downloaded images into a structured dataset.
- **Image Verification**: Verify the integrity of images and remove any corrupted files.
- **Model Training**: Train an image classification model using FastAI's high-level API.
- **Model Evaluation**: Test the model's performance on new images and save the trained model for future use.

## Installation

To get started, install the required dependencies:

```bash
pip install -U duckduckgo_search fastcore fastdownload fastai
```

## Usage

1. **Search and Download Images**:
   - Define search terms and download images using DuckDuckGo.
   - Save the images locally for dataset creation.

2. **Create Dataset**:
   - Organize the downloaded images into a dataset structure suitable for training.
   - Perform necessary image preprocessing and resizing.

3. **Train the Model**:
   - Use FastAI to create data loaders and define a convolutional neural network (CNN) model.
   - Train the model on the dataset and fine-tune it to improve performance.

4. **Evaluate the Model**:
   - Test the model on new images to assess its accuracy.
   - Save the trained model for deployment or further use.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
