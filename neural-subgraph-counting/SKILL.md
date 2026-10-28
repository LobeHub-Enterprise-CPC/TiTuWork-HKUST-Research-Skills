---
name: hkust-neural-subgraph-counting
description: 评估图神经网络近似子图同构计数。用于用户明确提到 NeuralSubgraphCounting 或对应科研复现任务时。
---

# NeuralSubgraphCounting 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [NeuralSubgraphCounting](https://github.com/HKUST-KnowComp/NeuralSubgraphCounting)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

提供模式图、目标图及可用于核对的小规模精确计数样本。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

按原仓库 README 检查 PyTorch、DGL、igraph 与 GPU 版本；先跑小样本数据生成和基线，再运行近似计数模型，核对精确计数与估计误差。

## 交付

记录数据划分、模型配置、误差分布、运行时间与失效的图结构。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

旧版 DGL 依赖可能与新环境不兼容；外链数据可能失效；估计值不是精确计数。
