
# 🇬🇧➡️🇮🇳 English to Hindi Translator (WIP)

This is an ongoing NLP project aimed at translating English sentences into Hindi using traditional natural language processing techniques. The current focus is on preprocessing bilingual data — cleaning, normalizing, and preparing sentence pairs for model training.

🚧 **Current Status**: Data preprocessing stage. No deep learning or transformer models are being used yet.

## Features

- Clean and normalize parallel English-Hindi text
- Tokenize sentences and build vocabularies
- Prepare padded sequences for model input
- (Planned) Train a basic seq2seq model without transformers

## Tech Stack

Python 3, NLTK, spaCy, NumPy, pandas (for data handling), Jupyter Notebooks (for experiments)

## Folder Structure (Planned)

english-to-hindi-translator/  
├── data/ → raw and cleaned datasets  
├── preprocessing/ → scripts for cleaning and tokenizing  
├── models/ → model training and evaluation scripts (future)  
├── notebooks/ → Jupyter experiments and EDA   
├── README.md  
└── requirements.txt  

## Usage (Planned)

```python
from translator import translate_to_hindi
print(translate_to_hindi("Hello, how are you?"))
# Output: "नमस्ते, आप कैसे हैं?"
````

## To-Do

* [x] Collect and organize English-Hindi datasets
* [x] Basic text cleaning and normalization
* [ ] Tokenization and sequence preparation
* [ ] Vocabulary building
* [ ] Implement simple encoder-decoder model
* [ ] Evaluate model performance


## Demo

Coming soon! A command-line or notebook-based demo will be added once the model is ready.

