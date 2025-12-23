# Quantum NLP Sentence Similarity

This project explores a hybrid classical–quantum approach to natural language processing (NLP) by computing semantic similarity between words and sentences using quantum machine learning techniques.

Traditional NLP systems represent text as high-dimensional embeddings and measure similarity using classical metrics such as cosine similarity. In this project, Transformer-based language models are used to generate sentence embeddings, which are then encoded into quantum feature maps. A quantum kernel is applied to measure similarity based on the overlap of quantum states.

## Approach

1. Generate sentence embeddings using a pretrained Transformer model.
2. Reduce and normalize embeddings to a fixed number of features suitable for quantum circuits.
3. Encode features into quantum states using a ZZFeatureMap.
4. Compute similarity using a quantum kernel evaluated on a quantum simulator.
5. Normalize kernel outputs to obtain interpretable similarity scores.

This hybrid pipeline demonstrates how quantum algorithms can be integrated with modern NLP and large language model (LLM) embeddings.

## Technologies Used

- Python
- NumPy
- PyTorch
- Hugging Face Transformers
- Qiskit
- Qiskit Machine Learning
- Quantum circuit simulation via Qiskit Aer / BasicAer

## Example Use Case

The system can be used to:
- Compare semantic similarity between two sentences
- Generate a pairwise similarity matrix for a set of sentences
- Explore quantum-enhanced approaches to NLP tasks such as clustering and classification

## Motivation

Language embeddings are high-dimensional and complex. Quantum systems naturally operate in exponentially large vector spaces, making them a promising platform for future NLP and machine learning applications. This project serves as an exploratory step toward quantum-enhanced semantic analysis.

## Status

This project is intended for educational and research exploration and runs on simulated quantum hardware.

