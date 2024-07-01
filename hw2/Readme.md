
1) 
```bash
docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
```

2) 
```bash
docker exec -it ollama bash
```

```bash
ollama run phi3
```
