# Ollama-UI
A simple web interface to chat with Ollama models (LLaMA2, Mistral, Gemma, etc.) in your browser. Built so you can simply just open the page and connect to your local Ollama instance. Fast, minimal, and easy to modify.

## No Installation Required

As long as Ollama is running, you can access the page directly from your browser.

## Important

Just make sure Ollama is started with the proper CORS setting, and to do that you'll need to serve ollama with the following parameter:

```
OLLAMA_ORIGINS=* ollama serve
```

## Preview

<img width="1909" height="914" alt="image" src="https://github.com/user-attachments/assets/d597ce26-bc4b-4182-b246-4c163f6d7362" />
