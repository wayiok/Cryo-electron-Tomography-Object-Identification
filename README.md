# Directory Structure Documentation

## Overview
This document describes the structure and purpose of the directories and files in the project. Below is the hierarchical structure and explanation of each component.

## Project Structure

```text
2D U-NET APPROACH/
├── 1 - source data/
│   ├── 1 - original dataset/
│   ├── 2 - yolo dataset/
│   └── file4.txt
├── 2 - data processing code/
│   └── preprocessing notebook
└── 3 - training code/
    ├── models result of training/
    └── notebooks of training/

3D U-NET APPROACH/
└── notebooks of training/

REPORT
```

## Folder Descriptions

### 1. 2D U-NET APPROACH
This is the root directory of the project containing all data for YOLO11 approach.

#### a. 1 - SOURCE DATA
Contains raw and preprocessed datasets used in the project.
- **1 - ORIGINAL DATASET**: Includes the unaltered, original dataset.
- **2 - YOLO DATASET**: Contains datasets formatted or processed for YOLO models.

#### b. 2 - DATA PROCESSING CODE
Includes jupyter notebook for data preprocessing.

#### c. 3 - TRAINING CODE
Houses code and outputs related to training the 2D U-Net model.
- **MODELS result of training**: Trained models and their checkpoints.
- **NOTEBOOKS**: Notebooks used for training and analyzing model performance.


## Folder Descriptions

### 1. 3D U-NET APPROACH
This is the root directory of the project containing all data for 3D U-NET approach.


## Notes
- The main project report summarizing the methodology, results, and analysis. The **REPORT** file is critical for understanding the overall project outcomes.
- The directory names and file organization aim to streamline project navigation and clarity.

For any questions or further clarifications, refer to the **REPORT** or contact the project team.
