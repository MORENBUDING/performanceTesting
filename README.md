# performanceTesting

## 衡量性能的指标

1. 响应时间（Response Time）

2. 吞吐量（Throughput）

   提高吞吐量的架构CQRS

3. 并发量（Concurrency）

## 性能质量

1. 问题重现（Reproduce）

   - 数据量（Data Volume）

   - 数据分布（Data Distribution）

   - 真实应用场景（latency）

2. 解决方法（Resolve）

   常见优化策略（Strategy）：

   - 预加载（Preload）
   - 延迟加载（Lazyload）
   - 批处理（Batch）：提高读写、更新速度

3. 回归（Regression）

## 产品前期，提前预知性能

1. Code Review
2. Testing
   - 压力测试（Stress）：系统临界点/上限
   - 负载测试（Load Testing）：在一定负载下，找出系统瓶颈
   - 数据量（Volume）
   - 耐久测试（Endurance Testing）：真实应用场景下可以运行多久

##持续监控（Monitering）

生产环境前，设置一个baseline，进行观察检测，生成一个可视化报告，有利于整个团队了解系统当前性能状况。
1. QA or Test Env
2. Setup Alert
3. Generate Reporting（）

## 工具（Tools）


|   GA    |  Splunk  | Nagios |
| :-----: | :------: | :----: |
| 端到端测试工具 | 后端（日志分析） |   硬件   |



| Gatting | JMeter | The Grinder |
| :-----: | :----: | :---------: |
|  负载测试   |  性能测试  |  一个轻量级测试工具  |

