# Gewu（格物）· AI 原生应用平台

**Gewu** 是一套前后端分离、开箱即用的企业级 AI 原生应用平台，基于 Apache-2.0 完全开源。

| 仓库 | 定位 | 技术栈 |
|---|---|---|
| [gewu](https://github.com/gewu-platform/gewu) | 后端服务 | Java 17 · Spring Boot 3 · LangChain4j · PostgreSQL/pgvector |
| [gewu-web](https://github.com/gewu-platform/gewu-web) | Web 前端 | Vue 3 · Vite 5 · Pinia |

## ✨ 核心能力

- 🤖 **Agent 编排**：模板向导（知识库问答 / 客服接待 / 通用助手）、工具调用、人工审批流
- 📚 **RAG 知识库**：md/txt/pdf/docx 异步索引，检索测试台相似度可视化
- 🧩 **Prompt 版本制**：模板自增版本、变量提取、一键回退
- 📊 **可观测**：调用链路 + 用量报表三视图（按天/用户/Agent）+ 用户级每日 token 配额
- ⚙️ **模型配置中心**：OpenAI 兼容多 Provider，密钥加密存储，保存即生效
- 🐳 **Docker Compose 一键部署**：nginx + server + pgvector

## 🚀 快速开始

从 [gewu 后端 README](https://github.com/gewu-platform/gewu#readme) 开始，两仓库 clone 后 3 条命令拉起全套。

---

**English**: Gewu is an open-source enterprise AI-native platform (Apache-2.0) — Agent orchestration with tool approval, RAG knowledge base, versioned prompts, usage analytics & token quotas. Backend: Java 17 + Spring Boot 3 + LangChain4j + pgvector. Frontend: Vue 3 + Vite 5. Start at the [backend README](https://github.com/gewu-platform/gewu#readme).
