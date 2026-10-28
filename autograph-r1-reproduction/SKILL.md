---
name: hkust-autograph-r1-reproduction
description: 复现以强化学习优化知识图谱构建的实验。用于用户明确提到 AutoGraph-R1 或对应科研复现任务时。
---

# AutoGraph-R1 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [AutoGraph-R1](https://github.com/HKUST-KnowComp/AutoGraph-R1)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

明确目标是阅读论文与配置审计、小规模推理，还是完整训练复现，并给出 GPU 预算。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

按仓库 README 锁定 PyTorch、VeRL、vLLM 等版本；先检查训练数据、奖励定义和 GraphRAG 评测，再运行仓库提供的小规模配置。仅在资源和数据都明确时启动训练。

## 交付

输出奖励项、基线、数据划分、训练曲线和下游问答差异。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

仓库中的 MCP 文件是研究代码所用的客户端/工具配置，不代表本项目提供可安装 MCP Server；完整训练算力需求高。
