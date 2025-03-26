# 🧬 Introduction to NLP for Life Sciences

A practical introduction to Natural Language Processing techniques applied to biomedical literature using the CORD-19 dataset.

## 📋 Description

This repository contains a Jupyter notebook that demonstrates various NLP techniques for analyzing biomedical literature, specifically focused on COVID-19 research papers from the CORD-19 dataset. The notebook provides a step-by-step guide to implementing and understanding different NLP approaches, from basic text preprocessing to advanced semantic search using BERT embeddings.

## ✨ Features

- **Text Preprocessing**: Clean and prepare biomedical text data for analysis
- **Language Detection**: Identify and filter articles by language
- **Regular Expression Heuristics**: Extract specific patterns like clinical trial identifiers
- **Word Clouds**: Visualize dominant terms in the corpus
- **N-gram Analysis**: Explore common multi-word phrases in the literature
- **Topic Modeling**: Discover latent topics using Latent Dirichlet Allocation (LDA)
- **Semantic Search**: Implement BERT-based search functionality to find relevant articles

## 🔧 Prerequisites

- Python 3.6+
- Jupyter Notebook or Google Colab
- Basic understanding of NLP concepts and Python programming

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/intro_nlp_life_sciences.git
   cd intro_nlp_life_sciences
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook "Introduction to NLP for life sciences.ipynb"
   ```

4. If using Google Colab, upload the notebook and CSV files to your Google Drive.

5. Adjust the file paths in the notebook if necessary:
   ```python
   # Change this line to point to your CSV file
   my_articles = pd.read_csv('cord19-subset-500.csv')
   ```

## 📊 Dataset

The repository includes two subsets of the CORD-19 (COVID-19 Open Research Dataset):

- `cord19-subset-100.csv`: A smaller subset with 100 research papers
- `cord19-subset-500.csv`: A larger subset with 500 research papers

Each CSV file contains the following columns:
- `paper_id`: Unique identifier for each paper
- `title`: Title of the research paper
- `body_text`: Full text content of the paper
- `journal`: Journal where the paper was published

## 📚 Resources

- [CORD-19 Dataset](https://www.semanticscholar.org/cord19)
- [ScispaCy Documentation](https://allenai.github.io/scispacy/)
- [Sentence Transformers Documentation](https://www.sbert.net/)
- [FAISS Documentation](https://github.com/facebookresearch/faiss)

## 📄 License

This project is available for educational and research purposes.
