This is an AI chatbot built using Llama2 and Sentence Transformers. The bot is powered by Langchain and Chainlit. The bot runs on a decent CPU machine with a minimum of 16GB of RAM.

Data folder - this is the repository to store you own pdf for private knowledge base 
ingest.py - this file would ingest pdfs in the data folder and build a vector store database
    
run - chainlit run app.py -w

Note:
chainlit required latest version of langchain.

pip install langchain -- upgrade
or
python -m pip install --upgrade langchain[llm]

pip install chainlit