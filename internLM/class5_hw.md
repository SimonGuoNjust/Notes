# 书生浦语实战营-第四课作业
## 基础作业
使用LMDeploy部署InternLM-Chat-7B 模型。
1. 离线转换模型到lmdeploy TurboMind格式
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219162234.png)
2. 本地命令行调用TurboMind部署
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219162506.png)
 3.Gradio作为前端， TurboMind作为后端部署，二者直接连接
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219162925.png)

## 进阶作业
### 比较量化效果
1. 未量化时
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219171159.png)
2. 使用模型量化和KV_Cache量化后
	![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240219190528.png)
