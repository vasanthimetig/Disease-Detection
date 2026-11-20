# Disease Detection System

## Overview

The Disease Detection System is a Flask-based web application that explores disease prediction using medical images and symptom-based analysis. It combines machine learning models for chest X-ray classification with rule-based symptom matching.

## Features

- **Chest X-ray Analysis:** Uses TensorFlow/Keras models for Pneumonia and Tuberculosis prediction.
- **Symptom-Based Prediction:** Matches user-entered symptoms against predefined disease patterns.
- **Health Suggestions:** Displays basic suggestions based on the identified symptoms or disease category.
- **Doctor Recommendations:** Provides doctor suggestions based on the selected location when matching doctor data is available.
- **Web Interface:** Provides a simple interface for submitting symptoms and medical images.

## Technology Stack

- Python
- Flask
- TensorFlow
- NumPy
- HTML
- CSS
- Machine Learning

## Project Structure

```text
Disease-Detection/
├── static/
│   └── images/
├── templates/
├── app.py
├── APP1.PY
├── predict.py
├── predict_tb.py
├── train.py
├── train_heart.py
├── train_tb.py
├── evaluate.py
└── test.py
```

## Setup and Execution

### Prerequisites

- Python 3.x
- pip
- Required Python libraries
- Trained model files for image prediction

### Steps

1. Clone the repository:

```bash
git clone https://github.com/vasanthimetig/Disease-Detection.git
```

2. Navigate to the project folder:

```bash
cd Disease-Detection
```

3. Install the required dependencies after configuring them for your Python environment.

4. Place the required trained model files in the expected model directory and update model paths in the application if necessary.

5. Run the Flask application:

```bash
python app.py
```

6. Open the local Flask address displayed in the terminal.

## Note

This project is developed for academic and learning purposes. Predictions and suggestions are experimental and must not be considered a substitute for professional medical diagnosis or treatment. Image prediction requires the corresponding trained model files and correct model paths.

## Repository

[GitHub – Disease Detection](https://github.com/vasanthimetig/Disease-Detection)
