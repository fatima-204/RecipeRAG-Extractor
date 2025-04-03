# RecipeRAG-Extractor

Extracts structured recipes from PDFs using RAG architecture with FAISS indexing, HuggingFace embeddings, and Gemini LLM.

## Features
- PDF text extraction with layout filtering
- FAISS-based similarity search
- Recipe quality validation
- JSON output generation
- Dual mode operation (single query/whole PDF processing)

## Data Samples
- `Recipe_info.json` (example output)
- `Things mother used to make.pdf` (test input)

## Setup
1. Install requirements: `pip install -r requirements.txt`
2. Add Google API key in `.env`
3. Run notebooks:
   - `NOTEBOOK1.ipynb` for individual queries
   - `NOTEBOOK2ipynb` for full PDF processing
