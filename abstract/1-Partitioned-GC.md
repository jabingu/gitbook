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

对之前的内论文进行说明

**B. Flash Translation Layer** 

Because of the impact GC has on overall performance, GC algorithms that provide real-time guarantee have been an active area of interest [10, 14, 15, 16]. While prior techniques focus on bounding the worst-case response time, our approach improves the overall QoS under sustained workloads. RTGC [10] is the first study on real-time garbage collection, but it requires file system support and its worst case performance is limited. GFTL [14] introduces the idea of partial garbage collection to reduce the worst case response time, but at the cost of reduced average response time. RFTL [15] improves both worst case and average case performance but requires a large amount of space overhead. WAO-GC [16] reduces this overhead, but its space overhead reduction depends on the program latency. With the current technology trend of increasing operation latencies in favor of higher density, the benefit of space overhead reduction in WAO-GC is limited. 

**C. Fair Scheduling** 

略