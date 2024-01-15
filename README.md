**Build a AI Powered Chatbot with RAG(Retrieval augmented generation) Architecture pattern ***

Large language models (LLMs) have undoubtedly changed the way we interact with information. However, they come with their fair share of limitations as to what we can ask of them. Base LLMs ( gpt-4, etc.) are only aware of the information that they've been trained on and will fall short when we require them to know information beyond that. Retrieval augmented generation (RAG) based LLM applications address this exact issue and extend the utility of LLMs to our specific data sources. 

![image](https://github.com/umianta/Public/assets/241957/200a89a1-2812-4586-aace-b2e894a43fb5)


I've used the following components to build an AI-powered chatbot using the RAG Arch pattern:

1. Utilized the OpenAI embedding model to transform structured/unstructured data into vectors.
2. Used Pinecone Vector DB for storing these vectors.
3. Leveraged Microsoft Copilot Studio to build the AI-powered Chatbot.
4. Integrated Microsoft Power Flow to facilitate interaction with Pinecone DB and OpenAI APIs.
5. Incorporated OpenAI APIs for chatbot response summarization.
