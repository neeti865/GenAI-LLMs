# GenAI-learnings

This repositories contains: 

1. Code snippets to run some of the open source and API boxed LLMs including OpenAI, Llama2 
2. Usage of some of the frameworks for LLMs including Pinecone, Langchain
3. Efficient Finetuning on Llama2
4. Usage of RAG

   ## What is an LLM

   Large Langugae Models are a medium that depict the application and capability of Generative AI. These models are built on a humogous corpus of data which is trained on billions of parameters taking in a lot of compute. Some of the examples include OpenAi's ChatGPT, Llama2, Falcon et al. These models are prevalent today both in Open source and boxed format which are only accessible through APIs. LLMs are being used for a range of tasks such as answering questions, summarising documents, completing sentences, translating text, generating or explaining code, and more. Their performance is scaleble. That's fundamentally the difference between GPT-3 (175 billion parameters in its neural network) and GPT-4 (1 trillion parameters). Very large pre-trained language models like these can accurately predict text with just a handful of labeled examples. 

   ## What is PineCone

   The usage of LLMs in the applications largely depends on the ability to convert the unstructured data into vectors and then eventually store as embeddings. Pinecone is an open source project that makes life easier for data scientist and developers to acheive this goal. Its a easy to use management suite for maintaining of embeddings, vector stores and indexes.

   ## What is Langchain

   Langchain is another framework which is open source and has gained immense popularity on  teh grounds of bringing multiple LLMs access to one platform. It also abstracts some of the tasks for applicationd evelopments using LLMs like chunking, data loading, transformations, access to LLLms and much more.

   ## Open Source model used in this repo: Llama2 

![image](https://github.com/neeti865/GenAI-learnings/assets/20933728/674c9a48-b2d8-4ab6-a411-278f6a502360)


I specifically used Llama2 for my experiements because :

1. Community response to Llama2 as an incumbent to open source models category of LLMs has been good.
2. It is trained on diverse and extensive range of data making it much more performant and accurate in the NLP tasks
3. It is readily availabile for fine tuning on muiltuple platforms liek HuggingFace, Ludwig
4. There are multiple techniques availabel for efficient fien tuning using QLora and many other techniques
5. RAG process is also applicable to the same.

I'd like to explore all above and more in this repo to truly tap and apply the understanding on LLMs. this may serve useful to the community to understand the capabilities and lift and shift some of it to their own problems and coming up with solutions using the combination of learnings from the notebooks in this repo. 

.... Thanks 

