# RAG Experiment Pipeline

A comprehensive pipeline for evaluating Retrieval-Augmented Generation (RAG) systems using diverse embedding models, chunking strategies, and datasets. This project evaluates RAG based on metrics such as hit rate, MRR, relevancy, and faithfulness.

## Features

- **Flexible Embedding Models**: Supports multiple state-of-the-art embedding models.
- **Configurable Chunk Sizes**: Experiment with varying document chunk sizes.
- **Evaluation Metrics**: Hit Rate, Mean Reciprocal Rank (MRR), Faithfulness, and Relevancy.
- **Integration with LLMs**: Generate context-specific questions using LLMs.
- **Dataset Versatility**: Process and evaluate datasets from multiple domains (e.g., Psychology, Business).

## Usage

Configure the desired embedding models, chunk sizes, and datasets in RAGExperimentPipeline.
Upload the file to Google Collab, set your Groq API Key and start the expertiments.
Results will be saved in the Result/ directory as a CSV file.

## Configuration
The pipeline allows flexible configurations via the ExperimentConfig class:
- embedding_model: The name of the embedding model from HuggingFace to use (e.g., jinaai/jina-embeddings-v3).
- chunk_size: The size of document chunks (e.g., 128, 256).
- dataset_name: The dataset tag or domain (e.g., Psychology).
- llm_model: The language model for question generation (e.g., llama3-8b-8192).
