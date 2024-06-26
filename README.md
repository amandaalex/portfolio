# AI portfolio

### [Voice Assistant Utilizing Google Gemini](#voice-assistant-utilizing-google-gemini-1)
### [Retrieval-Augmented Generation (RAG) application](#retrieval-augmented-generation-rag-application-1)
### [Backtest experiment using chatbots](#backtest-experiment-using-chatbots-1)
### [Facial Landmark Detection for Augmented Reality Experiences](#facial-landmark-detection-for-augmented-reality-experiences-1)

***

# Voice Assistant Utilizing Google Gemini
Using Gemini API's to provide intelligent responses to complex questions. Featuring real-time interaction, responsive design, and support for Gemini Pro and Gemini Vision models.

[Github](https://github.com/amandaalex/google-gemini-voice-chatbot)

# Retrieval-Augmented Generation (RAG) application
Implementing a Retrieval-Augmented Generation (RAG) System built using Python, OpenAI API, and LangChain.

This project provides an outline of the key steps involved in building a RAG system powered by OpenAI's API and orchestrated by LangChain. RAG enhances conversational AI by combining document retrieval and generative language modeling.

#### Prerequisites
* Python environment
* LangChain, OpenAI, and relevant libraries installed (pip install langchain openai)
* A valid OpenAI API key

#### Process
1. `Data Preparation`: Structure your knowledge base (e.g., ScaleX Innovation information) for optimal retrieval. Consider formats like text files, CSV, or a database.
2. `Vectorization`: Use OpenAI's embedding models to convert textual data into vector representations, enabling efficient similarity search.
3. `Retrieval Component`: Choose a vector database (e.g., Faiss, Pinecone) to store and search the embeddings.
4. `LangChain Integration`:
    * Create a chain for the retrieval process, querying your vector database.
    * Construct a chain for generating text (using OpenAI's text generation models).
    * Combine the chains, feeding retrieved context into the text generation chain.
5. `Conversation Flow`: Design the logic for how your chatbot interacts with users, incorporating the RAG system for informed responses.

#### Key Points
* RAG augments standard chatbots with the ability to reference external knowledge sources.
* The quality of your data preparation directly impacts retrieval effectiveness.
* LangChain streamlines the integration of retrieval and generation components.
  
[Github](https://github.com/amandaalex/rag-openai)


# Backtest experiment using chatbots 
Using chatbots to execute backtests of simple trading strategies. Backtest trading strategies in minutes using Gemini AI.

Generate python code to import the necessary libraries for backtesting a trading strategy, focusing on data handling from Yahoo Finance and visualization.

[Github](https://github.com/amandaalex/backtest-chatbots)

![Screenshot](https://lh3.googleusercontent.com/pw/AP1GczNR_9JVFBC3FGI6nknafk2T-DIPA34q-4eR98_eOqbUEYUF3UkeoxxCYTqUmUacO16NMOmC7vtG3aGXNBVwVCHReHr0pdcCgxTkaIBxSW4z2157bJ86Oerfvl9_O1Os8GWckfrPbuCU6ovLRvvIx8rK=w948-h593-s-no-gm?authuser=0)


# Facial Landmark Detection for Augmented Reality Experiences
Snapchat's dynamic filters demonstrate the power of real-time facial landmark detection in augmented reality (AR). To achieve similar effects, precise identification of key facial features is essential. In this project, I'll explore the machine learning techniques behind facial landmark detection and provide guidance for implementation.

#### Key Concepts and Techniques
* `Facial Landmarks`: These are anatomically significant points on the face (e.g., corners of the eyes, tip of the nose, etc.).
* `Machine Learning Models`: Computer vision models, often convolutional neural networks (CNNs), are trained to locate these landmarks within images or video frames.
* `Libraries and Tools`: Popular choices include OpenCV, Dlib, and MediaPipe for model development and real-time inference.

#### Process
1. `Data Preparation`: Sourcing or creating a dataset of images with labeled facial landmarks.
2. `Model Selection and Training`: Choosing an appropriate pre-trained model or training a custom CNN.
3. `Landmark Detection`: Applying the model to new images or videos.

[Github](https://github.com/amandaalex/face-landmarks)

![Picture](https://raw.githubusercontent.com/amandaalex/face-landmarks/main/images/pic.jpeg)

