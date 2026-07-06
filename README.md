Local Chatbot with LangChain and TinyLlama
This project demonstrates how to set up and run a local conversational AI chatbot using LangChain and Hugging Face's HuggingFacePipeline. It uses the lightweight TinyLlama-1.1B-chat-v1.0 model to run completely locally on your machine without relying on external API calls.

How It Works
Instead of hitting a remote API server, this script downloads the model weights locally to your machine.

HuggingFacePipeline loads the model into your local memory and sets up a text generation pipeline using the transformers library.

ChatHuggingFace wraps that pipeline to format your inputs into a chat-ready structure (System, Human, and AI messages).
