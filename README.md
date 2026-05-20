# Winona-Go-to-Sea-n8n-Agent
# 薇诺娜海外市场多智能体战略分析系统

---

## Project Overview | 项目概述


This project is a Multi-Agent AI workflow built with n8n for overseas market strategy planning and social media campaign generation.

The system transforms raw market research data into structured business intelligence and automatically generates region-specific market expansion strategies.

Instead of relying on a single LLM output, this workflow adopts a multi-agent architecture where different agents take responsibility for analysis, compliance validation, strategy formulation, and executive summarization.

Key target regions include:

- North America
- Southeast Asia

Final outputs include:

- Market insights
- Competitive analysis
- Localization strategy
- Social media campaigns
- Influencer strategies
- Executive-level reports

---


该项目是一个基于 n8n 构建的多智能体（Multi-Agent）海外市场战略分析系统，用于自动生成国际市场拓展和社交媒体营销方案。

系统将原始市场研究数据转换为结构化商业洞察，并自动输出针对不同区域的市场进入策略。

区别于单次大模型问答，该工作流采用多智能体架构，让不同 Agent 分别承担：

- 洞察提取
- 合规审查
- 战略制定
- 社交媒体规划
- 高层决策总结

目标市场包括：

- 北美市场
- 东南亚市场

输出结果包括：

- 市场洞察
- 竞争分析
- 本地化策略
- 社媒营销方案
- KOL合作策略
- 管理层决策报告

---

## Workflow Architecture | 工作流架构

```text
Google Sheets
        ↓

Data Structuring (JavaScript)
数据结构化处理

        ↓

Agent1
Insight Engine
洞察提取

        ↓

Agent1.5
Compliance Guard
合规过滤

        ↓

 ┌──────────────┐
 │              │
 ↓              ↓

Agent2         Agent3
NA Strategy    SEA Strategy

 ↓              ↓

Agent4         Agent5
NA Social      SEA Social

 └──────┬───────┘
        ↓

Merge Results

        ↓

Agent6
CMO Final Review

        ↓

Google Sheets Output
```

---

## Core Features | 核心功能


### Multi-Agent Collaboration

Different agents focus on specialized tasks:

- Insight extraction
- Compliance checking
- Regional strategy planning
- Social media generation
- Executive summarization

---

### Tool Calling

The workflow uses external tools such as:

- Calculator tool
- Google Sheets API
- LLM APIs

for automated computation and information processing.

---

### Structured Data Pipeline

Raw spreadsheet data:

→ cleaned  
→ transformed  
→ analyzed  
→ converted into strategy outputs

---

### Prompt Engineering

Each agent has:

- strict role definitions
- constraints
- output structure
- hallucination prevention rules

---

### 多智能体协同

不同 Agent 专注于不同职责：

- 洞察分析
- 合规审查
- 区域战略规划
- 社媒策略生成
- 管理层总结

---

### 工具调用能力

工作流集成：

- Calculator工具
- Google Sheets API
- 大模型API

实现自动计算与数据处理。

---

### 结构化数据流程

原始表格数据：

→ 清洗

→ 结构化

→ 分析

→ 策略输出

---

### Prompt工程设计

每个 Agent 都具有：

- 明确角色定义
- 行为约束
- 输出格式控制
- 幻觉控制机制

---

## Tech Stack | 技术栈

| Technology | Usage |
|---|---:|
| n8n | Workflow orchestration |
| JavaScript | Data preprocessing |
| Google Sheets API | Data storage |
| DeepSeek API | LLM inference |
| Gemini API | LLM inference |
| Multi-Agent Architecture | Task collaboration |

---

| 技术 | 用途 |
|---|---:|
| n8n | 工作流编排 |
| JavaScript | 数据预处理 |
| Google Sheets API | 数据管理 |
| DeepSeek API | 大模型调用 |
| Gemini API | 大模型调用 |
| Multi-Agent架构 | 智能协同 |

---

## Future Improvements | 后续优化


Possible future improvements:

- Add RAG knowledge retrieval
- Add memory mechanism
- Introduce autonomous planning
- Add visualization dashboard
- Support more international markets

---

未来可进一步优化：

- 增加 RAG 知识检索
- 引入记忆机制
- 增加自主任务规划
- 增加可视化仪表盘
- 扩展更多国际市场

---


## Author

Reese Tang
