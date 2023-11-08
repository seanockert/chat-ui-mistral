# Chat interface for Mistral AI

A simple UI for chatting to [Mistral AI](https://mistral.ai/)

1. Install Mistral with Ollama. [Instructions here](https://ollama.ai/library/mistral)
2. Run Mistral with Ollama. To allow the app to run on your local network run the following command (replace the IP address with your own local IP): `OLLAMA_ORIGINS=http://192.168.1.3:* OLLAMA_HOST=192.168.1.3:11435 ollama serve` [see docs](https://github.com/jmorganca/ollama/blob/main/docs/faq.md#how-can-i-expose-ollama-on-my-network)
3. Edit the `API_BASE_URL` in the `index.html` to point to the URL that Ollama is running on
4. Open the `index.html` file in your browser and type your question. Alternatively, run the app with [Serve](https://www.npmjs.com/package/serve) 

<img width="641" alt="screenshot" src="https://github.com/seanockert/chat-ui-mistral/assets/574163/cbc71c61-00c4-425f-a01a-af38c034b16e">
