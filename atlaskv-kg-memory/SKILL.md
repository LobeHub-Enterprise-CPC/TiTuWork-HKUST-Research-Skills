---
name: hkust-atlaskv-kg-memory
description: 评估十亿级知识图谱键值增强大模型的方法。用于用户明确提到 AtlasKV 或对应科研复现任务时。
version: 1.0.0
license: MIT
category: research
author:
  name: TITU Work
  url: https://github.com/LobeHub-Enterprise-CPC
repository: https://github.com/LobeHub-Enterprise-CPC/TiTuWork-HKUST-Research-Skills
sourceUrl: https://github.com/HKUST-KnowComp/AtlasKV
tags:
  - 香港科技大学
  - HKUST-KnowComp
  - 科研
  - 知识图谱
---

# AtlasKV 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [AtlasKV](https://github.com/HKUST-KnowComp/AtlasKV)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

确定使用公开检查点还是重建 KG2KV，并确认模型许可、显存和数据存储空间。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

按原仓库 README 核对检查点与数据链接；先用小规模样本验证 KG2KV 格式、检索和生成，再复现显存占用与准确率对比；记录 Llama 授权状态。

## 交付

报告图谱规模、显存峰值、准确率、检索覆盖和与基线的同条件比较。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

20GB 左右 GPU、模型授权和外链数据是前置条件；本技能不下载或再分发权重与数据。
