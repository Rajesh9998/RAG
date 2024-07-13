# RAG Chatbot with Pinecone, Gemini 1.5 Pro & Groq's LLama3 70b

> This repository showcases a Retrieval Augmented Generation (RAG) chatbot powered by Pinecone vector database and Google's Gemini 1.5 Pro & Groq's LLam3 70b LLMs.

## Overview

Traditional LLMs are limited by their static knowledge cutoff. This project overcomes this by integrating a Pinecone vector database, allowing the LLM to access and leverage up-to-date, domain-specific information.


## Here’s a quick demo:

[![Watch the video](https://img.youtube.com/vi/your_video_id/maxresdefault.jpg)](https://github.com/user-attachments/assets/010c9e20-d5ba-44b0-a557-e43024a10cb3)

## What is RAG?

Retrieval Augmented Generation (RAG) enhances LLMs by connecting them to external knowledge sources. This enables them to access current information, specialized knowledge, and personalized data, leading to more accurate and relevant responses.

## Key Components

### Pinecone

Pinecone is a leading cloud-native vector database, optimized for efficient storage and retrieval of high-dimensional vectors. Its robust API, scalability, and focus on machine learning make it ideal for RAG applications.

### Gemini 1.5 Pro

Google DeepMind's next-generation multimodal AI model, designed for versatility and performance, includes:

- **Long Context Window:** Processes up to 128,000 tokens, enabling a deeper understanding of complex topics.
- **Multilingual Capabilities:** Understands and responds in multiple languages.
- **2 Million Context Length (Private Preview):** Expands the context window even further, allowing for an unprecedented amount of information processing.
- **Code Execution:** Executes Python code within a secure sandbox environment, facilitating problem-solving and iterative learning.

### Groq

Groq, an American AI company founded in 2016, specializes in hardware and software solutions designed to accelerate AI workloads, with a strong focus on natural language processing (NLP).

#### Groq API

Developers can seamlessly integrate Groq's technology into their applications using the Groq API. Key features include:

- **Ultra-low Latency Inference:** Enables real-time processing of large language models (LLMs), ensuring rapid responses.
- **State-of-the-art LLM Integration:** Facilitates the use of powerful LLMs, like Llama-2, within applications, unlocking advanced NLP capabilities.
- **Scalability:** Handles large workloads and integrates seamlessly with existing development workflows.

#### Groq's Llama 3 70B Model

Groq offers the Llama 3 70B model, a powerful open-source large language model (LLM) from Meta, running on its LPU Inference Engine. 

- **High Throughput:** Groq's implementation of Llama 3 70B achieves an impressive throughput of approximately 700 tokens per second, significantly faster than many other providers.
- **Competitive Pricing:** Groq provides cost-effective access to Llama 3 70B, with pricing based on input and output tokens.
- **Low Latency:** Groq's infrastructure ensures a low latency for initial responses, contributing to a smooth user experience.



## Features

- **Enhanced Accuracy:** Grounding LLM responses in factual data from the Pinecone knowledge base, mitigating "hallucinations."
- **Up-to-date Information:** Accessing the latest information, overcoming the static knowledge limitations of LLMs.
- **Domain Specialization:** Tailoring the LLM's knowledge to specific domains through curated data in Pinecone.
- **Efficient Retrieval:** Leveraging Pinecone's high-speed similarity search for rapid retrieval of relevant context.

## Real-World Applications

- **Code Generation and Summarization:** Efficiently generating and summarizing code.
- **Document and Meeting Summarization:** Extracting key insights from lengthy documents and meeting transcripts.
- **Personalized Financial Advice:** Providing tailored financial guidance based on user data and market trends.
- **Customer Service Chatbots:** Enhancing customer support with accurate and relevant information retrieval.
- **Improving Search Engine Results:** Delivering more precise and context-aware search results.

