---
name: hkust-mne-multiplex-embedding
description: 复现多关系网络嵌入并评估链接预测。用于用户明确提到 MNE 或对应科研复现任务时。
version: 1.0.0
license: MIT
category: research
author:
  name: TITU Work
  url: https://github.com/LobeHub-Enterprise-CPC
repository: https://github.com/LobeHub-Enterprise-CPC/TiTuWork-HKUST-Research-Skills
sourceUrl: https://github.com/HKUST-KnowComp/MNE
tags:
  - 香港科技大学
  - HKUST-KnowComp
  - 科研
  - 知识图谱
---

# MNE 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [MNE](https://github.com/HKUST-KnowComp/MNE)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

整理包含关系类型、起点、终点、权重的边表，并分出训练与测试边。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

从原仓库 README 核对旧版 Python 依赖，先用仓库自带 Vickers 样例运行；记录网络层和节点映射，再以同一划分训练模型并评估每层链接预测。

## 交付

报告每层样本量、嵌入维度、随机种子、评估指标和可复现命令。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

该原仓库未声明开源许可证；本技能只引用仓库，不复制、再分发或修改其代码；旧依赖可能需隔离环境。
