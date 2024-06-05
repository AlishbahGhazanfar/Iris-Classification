
# Iris Classification Task

This project involves an Iris classification task using various Python libraries for data processing, visualization, and machine learning. The model is deployed using FastAPI to provide easy access via API endpoints.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Training](#model-training)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)

## Project Overview

This project demonstrates the process of classifying Iris species using logistic regression. The following libraries and tools are used:

- **pandas**: For data manipulation and analysis
- **numpy**: For numerical computations
- **seaborn**: For data visualization
- **matplotlib**: For plotting graphs
- **scikit-learn**: For machine learning tasks, including preprocessing and model training
- **FastAPI**: For deploying the model as an API

## Installation

To set up the project, follow these steps:

1. Clone the repository.
2. Install the required Python packages listed in `requirements.txt`.

## Usage

1. Open and run the Jupyter Notebook provided to preprocess the data, train the model, and evaluate its performance.
2. Use the FastAPI app to create API endpoints for making predictions using the trained model.

## Project Structure

- `data/`: Contains the Iris dataset.
- `notebooks/`: Jupyter Notebook for data preprocessing, model training, and evaluation.
- `app/`: FastAPI application for deploying the model.

## Model Training

The logistic regression model is trained on the Iris dataset, which includes data preprocessing steps like label encoding and standard scaling. The model is evaluated using metrics such as accuracy and confusion matrix.

## API 

The FastAPI application provides endpoints to interact with the trained model. You can make predictions by sending requests to these endpoints.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.
