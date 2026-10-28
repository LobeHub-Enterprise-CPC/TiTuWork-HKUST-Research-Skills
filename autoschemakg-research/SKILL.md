---
name: hkust-autoschemakg-research
description: 自动从文本构建知识图谱并评估 GraphRAG 问答。用于用户明确提到 AutoSchemaKG 或对应科研复现任务时。
---

# AutoSchemaKG 研究工作流

本技能由 TITU Work 编写，帮助研究者使用香港科技大学 HKUST-KnowComp 的 [AutoSchemaKG](https://github.com/HKUST-KnowComp/AutoSchemaKG)。它是研究流程指南，不是原项目的代码、数据集或 MCP 服务。

## 准备

选择一组已获授权的文档，记录语种、数量、预期实体类型及问答问题。开始前核对原仓库 README、许可证和当前依赖；如果资料或数据不可获取，说明缺口，不虚构运行结果。

## 执行

按仓库 README 核对当前 atlas-rag 安装与模型配置；先用小样本运行构图，再检查生成的实体、关系、概念 schema 与来源文本；确认质量后再扩大语料并运行 GraphRAG 问答。

## 交付

记录实体/关系数量、抽样错误、每条回答的证据来源及失败样例。说明哪些结果来自实际运行，哪些仅来自论文或仓库文档。

## 边界

模型接口可能产生费用；不得把私有语料提交到公共仓库；不要把生成的关系当作已证实事实。
