# auto-tune

Automatic tuning and optimization practices.

## 计算

优化（Optimization）：由程序驱动优化；调优（Tuning）：由人工驱动优化

### SQL引擎

- 基于规则的优化（RBO）：通过编程、关系代数等理论进行局部优化
- 基于成本的优化（CBO）：基于统计，通过启发式算法、增强学习进行优化
- 基于历史的优化（HBO）：基于历史运行状态，通过运筹规划、增强学习进行优化
- 自适应优化（Adapter）：基于运行时度量，自适应调整

### 数据存储

- 使用场景：Ad-hoc、OLAP、OLTP、HTAP
- 列存、向量化、冷热分级
- 空间换时间：预计算、索引

### 调度

- First Fitness
- 背包问题：贪心算法
- 规划问题：整数规划
- Graph Base（Firmament）
- 强化学习

## Reference
