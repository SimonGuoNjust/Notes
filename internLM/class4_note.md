# 书生浦语实战营-第四课笔记

## Finetune的概念
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104351.png)
### 增量预训练
使基座模型学习到新领域的知识
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104916.png)

### 指令跟随
使模型学会跟随用户给出的指令，如回答问题，给出示范等等。
对话模板：
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104737.png)
指令跟随微调的方法：添加对话模板，只对答案计算损失
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104757.png)

## 微调算法
### LoRA
通过新增支路 adapter的方法实现训练
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221105056.png)
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221105108.png)

## XTuner介绍
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221105131.png)
