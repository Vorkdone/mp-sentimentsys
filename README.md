# Sentiment and Emotion Analyzer

## Overview

The **Sentiment and Emotion Analyzer** is a Python application designed to analyze text input (such as product reviews) for sentiment and emotional content. This application utilizes Natural Language Processing (NLP) techniques, leveraging libraries like NLTK and Hugging Face's Transformers to detect sentiments and emotions from user-provided text.

The project reads emotional data from an Excel file (`emotions.xlsx`) that maps specific words to corresponding emotions. It categorizes these emotions into predefined groups and visualizes the results using Matplotlib.

## Features

- Sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner).
- Emotion detection based on a custom lexicon loaded from an Excel file.
- Visualization of detected emotions using bar charts.
- User-friendly command-line interface for inputting text reviews.

## Requirements

To run this project, you will need to install the following Python packages:

- `pandas`: For data manipulation and analysis.
- `openpyxl`: For reading Excel files.
- `nltk`: For natural language processing tasks.
- `transformers`: For emotion detection using pre-trained models.
- `matplotlib`: For plotting emotion analysis results.

### Installation

1. main code

2. pip install pandas openpyxl nltk transformers matplotlib

3. **Install required packages**:

You can install all required packages using pip. Run the following command:

3. **Install TensorFlow**:

To install TensorFlow, you can use the following command based on your system configuration:

- For CPU support:

  ```
  pip install tensorflow
  ```

- For GPU support (ensure you have the necessary CUDA drivers installed):

  ```
  pip install tensorflow[and-cuda]
  ```

4. **Download NLTK data**:

After installing NLTK, you may need to download additional datasets used in the project. You can do this by running the following commands in your Python environment:
import nltk
nltk.download('stopwords')
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('vader_lexicon')


## Datasets

### Accessing the Emotion Dataset

The application requires an Excel file named `emotions.xlsx` that contains two columns:
- **word**: The words to analyze.
- **emotion**: The corresponding emotions associated with those words.

#### Creating the `emotions.xlsx` File

You can create this file manually or download a sample dataset. Here’s how to format it:

| word        | emotion    |
|-------------|------------|
| happy       | happy      |
| sad         | sad        |
| angry       | angry      |
| anxious     | anxious    |
| attached    | attached   |
| fearful     | fearful    |
| lustful     | lustful    |

Make sure to save this file in the same directory as your main script (`main.py`).

## Usage

1. **Run the application**:

Execute the main script using Python:


2. **Input reviews**:

When prompted, enter a product review or any text you want to analyze. Type 'exit' to quit the application.

3. **View results**:

The application will display the detected sentiment and emotions, along with a bar chart visualizing the emotional distribution.

## Example Input





