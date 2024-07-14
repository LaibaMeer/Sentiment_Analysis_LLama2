# Sentiment_Analysis_LLama2

## Readme for Aspect-Based Sentiment Analysis with Llama 2 on Amazon Reviews

Project Overview
This project explores aspect-based sentiment analysis (ABSA) using the powerful Llama 2 large language model (LLM) on a dataset of Amazon reviews obtained from Kaggle. ABSA aims to identify aspects (extracted from user's input) within a review and determine the sentiment (positive, negative, neutral) expressed towards those aspects.

About Data
* Source: Kaggle Amazon Reviews dataset
  https://www.kaggle.com/datasets/tarkkaanko/amazon
* Preprocessing: cleaning, tokenization, lemmatization, handling missing values

About Model
* Source: https://huggingface.co/meta-llama/Llama-2-7b
* Instructions: Create a token on **Settings** at Huggingface User
  Post a request to access the model Llama 2 or Llama 3 on the above website
  Login into Huggingface using the cell and enter your token in it!

Methodology

Model: Llama-2 7B parameter LLM ("meta-llama/Llama-2-7b-chat-hf")
Fine-tuning: Specific fields of the model are altered. 
Framework: Langchain, Transformers, pipeline, torch, 

Demo of one of the Text:

""" Don't buy this car as I already made a mistake buying that car of model XZ+O.
Within 1 week the sensor did not work.
Irritating noise produce during back gear applied. And when I inform to the company they work as laziness. No speed-up process for a new car as I bought. Many times I mail to their customer care, no response comes. The only e generated mail comes from their side. No hope whether my car is well. or not. I suggest never buy that car. I already waste my 13 lakh rupees. Don't buy
"""

Results:

[
            "back sensor", "negative"
            "irritating noise", "negative"
            "speed-up process", "neutral"
            "customer care", "negative"
            "waste my 13 lakh rupees", "negative"
            "don't buy", "negative"
]

#LLMProject #Langchain #sentiment_analysis #aspectbased #transformers #LLama2 #LLMdevelopment
