Basic Chat with PDF using Streamlit, Ollama and Langchain and Langsmith

Install Ollama using Docker
 !docker run -d --gpus=all -v ollama:/root/.ollama -p 11435:11434 --name ollama ollama/ollama
-Add qwq and mxnai-embed-large models
 !docker exec -it ollama ollama run mxbai-embed-large
 !docker exec -it ollama ollama run qwq

 Create a virtual Environment 
 !python -m venv env
 !source env/bin/activate

 run app with this command:
 !streamlit run app.py
