> Don't use this repo for now. I will remove this comment when I consider it mature enough to be useful as a starting point for others

# Everything you need to run LLMs Locally

Running large language models (LLMs) on your own system can be surprisingly straightforward, provided you have the right tools. 

This repository is a personal testing space to run a local server to test out the LLMs and a very rich user interface for interacting with the LLMs.

Next up: setting up Visual Studio Code to integrate Ollama, code example for interacting with the backend APIs, etc

## Hardware Requirements

- CPU: At least Intel i7 4 cores
- RAM: 16GB
- GPU (VRAM): Not mandatory but you could be limitated to tiny LLM (depending of your CPU) 
- At least, 5 GB free space on your hard drive

## Stack 

- Server: [Ollama](https://ollama.com/)
  - With web search capability
- UI: [Open WebUI](https://docs.openwebui.com/)

## Some LLM Examples 

Without GPU:
- LLama 3.2 1B 
- qwen 2.5  0.5B

With 4GO VRAM (My current conf)
- Gemma 2B 
- LLama 3.2 3B 
- phi3.5 3B

And of course, you can really enjoy the experience with 8GB or more. Check Ollama for the list of available models. LLama 3.1 8B is definitely enough good to do a lot with, even with the 3B or 1B version.


Recommended readings: 
- [GPU support in Docker Desktop](https://docs.docker.com/desktop/gpu/)
- [How to run Ollama locally on GPU with Docker](https://medium.com/@srpillai/how-to-run-ollama-locally-on-gpu-with-docker-a1ebabe451e0)