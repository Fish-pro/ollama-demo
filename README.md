# ollama-demo

## install ollama

1.Pull ollama image

```sh
docker pull ollama/ollama
```

2.Run the ollama container

```sh
docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
```

3.Run the llama3 model

```sh
docker exec -it ollama ollama run llama3
```
