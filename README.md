# RAG-Test


## FAISS 方法

***RAG-Test-KB.ipynb：*** 配合 rag-test-KB.json 文件，json 文件为一条一条的 Knowledge。

***RAG-Test-QA.ipynb：*** 配合 rag-test-QA.json 文件，json 文件为问答对。

***RAG文本信息检索.ipynb：*** 配合 test.docx 文档，使用 jieba 分词，并用 TF-IDF 方法将文本转换为向量表示，使用 FAISS 向量检索库，根据输入的关键词进行相似度检索，找到与查询最相关的句子。
