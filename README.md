# MaximusLLM

## Overview
Brief description of your project.

## Setup

### Conda Environment
```bash
conda env create -f environment.yml
conda activate MaximusLLM
```

### Pip Environment
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage
```bash
cd ollama/
(python) huggingface-cli download awels/maximusLLM-phi3-128k-3b-v0.1-gguf maximusLLM-phi3-128k-3b-v0.1.gguf --local-dir .
ollama create maximusLLM-phi3-128k -f Modelfile -q q8_0
```
