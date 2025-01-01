# Advanced AI Chatbot with NLP Features

This project is an **Advanced AI Chatbot** that integrates the capabilities of the **Ollama model** and **Hugging Face NLP pipelines** to deliver rich conversational experiences and perform various natural language processing tasks. The chatbot supports multiple functionalities, including direct interaction with the Ollama model, text translation, summarization, and sentiment analysis.

## Objectives
1. **Interactive Conversations**: Facilitate seamless user interactions with the Ollama model for conversational AI tasks.
2. **Multilingual Support**: Translate text to English or other specified languages using state-of-the-art translation models.
3. **Summarization**: Condense lengthy text into concise summaries to aid in understanding large amounts of information quickly.
4. **Sentiment Analysis**: Determine the sentiment (positive, negative, or neutral) of user-provided text and provide confidence scores.

## Features
- **Ollama Integration**: Allows users to interact with the Ollama language model by prefixing queries with "ollama."
- **Translation Pipeline**: Uses the Hugging Face `Helsinki-NLP/opus-mt-fr-en` model to translate text to English.
- **Text Summarization**: Generates concise summaries using Hugging Face's summarization pipeline.
- **Sentiment Analysis**: Leverages Hugging Face's sentiment analysis pipeline to classify the sentiment of the input text.
- **Dynamic Functionality**: Automatically detects the user's intent based on keywords like "translate," "summarize," or "sentiment."

## How It Works
1. Users can interact with the chatbot via a command-line interface (CLI).
2. Depending on the user's input:
   - If the query starts with "ollama," the chatbot communicates with the Ollama model to generate a response.
   - If the query contains "translate," "summarize," or "sentiment," the chatbot executes the corresponding NLP task.
3. The chatbot processes the user's input and returns relevant responses or analysis results.

## Applications
- **Multilingual Support**: Translate non-English text into English for broader understanding.
- **Content Summarization**: Aid researchers, students, and professionals in condensing large texts into actionable insights.
- **Sentiment Insights**: Help businesses or individuals gauge public opinion or emotional tones in text data.
- **Conversational AI**: Serve as an intelligent assistant for answering questions and engaging in discussions.

## Potential Extensions
- Adding support for additional languages in translation.
- Enhancing summarization and sentiment analysis with fine-tuned models.
- Integrating the chatbot into a web or mobile application for broader accessibility.

This project combines conversational AI with powerful NLP tools, making it versatile for personal use, research, or business applications.
