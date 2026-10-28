---
name: hkust-efo1qa-benchmark
description: 运行存在一阶逻辑知识图谱查询基准。用于用户明确提到 EFO-1-QA-benchmark 或对应科研复现任务时。
---

# EFO-1-QA-benchmark 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [EFO-1-QA-benchmark](https://github.com/HKUST-KnowComp/EFO-1-QA-benchmark)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

确定待比较模型、KG 数据集、查询类型和评估拆分。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

阅读原仓库 README，确认 KGReasoning 子模块、数据集下载来源及许可；先对少量查询检查答案集合与训练/测试隔离，再按仓库脚本运行模型基线。

## 交付

按查询结构报告指标、样本量、随机种子、数据版本和失败案例。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

基准数据体积较大，外部下载链接可能失效；不同查询结构的结果不能简单混为一个分数。
