# WhatsApp Classifier

A machine learning project to predict the author of messages in a WhatsApp group chat.

Everyone has their own unique texting style. This project leverages natural language processing (NLP) techniques to analyze message patterns and identify who likely wrote a given message. By training a model on historical chat data, the classifier can predict the author with reasonable accuracy.

It uses the `bert-base-cased` model for classification—while not the most powerful by today's standards, it's ideal for demonstrating functionality with manageable training time.

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
