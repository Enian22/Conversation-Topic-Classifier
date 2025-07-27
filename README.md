# Conversation Topic Tagging

This project aims to classify conversations between two people into one of six predefined topics using a deep learning model. The model is trained on a dataset of text transcripts and can predict the most likely topic of a given conversation.

## Topics
The model classifies conversations into the following topics:
- Bank Bailout
- Budget
- Credit Card
- Family Finance
- Job Benefits
- Taxes

## Features
- Preprocesses and tokenizes conversation text.
- Uses a TensorFlow model with embedding and convolutional layers for classification.
- Achieves high accuracy on both training and validation datasets.
- Includes an API function to predict the topic of new conversations.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd conversation-tagging