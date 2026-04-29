# Gov-Scholar-Agent

**Gov-Scholar-Agent** 是一个基于大语言模型（LLM）的多智能体协作系统，专门设计用于处理复杂的“治理现代化”领域学术文献，并自动化生成 2500 字以上的高质量学术报告。

## 🌟 核心功能
- **RAG 增强检索**：针对特定治理理论书籍（PDF/TXT）进行向量化索引，消除 AI 幻觉。
- **多智能体协作 (Multi-Agent)**：内置文献解析、逻辑推演、学术校对三个独立智能体。
- **长链推理 (CoT)**：通过链式思考生成深度逻辑大纲，确保长文本产出不偏离主题。

## 🏗️ 架构设计
项目采用模块化设计，通过 Python 实现智能体调度：
1. **Analyst Agent**: 负责从海量语料中提取关键政策导向与理论基点。
2. **Architect Agent**: 基于提取的观点，构建 2500 字规模的非线性逻辑架构。
3. **Refiner Agent**: 针对学术合规性、术语准确性进行终审润色。

## 🚀 快速开始
1. 配置 API Key: `export API_KEY='your_key'`
2. 安装依赖: `pip install -r requirements.txt`
3. 运行分析: `python main.py --topic "治理现代化与基层协作"`
