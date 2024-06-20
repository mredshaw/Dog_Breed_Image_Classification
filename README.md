# Dog Breed Image Classification

## Project Overview
The objective of this project is to develop a deep learning model to classify images from the Stanford Dogs dataset. The goal is to experiment with different neural network architectures and optimization techniques to achieve the best possible classification accuracy.

## Dataset
- **Dataset:** Stanford Dogs Dataset available in TensorFlow Datasets
- **Description:** This dataset contains images of 120 breeds of dogs from around the world and is commonly used for fine-grained image categorization.

## Requirements

### Data Preprocessing [5 marks]
- Load the dataset using TensorFlow Datasets.
- Perform necessary preprocessing steps like resizing images, normalizing pixel values, etc.

### Model Building [8 marks]
- Design a convolutional neural network (CNN) for this multi-class classification task.
- Include various types of layers such as Convolutional Layers, Pooling Layers, Dropout Layers, and Fully Connected Layers.
- Experiment with different numbers of layers and varying numbers of neurons.

### Model Training and Optimization [10 marks]
- Split the dataset into training, validation, and test sets.
- Choose an appropriate loss function and optimizer for training the model.
- Implement callbacks like Early Stopping and Model Checkpoints to optimize the training process.

### Evaluation [5 marks]
- Evaluate the model's performance on the test set.
- Report the classification accuracy and visualize the performance using a confusion matrix.

### Write-Up [2 marks]
- Document the process, model architecture choices, and results in a report.
- Discuss any challenges faced and how you overcame them.
- Provide insights on what worked well and what didn’t.

## Contents
- `Dog_Breed_Image_Classification.ipynb`: Jupyter Notebook containing the entire analysis, including data preprocessing, model building, training, optimization, evaluation, and write-up.

## Tools and Libraries Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn

## How to Run
1. Clone this repository: `git clone https://github.com/mredshaw/Dog_Breed_Image_Classification.git`
2. Open the Jupyter Notebook: `Dog_Breed_Image_Classification.ipynb`
3. Execute the cells in the notebook to see the analysis and results.

## Key Insights
The notebook provides detailed insights into the development and performance of various convolutional neural network architectures for dog breed classification using the Stanford Dogs dataset.
