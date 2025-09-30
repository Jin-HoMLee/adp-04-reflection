# adp-04-reflection

## Setup

### Virtual Environment 

Setup a virtual environment and install dependencies using:

```bash
pyenv local 3.13.5
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### APIs 

#### OpenAI API Key

In the root of this repository, create a `.env` file. Inside, paste your OpenAI API Key as: 

```OPENAI_API_KEY = "your-api-key"``` (just the key without the quotes)

