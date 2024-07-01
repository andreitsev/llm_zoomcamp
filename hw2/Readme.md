
1) 
```bash
docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
```

2) 
```bash
docker exec -it ollama bash
```

```bash
ollama pull gemma:2b
```

<img width="1202" alt="image" src="https://github.com/andreitsev/llm_zoomcamp/assets/122976308/0e86a634-6baf-4974-a141-8e7290a97b42">

