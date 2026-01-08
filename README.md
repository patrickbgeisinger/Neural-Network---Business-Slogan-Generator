# Neural-Network---Business-Slogan-Generator
Program that helps businesses generate slogans based on their industry and predict the industry of a business based on a given slogan.

## Project Overview
This project implements two neural network models for business slogan analysis:
1. **Slogan Generator**: An LSTM model that generates slogans based on industry category
2. **Slogan Classifier**: A classification model that predicts industry from slogans

## Features
- Data preprocessing and tokenization
- LSTM-based text generation
- Industry classification from slogans
- Model evaluation and comparison

## Technologies Used
- Python 3.8+
- TensorFlow/Keras
- spaCy
- Pandas
- NumPy
- Jupyter Notebook

## Dataset Used
This project utilized the 'slogan-valid.csv' file provided by Arizona State University, the file has been provided for you to download. The data in the jupyter notebook is loaded using google drive,
you will be prompted for Google credentials and that the file is saved in a Google Drive. 


## Project Structure

### 1. Data Preprocessing
- Load and clean the slogan dataset
- Handle missing values
- Tokenize slogans and business names

### 2. Slogan Generator
- LSTM model architecture
- Industry-conditioned text generation
- Model training and evaluation

### 3. Slogan Classifier
- Classification model for industry prediction
- Train/test split and evaluation
- Performance metrics

### 4. Model Integration
- Generate slogans for specific industries
- Classify generated slogans
- Compare and analyze results

## Author
Patrick Geisinger

## License
This project is part of the Arizona State Univeristy bootcamp curriculum.

## Acknowledgments
- Arizona State Univeristy for the project template
- Dataset providers
