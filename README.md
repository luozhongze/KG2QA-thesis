# KG2QA: Knowledge Graph-enhanced Retrieval-Augmented Generation for Communication Standards Question Answering

<div align="center">
  
*This is the **undergraduate thesis** of [Zhongze Luo](https://luozhongze.github.io), supervised by [Jian Wang](https://ccec.nefu.edu.cn/info/1043/1843.htm)* <br>
*You can view the thesis by this url* <br>
*[http://luozhongze.github.io/KG2QA](http://luozhongze.github.io/KG2QA)* <br>


🌲Northeast Forestry University, Harbin, China <br>
Email: luozhongze0928@foxmail.com <br>

</div>

There are numerous types of standards in the field of communication. The traditional consulting model has a long cycle and relies on the knowledge and experience of experts, making it difficult to meet the rapidly developing technical requirements. In view of the characteristics in the field of communication standards, this paper combines the methods of fine-tuning large language models and constructing knowledge graphs to implement an intelligent consultation and question-answering system for communication standards.

In this thesis, the LoRA low-rank adaptation method is adopted to fine-tune the large language model to enhance its semantic analysis ability for professional language understanding and targeted content generation. A well-designed ontology structure was proposed. With the assistance of a large language model, efficient recognition and extraction of entities and relations were carried out to construct a knowledge graph of the communication standard domain with high accuracy. The RAG intelligent consultation and question-answering system for retrieval enhancement generation was designed to achieve the organic integration of the fine-tuning model and the knowledge graph.

The experimental results show that after fine-tuning on the dataset of 6,587 question-answer pairs in the field of communication standards constructed in this thesis, Qwen2.5-7B-Instruct demonstrates excellent professional capabilities in the field of communication standards on the test set. BLEU-4 increases from 18.8564 to 66.8993, and evaluation indicators such as ROUGE also rise significantly. And it outperforms the fine-tuning effect of the comparison model Llama-3-8B-Instruct; Based on the ontology framework containing 6 entity attributes and 10 relation attributes, a knowledge graph of the communication standard domain containing 13,906 entities and 13,524 relations was constructed, demonstrating good query accuracy. The intelligent consultation and question-answering system enables the fine-tuned model on the server side to access the knowledge graph constructed on the local side. It conducts graph retrieval of key information first to help enhance the question-answering effect. Combined with web services and API interfaces, it achieves good results in terms of interaction experience and back-end access, and has good practical application value.

<div align="center">
