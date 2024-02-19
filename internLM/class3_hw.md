# 书生浦语实战营-第三课作业
## 基础作业
复现知识库助手搭建过程
1. 构建基于sentence_transformer的本地词向量数据库
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219101328.png)
2. 加载InternLM模型并构建检索问答链，比对大模型和检索问答链回答。
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219102705.png)
3. 部署web_demo
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219103406.png)

## 进阶作业
选择一个垂直领域，收集该领域的专业资料构建专业知识库，并搭建专业问答助手，并在 [OpenXLab](https://openxlab.org.cn/apps) 上成功部署
1. 克隆openmmlab系列仓库，如mmengine，mmcv等。
2. 基于仓库中的.md,..txt文件构建词向量数据库
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219140154.png)
3. 部署web，效果测试
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219135932.png)

5.  部署到openxlab
	由于openxlab镜像问题，sqlite3与开发机版本不一样导致数据库文件解码出错，需要在应用启动时构建词向量数据库，但应用的硬件资源不足，词向量数据库构建很慢。
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219140015.png)
