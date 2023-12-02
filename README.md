# Face Detection Neural Network using TensorFlow Notebooks

This repository contains a collection of Jupyter notebooks demonstrating face detection techniques implemented using TensorFlow.
You can train the model on your data too by keeping files in a folder structure which will be described below

## Table of Contents

1. [Introduction](#introduction)
2. [Notebooks](#notebooks)
3. [Requirements](#requirements)
4. [Usage](#usage)
5. [Folder Structure](#folder)

## Introduction

Face detection is critical in computer vision, enabling applications like facial recognition, emotion analysis, and more. These notebooks explore different approaches and models for detecting faces in images using TensorFlow.

Pretrained weights at: [https://drive.google.com/drive/folders/1_AxpfdjK2TYvuh5MpR10x8c9gfhZ1efu?usp=share_link]

## Notebooks

### 1. data_collection.ipynb
- Description: This notebook can be used to collect data.
- Topics Covered:
  - Data collection techniques
  - Data labeling
  - Data preprocessing techniques

### 2. model.ipynb
- Description: This notebook is used to train model and sabe the wieghts.
- Topics Covered:
  - Transfer learning for face detection
  - Fine-tuning model

### 3. video.ipynb
- Description: Test model here.
- Topics Covered:
  - Face detection
  - Real-time face detection using video streams

### How to Use the Notebooks
- Each notebook contains detailed instructions within itself for execution.
- Ensure necessary libraries and dependencies are installed as per the provided requirements.

## Requirements

- Python 3.x
- TensorFlow
- OpenCv Python
- labelme
- Jupyter Notebooks
- matplotlib
- numpy

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/itmaybehimm/face-detection.git

2. Navigate to the cloned directory:
   
   ```bash
    cd face-detection
   
3. Open and run the notebooks using Jupyter Notebook or JupyterLab:
   
  ```bash
    jupyter lab
  ```

4. Follow the instructions within each notebook for execution and experimentation.


## Folder

- 📁 face-detection
  - 📔 Notebook_1.ipynb
  - 📔 Notebook_2.ipynb
  - 📔 Notebook_3.ipynb

  - 📁 data
    - 📂 images
    - 📂 labeled_images
    - 📂 unlabeld_images
    - 📂 labels
   
    - 📂 test
      - 📂 images
      - 📂 labels
        
    - 📂 train
      - 📂 images
      - 📂 labels
        
    - 📂 validation
      - 📂 images
      - 📂 labels

  - 🧠 trained_model_1.h5
  - 📄 README.md
