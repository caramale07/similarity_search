# Similarity Search Algorithms

This repository contains Jupyter notebooks exploring various similarity search algorithms. The algorithms covered include:

1. **Jaccard Similarity:**
   - Measures the similarity between sets based on the size of their intersection relative to the size of their union.

2. **Levenshtein Distance:**
   - Calculates the minimum number of single-character edits required to transform one string into another, representing string similarity.

3. **TF-IDF (Term Frequency-Inverse Document Frequency):**
   - A numerical statistic that reflects the importance of a term in a document relative to a collection, commonly used in information retrieval and text mining.

4. **BM25 (Best Matching 25):**
   - An extension of TF-IDF that considers term saturation and document length normalization, often used in search engine ranking.

5. **Sentence-BERT (SBERT):**
   - Utilizes transformer-based models (e.g., BERT) to generate sentence embeddings, allowing for semantic similarity comparison between sentences.

6. **FAISS (Facebook AI Similarity Search):**
   - A library for efficient similarity search and clustering of dense vectors. It provides various indexing methods for fast and scalable nearest neighbor search.

### Notebooks:
- Each algorithm is implemented in a separate Jupyter notebook.
- Notebooks include explanations, code, and visualizations.
- The 'embeddings' folder contains pre-computed sentence embeddings, eliminating the need to run cells with sentence transformer models.

### Dataset:
- The 'sentences.txt' file contains the dataset of sentences used for testing the algorithms.

### How to Use:
1. Clone the repository: `git clone https://github.com/your-username/similarity-search-algorithms.git`
2. Open and run the Jupyter notebooks in your preferred environment.
3. Explore and experiment with different similarity search algorithms.

Feel free to provide feedback
