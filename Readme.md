# [Книга][Дэнис Ротман] RAG и генеративный ИИ. Создаем собственные RAG-пайплайны с помощью LlamaIndex, Deep Lake и Pinecon [RUS, 2025]

**Оригинальные исходники:**  
https://github.com/Denis2054/RAG-Driven-Generative-AI


<img src="./img/cover.webp" alt="RAG и генеративный ИИ. Создаем собственные RAG-пайплайны с помощью LlamaIndex, Deep Lake и Pinecon" height="256px" align="right">


<br/>

### Описание

В книге описываются приемы создания эффективных больших языковых моделей, систем компьютерного зрения и генеративного ИИ, показывающих высокую производительность при относительно невысоких затратах. В ней приводится подробное исследование технологии RAG, а также подходов к проектированию мультимодальных пайплайнов ИИ и управлению ими. Связывая вывод с исходными документами, RAG повышает точность и контекстную релевантность результатов, предлагая динамический подход к управлению большими объемами информации.

Узнайте, как построить инфраструктуру RAG, попутно разобравшись с векторными хранилищами, фрагментацией, индексацией и ранжированием. Познакомьтесь с методами оптимизации производительности и приемами более глубокого изучения данных, включая использование адаптивного RAG и обратной связи от человека для уточнения поиска, тонкую настройку RAG, реализацию динамических RAG для поддержки принятия решений в реальном времени и визуализацию сложных данных с помощью графов знаний. Вы также увидите, как на практике объединить такие фреймворки, как LlamaIndex и Deep Lake, векторные базы данных наподобие Pinecone и Chroma и модели, предлагаемые компаниями Hugging Face и OpenAI. Приобретите навыки внедрения интеллектуальных решений, что повысит вашу конкурентоспособность в различных областях: от продакшна до обслуживания клиентов в любом проекте.


<details open> 
  <summary><h2>Key Learnings</summary>
<ul>

<li>Scale RAG pipelines to handle large datasets efficiently</li>
<li>Employ techniques that minimize hallucinations and ensure accurate responses</li>
<li>Implement indexing techniques to improve AI accuracy with traceable and transparent outputs</li>
<li>Customize and scale RAG-driven generative AI systems across domains</li>
<li>Find out how to use Deep Lake and Pinecone for efficient and fast data retrieval</li>
<li>Control and build robust generative AI systems grounded in real-world data</li>
<li>Combine text and image data for richer, more informative AI responses</li>
</ul>

  </details>

<details open> 
  <summary><h2>Chapters</summary>

**This repo is continually updated and upgraded.**    
📝 For details on updates and improvements, see the [Changelog](./CHANGELOG.md).    
🐬 *New bonus notebooks* to explore, see [Changelog](./CHANGELOG.md).     
🚩 If you see anything that doesn't run as expected, raise an issue, and we'll work on it!      

### Platforms
You can run the notebooks directly from the table below:
| Chapter | Colab | Kaggle | 
| :-------- | :-------- | :------- |
| | | | | |
**Part I The RAG Framework**
 **Chapter 1: Why Retrieval Augmented Generation(RAG)?**
| <ul><li>RAG_Overview.ipynb</a></li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter01/RAG_Overview.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter01/RAG_Overview.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> | 
**RAG overview with Elon Musk's xAI grok-beta LLM model**
| <ul><li>🐬RAG_Overview_Grok.ipynb with Elon Musk's xAI grok-beta</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter01/RAG_Overview_Grok.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter01/RAG_Overview_Grok.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 2, RAG Embeddings and Vector Stores with Deep Lake and OpenAI**
| <ul><li>1_Data_collection_preparation.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/1_Data_collection_preparation.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/1_Data_collection_preparation.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>2_Embeddings_vector_store.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/2_Embeddings_vector_store.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/2_Embeddings_vector_store.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>3_Augmented_Generation.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
**RAG with OpenAI Reasoning models: the o1-preview API**
| <ul><li>🐬3_Augmented_Generation_o1_preview.ipynb</a></li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation_o1_preview.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation_o1_preview.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> | 
**RAG with OpenAI Reasoning models: the o3 API**
| <ul><li>🐬3_Augmented_Generation_o3.ipynb</a></li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation_o3.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation_o3.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> | 
**RAG with OpenAI Agentic GPT-4.5-preview model:  API**
| <ul><li>🐬3_Augmented_Generation_GPT_4-5.ipynb</a></li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation_GPT_4-5.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter02/3_Augmented_Generation_GPT_4-5.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> | 
 **Chapter 3, Building Index-based RAG with LlamaIndex, Deep Lake, and OpenAI**
| <ul><li>Deep_Lake_LlamaIndex_OpenAI_RAG.ipynb</li></ul> | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter03/Deep_Lake_LlamaIndex_OpenAI_RAG.ipynb) | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter03/Deep_Lake_LlamaIndex_OpenAI_RAG.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 4, Multimodal Modular RAG for Drone Technology**
| <ul><li>Multimodal_Modular_RAG_Drones.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter04/Multimodal_Modular_RAG_Drones.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter04/Multimodal_Modular_RAG_Drones.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 5: Boosting RAG Performance with Expert Human Feedback**
| <ul><li>Adaptive_RAG.ipynb</li></ul> | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter05/Adaptive_RAG.ipynb) | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter05/Adaptive_RAG.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 6, Scaling RAG Bank Customer Data with Pinecone**
| <ul><li>Pipeline_1_Collecting_and_preparing_the_dataset.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter06/Pipeline_1_Collecting_and_preparing_the_dataset.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter06/Pipeline_1_Collecting_and_preparing_the_dataset.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>Pipeline_2_Scaling_a_Pinecone_Index.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter06/Pipeline_2_Scaling_a_Pinecone_Index.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter06/Pipeline_2_Scaling_a_Pinecone_Index.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>Pipeline_3_RAG_Generative_AI.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter06/Pipeline_3_RAG_Generative_AI.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter06/Pipeline_3_RAG_Generative_AI.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 7, Building Scalable Knowledge Graph-based RAG with Wikipedia and LlamaIndex**
| <ul><li>Tree_2_Graph.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter07/Tree_2_Graph.ipynb)| <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter07/Tree_2_Graph.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>Wikipedia_API.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter07/Wikipedia_API.ipynb)| <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter07/Wikipedia_API.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>Knowledge_Graph__Deep_Lake_LlamaIndex_OpenAI_RAG.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter07/Knowledge_Graph__Deep_Lake_LlamaIndex_OpenAI_RAG.ipynb)| <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter07/Knowledge_Graph__Deep_Lake_LlamaIndex_OpenAI_RAG.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 8, Dynamic RAG with Chroma and Hugging Face Llama**
| <ul><li>Dynamic_RAG_with_Chroma_and_Hugging_Face.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter08/Dynamic_RAG_with_Chroma_and_Hugging_Face.ipynb)| <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter08/Dynamic_RAG_with_Chroma_and_Hugging_Face.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 9, Empowering AI Models: Fine-Tuning RAG Data and Human Feedback**
| <ul><li>Fine_tuning_OpenAI_GPT-4o-mini.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter09/Fine_tuning_OpenAI_GPT-4o-mini.ipynb)| <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter09/Fine_tuning_OpenAI_GPT-4o-mini.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
 **Chapter 10, RAG for Video Stock Production with Pinecone and OpenAI**
| <ul><li>Video_dataset_visualization.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Video_dataset_visualization.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Video_dataset_visualization.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>Pipeline_1_Generator_and_Commentator.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Pipeline_1_Generator_and_Commentator.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Pipeline_1_Generator_and_Commentator.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>Pipeline_2_The_Vector_Store_Administrator.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Pipeline_2_The_Vector_Store_Administrator.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Pipeline_2_The_Vector_Store_Administrator.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |
| <ul><li>Pipeline_3_The_Video_Expert.ipynb</li> |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Pipeline_3_The_Video_Expert.ipynb)  | <a href="https://www.kaggle.com/kernels/welcome?src=https://github.com/Denis2054/RAG-Driven-Generative-AI/blob/main/Chapter10/Pipeline_3_The_Video_Expert.ipynb"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open In Kaggle"></a><br> |







</details>


<details open> 
  <summary><h2>Requirements for this book</summary>


You should have basic **Natural Processing Language** (**NLP**) knowledge and some experience with Python. Additionally, most of the programs in this book are provided as Jupyter notebooks. To run them, all you need is a free Google Gmail account, allowing you to execute the notebooks on Google Colaboratory’s free **virtual machine** (**VM**). You will also need to generate API tokens for OpenAI, Activeloop, and Pinecone.
You might require to download modules while running the notebooks or you can simply run the ``requirements_01.txt`` file in the ``env`` you create.
Some of the modules are as follows:

| Modules          | Version                             |
|------------------|-------------------------------------|
| `deeplake`       | `3.9.18 (with Pillow)`              |
| `openai`         | `1.40.3`                            |
| `transformers`   | `4.41.2`                            |
| `numpy`          | `>=1.24.1`                          |
| `deepspeed`      | `0.10.1`                            |

**Note:** This GitHub repository will be continually maintained and updated as the platforms evolve. As such, the versions will evolve in time in this repo so that you will always have access to state-of-art programs!

<details> 
  <summary><h2>Get to know Author</h2></summary>

_Denis Rothman_ graduated from Sorbonne University and Paris-Cité University, designing one of the first patented encoding and embedding systems and teaching at Paris-I Panthéon Sorbonne.He authored one of the first patented word encoding and AI bots/robots. He began his career delivering a **Natural Language Processing** (**NLP**) chatbot for Moët et Chandon(LVMH) and an AI tactical defense optimizer for Airbus (formerly Aerospatiale).
Denis then authored an AI optimizer for IBM and luxury brands, leading to an **Advanced Planning and Scheduling** (**APS**) solution used worldwide.
[LinkedIn](https://www.linkedin.com/in/denis-rothman-0b034043/)



</details>
<details> 
  <summary><h2>Other Related Books</h2></summary>
<ul>

  <li><a href="https://www.packtpub.com/en-us/product/transformers-for-natural-language-processing-and-computer-vision-9781805128724">Transformers for Natural Language Processing and Computer Vision, Third Edition, First Edition</a></li>

  <li><a href="https://www.packtpub.com/en-us/product/generative-ai-application-integration-patterns-9781835887608">Generative AI Application Integration Patterns, First Edition</a></li>
 
</ul>

</details>
