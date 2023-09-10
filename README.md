# GenAI-learnings

This repositories contains: 

1. Code snippets to run some of the open source and API boxed LLMs including OpenAI, Llama2 
2. Usage of some of the frameworks for LLMs including Pinecone, Langchain
3. Efficient Finetuning on Llama2
4. Usage of RAG

   ## What is an LLM

   Large Langugae Models are a medium that depict the application and capability of Generative AI. These models are built on a humogous corpus of data which is trained on billions of parameters using deep learning techniques and taking in a lot of compute. Some of the examples include OpenAi's ChatGPT, Llama2, Falcon et al. Some models are Open source whereas others are accessible through APIs. LLMs are being used for a range of tasks such as answering questions, summarising documents, completing sentences, translating text, generating or explaining code, and more. Their performance is scalable. That's fundamentally the difference between GPT-3 (175 billion parameters in its neural network) and GPT-4 (1 trillion parameters). Very large pre-trained language models like these can accurately predict/ generate text with just a handful of labeled examples. Some of the common players explained as below: 

   ## PineCone

   The usage of LLMs in the applications largely depends on the ability to convert the unstructured data into vectors and then eventually store as embeddings. Pinecone is an open source project that makes life easier for data scientist and developers to acheive this goal. Its a easy to use management suite for maintaining of embeddings, vector stores and indexes. This helps in building NLP applications for a variety of use cases semantic search, search for text, visuals and audio, recommendar systems, customer chat assisstants et al. 

   ## Langchain

   Langchain is another framework which is open source and has gained immense popularity on  teh grounds of bringing multiple LLMs access to one platform. It also abstracts some of the tasks for applicationd evelopments using LLMs like chunking, data loading, transformations, access to LLLms and much more.

   ## RAG - Retrieval Augmented Generation allows for adding new data or rather keep the LLM up to date with latest/new information without having to finetune it.

   ## Open Source model used in this repo: Llama2 

![image](https://github.com/neeti865/GenAI-learnings/assets/20933728/674c9a48-b2d8-4ab6-a411-278f6a502360)


I specifically used Llama2 for my experiements because :

1. Community response to Llama2 as an incumbent to open source models category of LLMs has been good.
2. It is trained on diverse and extensive range of data making it much more performant and accurate in the NLP tasks
3. It is readily availabile for fine tuning using muiltuple platforms like HuggingFace, Ludwig and on your local machine too. You need > 10 GB RAM and >= RTX3070 series GPU
4. There are multiple techniques available for efficient fine tuning using QLora et al. (I have a notebook from one of the webinars I attended in this repo which throws light on efficient fine tuning of Llama2 locally with your own data) 
5. RAG process is also applicable to the same.

I'd like to explore all above and more in this repo to truly tap and apply the understanding on LLMs. This may serve useful to the community to understand the capabilities and lift and shift some of it to their own problems and coming up with solutions using the combination of learnings from the notebooks in this repo. 


