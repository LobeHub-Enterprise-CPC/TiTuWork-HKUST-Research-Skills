---
name: hkust-ngdbench-evaluation
description: 评估图数据管理、Text2Cypher 与 GraphRAG 的抗噪能力。用于用户明确提到 NGDBench 或对应科研复现任务时。
version: 1.0.0
license: MIT
category: research
author:
  name: TITU Work
  url: https://github.com/LobeHub-Enterprise-CPC
repository: https://github.com/LobeHub-Enterprise-CPC/TiTuWork-HKUST-Research-Skills
sourceUrl: https://github.com/HKUST-KnowComp/NGDBench
tags:
  - 香港科技大学
  - HKUST-KnowComp
  - 科研
  - 知识图谱
---

# NGDBench 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [NGDBench](https://github.com/HKUST-KnowComp/NGDBench)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

明确使用公开基准数据还是重建数据，并选定领域、噪声水平与任务类型。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

阅读原仓库和数据集说明；先核对数据来源及许可，再用小样本检查 Cypher 查询可执行性和答案格式。若需重建，按文档准备 Neo4j 5.x 与模型接口；评估结构化查询、非结构化查询和答案判定。

## 交付

按任务和噪声水平报告准确率、错误类别、数据版本及可复现配置。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

原仓库与数据集未声明许可证；本技能只指向来源，不包含或再分发代码与数据；重建流程可能产生模型费用。
