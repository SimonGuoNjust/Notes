# 书生浦语实战营-第三课笔记
[教程](https://github.com/InternLM/tutorial/blob/main/helloworld/hello_world.md)

RAG vs Finetune
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221102001.png)

使用internLM进行RAG的流程图
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221102054.png)

LangChain
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221102117.png)

构建向量数据库
- 根据源文件类型，如md，json等选用不同加载器去除其格式内容，变为无格式字符串
- 由于上下文长度限制，需要分割文件
- 使用embedding模型完成向量化
- 使用支持语义检索的数据库完成向量数据库构建
可以使用LangChain完成检索问答链的构建：自动知识检索，prompt填入，LLM问答
RAG的优化：
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221102433.png)

