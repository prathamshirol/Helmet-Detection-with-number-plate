# Helmet Detection with Number Plate Recognition using YOLOv8

## Overview
This project aims to detect helmets and recognize number plates in images using the YOLOv8 model. The dataset was custom-made and annotated using Roboflow. The model was trained and evaluated using Google Colab.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Training and Prediction in Google Colab](#training-and-prediction-in-google-colab)
- [Results](#results)
- [Contributing](#contributing)


## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/helmet-detection-number-plate.git
    cd helmet-detection-number-plate
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset
The dataset was created and annotated using [Roboflow]([https://roboflow.com/](https://app.roboflow.com/eis-ysd6a/number-plate-detection-hawvj/annotate)). The annotations are in YOLO format. 

## Training and Prediction in Google Colab
We use Google Colab to train the YOLOv8 model and perform predictions. Follow these steps:

1. Open the [Google Colab notebook](https://colab.research.google.com/drive/1pDlOVrn_GWY0irTwu4EvGF4P9sUReeUR#scrollTo=b7ONaFLRVIUl) 

2. Follow the instructions in the notebook to upload the dataset, install necessary libraries, and run the training and prediction code.

3. The notebook will guide you through:
    - Setting up the environment
    - Downloading and preparing the dataset
    - Training the YOLOv8 model
    - Making predictions on test images

## Results
![image](https://github.com/prathamshirol/Helmet-Detection-with-number-plate-using-yolov8-deep-learning-model/assets/105107078/e8b3e8df-d39d-4242-89a1-e082e9caf404)
![image](https://github.com/prathamshirol/Helmet-Detection-with-number-plate-using-yolov8-deep-learning-model/assets/105107078/6ced513c-59a7-41d1-b5b9-a0363a83f474)


## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue to discuss what you would like to change.

