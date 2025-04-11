# T5-Based-Multilingual-Translation
T5-Based Multilingual Translation

This project demonstrates a multilingual translation system using the T5 (Text-to-Text Transfer Transformer) model. The system translates text from one language to another, leveraging the power of pre-trained transformer models for accurate and efficient translations.

# T5-Based Multilingual Translation

## Overview
This project implements a multilingual translation system using the T5 (Text-to-Text Transfer Transformer) model. The T5 model is a pre-trained transformer-based architecture that excels at various natural language processing tasks, including translation. By providing a source language, target language, and input text, the system generates accurate translations.

## Key Features
- **Multilingual Support**: Translates text between multiple languages.
- **Advanced Parameters**: Allows customization of translation parameters such as `max_length`, `num_beams`, and `num_return_sequences`.
- **Pre-trained Model**: Utilizes the `t5-base` model for high-quality translations.

## Dependencies
To run this project, you need the following libraries:
- `transformers`: For loading the T5 tokenizer and model.
- `torch`: For tensor operations and model inference.

Install the required libraries using:
```bash
pip install transformers torch
