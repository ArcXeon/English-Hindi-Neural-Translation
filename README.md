# English-Hindi-Natural-Language-Translation
# Introduction
This project focuses on implementing an English-to-Hindi translation system using the MBart model and tokenizer from the Hugging Face Transformers library. The primary objective is to leverage pre-trained models to facilitate cross-lingual natural language generation, specifically translating English sentences into Hindi.

# Dataset
The dataset comprises English-Hindi sentence pairs, stored in a CSV file. Each row contains an English sentence and its corresponding Hindi translation. This dataset is critical for both training and evaluating the translation model.

# Methodolgy
## Importing Libraries
The first step is to import the necessary libraries and tool:
Transformers: For accessing the MBart model and tokenizer.
Pandas: For data manipulation and handling.
FastEda: For data visualization.
Matplotlib/Seaborn: For creating visualizations
Numpy: For numerical computations

## Data Import and Visualization
The next step involves importing the dataset from the CSV file and performing initial data exploration and visualization using the FastEda library. This helps understand the dataset's structure, distribution, and other essential characteristics.

## Data Preprocessing
Data preprocessing is crucial for preparing the text for model training. The steps include:
Text Cleaning: Removing unwanted characters, punctuation, and extra spaces.
Tokenization: Splitting sentences into individual tokens.
Adding Special Tokens: Creating sequence boundary marking

## Metric Calculation
Various metrics such as sentence lengths and word frequencies are calculated to gain insights into the dataset and prepare it for model training.

## Model Initialization and Translation Function
The MBart model and tokenizer are initialized for Hindi translation. A translation function is created to take an English input sentence, tokenize it, generate Hindi translations using the MBart model, and format the output

## Translation Results
The translation function is applied to a sample of English sentences from the dataset, and the results are printed alongside the original Hindi sentences.



