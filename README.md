# First approach to RAG: Extracting PDF file and chatting with it using RAG

LLAMAINDEX is a Python-based toolkit designed to facilitate advanced text extraction and URL parsing for document processing and information retrieval tasks. 
## Features

- **Text Extraction**: Automates the extraction of relevant information from a variety of document types.
- **URL Parsing**: Efficiently parses and processes URLs from text data to extract and organize web content.
- **Utils**: Function to merge PDFs

## Tokens
- [Llama](https://console.llama-api.com/account/api-token)
- [HuggingFace](https://huggingface.co/settings/tokens)
## Getting Started

- Install the repository using git clone command
- Enter into the folder using cd command
- Enter inside your prefered IDLE using code .
- To adapt your PDF to the dataset format and eventually to merge more than one PDFs use UrlParsing.ipynb
- To call the LLM and ask question to your PDF use Extraction.ipynb

### Prerequisites

All the needed libraries can be accessed through requirements.txt file. I suggest you to create a new environment through Conda to avoid discrepancies.

```bash
pip install -r requirements.txt
```
## Acknowledgments

Since I didn't find any citation reference, I'll link the [Youtube channel](https://www.youtube.com/@StatsWire/playlists) where I found a great playlist explaining everything regarding RAG, a big thanks to the author
