# LangChain basics

This repository contains small examples that demonstrate the basics of using
LangChain, including prompts, chat models, and output parsers.

## Setup

From the repository root, create and activate a Python virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows PowerShell, activate it with:

```powershell
.venv\Scripts\Activate.ps1
```

Install the project dependencies:

```bash
python -m pip install -r lang_chain/requirements.txt
```

## Configure environment variables

Create a local `.env` file from the example file:

```bash
cp lang_chain/.env.example lang_chain/.env
```

Update `.env` with your API key, API base URL, and `LLM_MODEL` value. The
`.env` file is ignored by Git; do not commit credentials to the repository.

## Run the example

After completing the setup, run the basic chain example:

```bash
cd lang_chain
python 01_langc_core_concept.py
```

If it returns a response, your environment and model configuration are ready.
