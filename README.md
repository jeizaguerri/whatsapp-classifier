# WhatsApp Classifier

A machine learning project to predict the author of messages in a WhatsApp group chat.

Ever looked at an old message with no name attached, and thought, *“Oh, that has to be Alex — only they text like that”*? Whether it’s a favorite phrase, punctuation style, or just a certain vibe, everyone has a unique way of writing. If humans can pick up on those subtle cues, why not teach a machine to do the same?

This project explores that idea using natural language processing (NLP). By analyzing historical WhatsApp chats, we train a model to recognize these patterns and predict the most likely sender of a message. It’s like giving your computer the same intuition you have when reading your friends’ texts.

It uses the `bert-base-cased` model for classification — not the most cutting-edge today, but ideal for demonstrating the concept with a reasonable training time.

## Core Features

- Parsing WhatsApp chat exports to create a training dataset  
- Preprocessing and tokenizing the dataset  
- Fine-tuning a language model on the training data  
- Inference on new messages to predict the most likely author  

## Usage

1. Export your WhatsApp group chat as a `.txt` file and place it in the project directory.  
   You can learn how to export chats [here](https://faq.whatsapp.com/1180414079177245/?locale=es_LA&cms_platform=android).

2. Run the cells in the `whatsapp_classifier.ipynb` notebook.  
   Training time depends on your machine and the size of the chat. For better performance, consider using a cloud platform like Google Colab.
