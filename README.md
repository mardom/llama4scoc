# llama4scoc
This code uses llama from huggingface to ingest pdf articles in the data directory (LSST SCOC papers as in this example).
and recalling LLM magic you could interact with them, just simply asking it questions about your papers corpus, enjoy!
## Installation 
Build up the conda environment with the provided yml file: conda env create --file=transformers.yml
This requires CUDA version 12.3 and related libraries, namely cudnn etc
The relevant library under the hood is llama-index: https://www.llamaindex.ai/
## Build up document corpus and query it
- Run the llama4scoc ipynb (for now using CPU for inference due to VRAM memory)
- Build up your complex query
