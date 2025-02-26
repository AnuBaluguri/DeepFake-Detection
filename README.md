# DeepFake Detection

## Overview

DeepFake Detection is a machine learning project designed to detect and classify deepfake videos. It leverages deep learning models such as CNN+LSTM and XceptionNet to analyze video frames and identify manipulated content.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Video Preprocessing**: Extracts frames from videos for model input.
- **Deep Learning Models**:
  - CNN+LSTM for temporal video analysis.
  - XceptionNet for image classification on extracted frames.
- **Dataset Handling**: Supports processing and augmentation of video datasets.
- **Evaluation and Analysis**: Provides performance metrics and insights.

## Installation

To set up the project on your local machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AnuBaluguri/DeepFake-Detection.git
   cd DeepFake-Detection
   
2. **Set Up a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
3. **Install Dependencies**
     ```bash
     pip install numpy pandas opencv-python tensorflow keras matplotlib
# Usage
1. **Run Jupyter Notebook**
     ```bash
     jupyter notebook
2. **Open and Execute a Notebook**
   
     •  **Preprocessing Video Data**
     ```bash
     python
     
     # Run the PreprocessingForVideos.ipynb notebook to extract frames from videos
  •  **Train CNN+LSTM Model**
    ```bash
    python
    
    # Open CNN+LSTM.ipynb and run all cells to train the model
  •  **Train XceptionNet Model**
      ```bash
      python
    
      # Open XceptionNet.ipynb and execute to train the Xception-based model
    
# Project Structure
    ```bash
      DeepFake-Detection/
      │── PreprocessingForVideos.ipynb   # Preprocessing video data
      │── CNN+LSTM.ipynb                 # CNN+LSTM model implementation
      │── XceptionNet.ipynb              # XceptionNet model implementation
      │── Report.docx                     # Project report and findings
      │── README.md                       # Project documentation


# Dependencies

Ensure the following dependencies are installed:
•  Python 3.6+
•  NumPy
•  Pandas
•  OpenCV
•  TensorFlow / Keras
•  Matplotlib

# Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/new-feature
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
4. Push to your branch:
   ```bash
   git push origin feature/new-feature
5. Open a pull request.
