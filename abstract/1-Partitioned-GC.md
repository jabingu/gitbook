# Partitioned-GC

## QoS-Aware Flash Memory Controller

> 17RTAS
>
> Bryan S. Kim; Sang Lyul Min 
>
> Department of Computer Science and Engineering 
>
> Seoul National University
> {bryansjkim, symin}@snu.ac.kr 

**Abstract**— NAND flash memory has gained a lot of popularity in recent years, widely used in applications ranging from small mobile devices to high-performance enterprise-class storage. However, the variation and unpredictability of performance caused by concurrent flash translation layer (FTL) tasks in a flash storage system are not desirable qualities especially for real-time systems and make it difficult to guarantee the QoS of the storage system. In this paper we present a QoS-aware flash memory controller (QoSFC) designed for predictable performance. For the workload we consider, QoSFC improves not only the average response time by a factor of 12–38 for reads and 1.4–6.9 for writes, but also the 99.9% QoS by a factor of 29–56 for reads and 2.0–8.5 for writes. 

**说明：**

是在之前的切分GC，real time task GC 的基础上新提出的论文，主要是考虑了整体的Qos保证，内容上主要是提出了一个新的队列的策略。

**好的内容：** 