# SRMAP University ChatBot

A web scraping and semantic search system that collects data, processes it using deep learning embeddings, and provides an interactive interface for exploring the results.

## Description

This project is a comprehensive web scraping and data processing system that follows a sequential workflow:
1. Web scraping using `deep_scraper.py` to collect data
2. Processing and embedding the scraped data using `modified_embedder.py`
3. Generating FAISS index and metadata files
4. Visualizing and interacting with the processed data through a Gradio interface in the Jupyter notebook

## Core Technologies

- **Embedding Model:** all-MiniLM-L6-v2
- **LLM:** TinyLlama-1.1B
- **Vector Database:** FAISS

## Features

- Advanced web scraping with BeautifulSoup4 and aiohttp
- Deep learning-based text embedding using sentence-transformers
- Efficient similarity search with FAISS
- Gradio-based interactive interface
- Support for PDF processing with PyMuPDF
- Asynchronous processing for improved performance

## Requirements

- Python 3.8+
- PyTorch
- Transformers
- Sentence-transformers
- FAISS
- Gradio
- BeautifulSoup4
- aiohttp
- PyMuPDF
- Other dependencies listed in requirements.txt

## Installation

1. Clone the repository:

```bash
git clone [your-repository-url]
cd [repository-name]
```

2. Create a virtual environment (recommended):

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Project Structure

- `deep_scraper.py`: Initial web scraping module
- `modified_embedder.py`: Data processing and embedding module
- `University_Chatbot.ipynb`: Jupyter notebook containing the Gradio interface
- `requirements.txt`: Project dependencies

## Workflow

1. Run the web scraper to collect data:

```bash
python deep_scraper.py
```

2. Process the scraped data and generate embeddings:

```bash
python modified_embedder.py
```

3. Use the Provided Jupyter Notebook:

```bash
run all the cells in the Jupyter Notebook
```

## Data Files

The project uses the following data files:

- `srmap_metadata_deep.pkl`: Metadata storage
- `srmap_faiss_deep.index`: FAISS index for similarity search
- `srmap_data_deep.pkl`: Processed data storage

Note: These files are not included in the repository and should be generated during the first run.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

Srikar Mandava 
https://github.com/srikarr3
