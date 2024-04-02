# News-Summarization
This project aims to develop a text summarization model using the T5 small architecture trained on the Multi News dataset. Text summarization involves condensing lengthy articles into shorter, coherent summaries while retaining key information. 

## Overview
The project utilizes transfer learning techniques with the T5 small model architecture. Transfer learning involves fine-tuning a pre-trained model on a specific task, in this case, text summarization. By leveraging the pre-trained weights and knowledge learned from a large corpus of data, the model can effectively summarize text with minimal training on the target dataset.

## Dataset
The Multi News dataset is used for training and evaluation. This dataset consists of news articles paired with human-written summaries, providing a rich source of data for training the text summarization model.

## Evaluation
The performance of the text summarization model is evaluated using the ROUGE (Recall-Oriented Understudy for Gisting Evaluation) metric. ROUGE measures the overlap between the generated summaries and human-written references, providing insights into the quality of the generated summaries.
