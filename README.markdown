# Digital Egypt Pioneers Initiative (DEPI) Graduation Project: End-to-End Text Sentiment Analysis

## Project Overview

This repository contains the code and documentation for an end-to-end text sentiment analysis system, developed as the graduation project for the Digital Egypt Pioneers Initiative (DEPI). The goal of this project is to analyze text (e.g., customer reviews) and classify the sentiment as **positive**, **negative**, or **neutral**. We aimed to help businesses understand customer feedback quickly and efficiently without manually reviewing thousands of comments.

## Problem Statement

In the digital era, businesses receive an overwhelming volume of unstructured textual feedback, such as customer reviews and social media comments. Manually analyzing this data to gauge customer sentiment is a time-intensive and resource-heavy process, often impractical for organizations dealing with large datasets. For instance, a restaurant receiving 1,000 reviews struggles to efficiently determine overall customer satisfaction, highlighting the need for an automated, scalable solution to extract actionable insights from text data.

## Solution

To address this challenge, we developed an advanced text sentiment analysis system that leverages machine learning to automate the classification of sentiments in textual data. The system:

- Automatically processes and analyzes input text.  
- Accurately categorizes sentiments into Positive (e.g., "I love this product!"), Negative (e.g., "Worst experience ever"), or Neutral (e.g., "The service was okay").  
- Utilizes state-of-the-art tools and frameworks to ensure efficient text processing, model training, and user interaction.

This solution empowers businesses to gain rapid insights into customer sentiment, enabling data-driven decision-making and improved customer experiences.

## Key Features

- **Data Preprocessing:** Cleaned and prepared a dataset of text examples using transformers for tokenization and text processing.  
- **Model Training and Tracking:** Trained multiple models and tracked experiments using MLflow for better management and comparison.  
- **Interactive Interface:** Built a user-friendly interface with Gradio to allow users to input text and get sentiment predictions easily.  
- **Prediction:** Can predict sentiments for new text inputs (e.g., "The service was okay" → Neutral).

## Repository Contents

- **DEPI_Graduation_Project.ipynb:**  
  Jupyter Notebook with the full project code, including data preprocessing, model training, experiment tracking with MLflow, Gradio interface setup, and prediction examples.

- **sentiment_analysis_model/:** Folder containing the sentiment analysis model files, including:  
  - `vocab.txt`: Vocabulary file for the tokenizer.  
  - `tokenizer_config.json`: Configuration file for the tokenizer.  
  - `tf_model.h5`: Trained model weights in HDF5 format.  
  - `special_tokens_map.json`: Mapping of special tokens for the tokenizer.  
  - `config.json`: Model configuration file.

## How It Works

- **Data Collection and Preprocessing:**  
  We gathered a dataset of text examples labeled as positive, negative, or neutral, and processed it using transformers for tokenization.

- **Model Training and Tracking:**  
  We trained multiple models and used MLflow to log experiments, parameters, and results for easy tracking and comparison.

- **Interactive Testing:**  
  We integrated Gradio to create an interface where users can input text and see the predicted sentiment instantly.

- **Prediction Examples:**  
  The system can classify new text inputs, e.g., "I love this product!" was predicted as Positive.

## Example Predictions

- "I love this product! It's amazing and works perfectly." → **Positive**  
- "This is the worst experience I've ever had." → **Negative**  
- "The service was okay, nothing special but not bad either." → **Neutral**

## Why This Matters

- Saves time by automating sentiment analysis.  
- Helps businesses understand customer feedback quickly.  
- Can be used for various applications, like analyzing product reviews or improving services.

## Setup and Usage

1. **Clone the Repository:**

```bash
git clone https://github.com/HalaMohamed1/End-to-End-Text-Sentiment-Analysis-Project
cd End-to-End-Text-Sentiment-Analysis-Project
```

2. **Install Dependencies:**  
   Ensure you have Python 3.x installed. Manually install the required packages, such as `pandas`, `scikit-learn`, `transformers`, `mlflow`, and `gradio`, using pip. For example:

```bash
pip install pandas scikit-learn transformers mlflow gradio
```

3. **Run the Notebook:**  
   Open `DEPI_Graduation_Project.ipynb` in Jupyter Notebook or Google Colab to explore the code and run the project.

4. **Launch the Gradio Interface:**  
   Run the notebook cells related to Gradio to launch the interactive UI and test the sentiment analysis tool.

## Contributors

- Hala Mohamed  
- Marwan Shamel  
- Mariam Samy  
- Malak Mohamed  
- Jana Hatem  
- Husam Abozide

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.