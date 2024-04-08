# Programmatically Access Generative APIs using Python.

## Generative AI Customer Query Resolution

    This project delves into the realm of generative AI, exploring its capabilities and practical applications. 
    The main focus lies in accessing various generative AI models programmatically through the APIs they offer.

## Overview

Generative AI refers to a class of artificial intelligence systems that are capable of generating new content, whether it be text, images, or even music, based on patterns learned from existing data. In this project, we delve into understanding what generative AI entails and how it can be leveraged to address real-life challenges.

## Project Objectives

The primary objective of this project is to implement a system for resolving customer queries using generative AI techniques. By recording customer complaints and utilizing generative AI models, we aim to provide relevant solutions from a database of potential resolutions.

## Implementation Details

### 1. Data Preparation

We begin by loading the training dataset from `Agent.csv`, which contains valuable information necessary for training our AI models. This dataset serves as the foundation for understanding customer complaints and their corresponding resolutions.

### 2. Audio-to-Text Conversion

Customer complaints, often recorded in audio format, need to be converted into text for further analysis. To achieve this, we employ Whisper, a tool designed for converting audio to text efficiently and accurately.

### 3. Text Analysis

Once the customer complaint is transcribed into text, we utilize embedding techniques to analyze the textual data. Embeddings enable us to represent words or phrases in a numerical format, facilitating semantic analysis and comparison.

### 4. Response Generation

To provide relevant answers to customer queries, we employ the RAG (Retrieval-Augmented Generation) model. RAG combines elements of retrieval-based and generative approaches, allowing us to retrieve relevant information from the database while also generating coherent responses based on the query context.

## Conclusion

Through the integration of various generative AI techniques, this project showcases a practical application for addressing customer queries effectively. By leveraging the capabilities of generative AI models, we can enhance customer satisfaction and streamline the resolution process.
