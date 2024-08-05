# Rider Intention Prediction (RIP) - ICPR 2024

**Team Name:** Utkarsh

## Project Overview
The Rider Intention Prediction (RIP) project is part of the ICPR 2024 competition, focused on enhancing rider safety by predicting two-wheeler rider maneuvers before they occur. By accurately predicting actions such as left turns, right turns, lane changes, and stops, this project aims to reduce road accidents involving motorbike riders and pedestrians.

## Objectives
- Develop a robust machine learning model capable of predicting rider intentions based on video data.
- Utilize single-view (frontal) and multi-view (frontal, left side-mirror, right side-mirror) video inputs to enhance prediction accuracy.
- Evaluate model performance using metrics like F1 score and accuracy.

## Key Components

### Data Preprocessing
- Handling and preprocessing video data to extract relevant features.
- Implementing data augmentation techniques to improve model robustness.

### Model Development
- Leveraging pre-trained models such as ResNet50 for feature extraction.
- Fine-tuning the model to adapt to the specific requirements of the rider intention prediction task.
- Experimenting with different model architectures to optimize performance.

### Evaluation
- Using a validation set to assess model performance.
- Generating classification metrics including accuracy, precision, recall, and F1 score.
- Analyzing the confusion matrix to identify and rectify misclassifications.

### Submission
- Outputting predictions in the required CSV format with one-hot encoded maneuver classes.
- Preparing method description documentation detailing the approach, model selection, and results.

## Repository Structure
- `/data`: Contains scripts for data loading and preprocessing.
- `/models`: Includes model architectures and training scripts.
- `/notebooks`: Jupyter notebooks for exploratory data analysis and model experimentation.
- `/results`: Stores validation results, confusion matrices, and other evaluation artifacts.
- `README.md`: Detailed project overview, setup instructions, and usage guide.
- `LICENSE`: The chosen license for the repository.

## Usage
This repository provides all the necessary code and documentation to reproduce our results and build upon our work. Users can follow the instructions in this `README.md` to set up the environment, preprocess the data, train the model, and evaluate its performance.
