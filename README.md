# Research-Paper-Summarizer-LLM-SerpAPI
A Python notebook that leverages Large Language Models (LLMs), Serp API, and other useful libraries to summarize research papers from Bibtex files. 

This Jupyter Notebook analyzes a collection of research documents to identify main topics and authors. The notebook uses BibTeX format to extract metadata from each document, and SerpAPI to search the download URL for each document. Documents are downloaded and summarized using LLMChain. Authors, institutions, as well as other principal documents associated with the topic of each document are identified using SerpAPI. A final report is generated.

## Usage

To use this notebook, first install all required libraries listed in the requirements.txt file by running:

```
pip install -r requirements.txt
```

Then open the notebook in Jupyter and run each cell in order. Make sure to update the variables path_bibtex_file and path_download_files to point to the correct file paths on your system. You can find test BibTeX files in the folder test-data.

## Requirements

Python: 3.10

These are the libraries required to run the notebook:

* bibtexparser==1.4.0
* fqdn==1.5.1
* google-search-results==2.4.2
* httptools==0.6.0
* isoduration==20.11.0
* jsonpointer==2.4
* langchain==0.0.234
* openai==0.27.8
* pip==22.0.2
* PyMuPDF==1.22.5
* python-dotenv==1.0.0
* requests==2.31.0
* setuptools==59.6.0
* tiktoken==0.4.0
* uri-template==1.3.0
* uvloop==0.17.0
* watchfiles==0.19.0
* webcolors==1.13
* websockets==11.0.3

## License

This notebook is licensed under MIT. Please see the LICENSE file for more information.

---
