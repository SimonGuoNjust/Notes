# 书生浦语实战营-第五课笔记

![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221103628.png)
**如何优化大模型的内存开销，加速推理速度，提升整体吞吐？**
模型并行，低比特量化，计算和访存优化等

## LMDeploy的特点
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221103900.png)

量化性能对比
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221103927.png)

weight-only量化的作用
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221103949.png)
降低访存成本，降低显存占用

LMDeploy使用AWQ算法
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104032.png)

### TurboMind推理引擎
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104120.png)
#### 持续批处理
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104148.png)
#### 有状态推理
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104206.png)

#### Blocked K/V Cache
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104235.png)

#### 高性能cuda kernel
![image.png](https://obsidiansycn.oss-cn-nanjing.aliyuncs.com/images/20240221104301.png)

### api server