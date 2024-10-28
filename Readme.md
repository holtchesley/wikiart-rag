# Setup

This uses ollama locally. Installation instructions are available at https://github.com/ollama/ollama .
After installation, I like to run it in it's own terminal window to ogle the logs: `ollama serve`
For this project, you'll need to pull llava-llama3: `ollama pull llava-llama3`

This uses virtual env
```
python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt
```
Should get all of the dependencies installed, and then a `jupyter notebook` will let you open up Rag.ipynb and poke around.

