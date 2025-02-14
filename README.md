# Law QA System

## Overview
The **Law QA System** is an AI-driven tool designed to retrieve and summarize relevant legal sections based on user queries. It leverages Natural Language Processing (NLP) techniques to match user questions to the most pertinent legal provisions and generate concise summaries.

## Models Used
1. **SentenceTransformer (all-MiniLM-L6-v2)**:
   - Used for encoding legal texts and user queries into numerical vectors.
   - Enables efficient similarity comparison through cosine similarity.
   
2. **NSI319 Legal-Pegasus**:
   - A fine-tuned version of the Pegasus model for legal text summarization.
   - Used to generate concise summaries of relevant legal sections.

## Features
- **Semantic Search**: Finds the most relevant legal provisions for a given query.
- **Text Summarization**: Generates a short summary of selected legal sections.
- **Preprocessing & Storage**: Cleans and embeds legal texts for efficient retrieval.
- **Persistence**: Allows saving and loading of model weights and embeddings.

## How It Works
1. Load or train the **SentenceTransformer** model for legal text embeddings.
2. Preprocess and store legal documents in vector format.
3. User inputs a legal query.
4. The system finds the most relevant legal sections using cosine similarity.
5. The user can select a section to receive a summarized version.


