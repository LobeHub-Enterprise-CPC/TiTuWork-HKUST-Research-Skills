---
name: hkust-ceqa-event-query
description: 在事件知识图谱上评估复杂查询与隐式逻辑约束。用于用户明确提到 CEQA 或对应科研复现任务时。
version: 1.0.0
license: MIT
category: research
author:
  name: TITU Work
  url: https://github.com/LobeHub-Enterprise-CPC
repository: https://github.com/LobeHub-Enterprise-CPC/TiTuWork-HKUST-Research-Skills
sourceUrl: https://github.com/HKUST-KnowComp/CEQA
tags:
  - 香港科技大学
  - HKUST-KnowComp
  - 科研
  - 知识图谱
---

# CEQA 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [CEQA](https://github.com/HKUST-KnowComp/CEQA)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

准备 ASER-50K 数据、查询与目标模型，确认是复现实验还是分析新查询。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

按原仓库 README 检查训练和定理证明器依赖；先验证数据与答案过滤流程，再运行基线及约束增强方法，人工检查典型逻辑冲突。

## 交付

分别报告查询准确率、逻辑冲突率、数据版本和复现环境。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

数据和依赖版本需从原仓库核实；外链可能失效；模型答案需与逻辑约束分别验证。
