Firstly, create a file called .env in this folder, and add the following content, obviously with your values:

OPENAI_API_KEY=xxxxxx
OPENAI_API_BASE=https://xxxxxxx.openai.azure.com/

OPENAI_DEPLOYMENT_NAME=xxxxxx
OPENAI_DEPLOYMENT_VERSION=xxxxxx
OPENAI_MODEL_NAME=xxxxxx

OPENAI_ADA_EMBEDDING_DEPLOYMENT_NAME=xxxxxx
OPENAI_ADA_EMBEDDING_MODEL_NAME=xxxxxx


Then, let's install all dependencies:

```
pip install -r ./requirements.txt
```

If you use VSCode, Install the extension `Jupyter Notebook Renderers`