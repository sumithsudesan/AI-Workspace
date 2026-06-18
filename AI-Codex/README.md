# 📚 AI-Codex

Welcome to **AI-Codex**, a centralized workspace and repository directory for my personal artificial intelligence projects. This repository functions as a monorepo, keeping different experiments, CLI tools, and agentic integrations cleanly organized within an interactive index.

---

## 🗺️ Project Directory

Below is the directory map of the AI utilities housed within this master repository. Each subfolder operates with isolated environment configurations and dependencies.

| Project Folder | Description | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| [📂 `okf-metadata-creator/`](./okf-metadata-creator/) | **Semantic Indexing Engine:** Maps repository code structures and extracts deeply nested Git dependencies into standardized Open Knowledge Format (OKF) metadata to help AI agents minimize hallucinations. | Python / Node.js, AST Parsing | 🚀 Active Development |
| [📂 `agent-query-bot/`](./agent-query-bot/) | **Placeholder:** Next concept in the pipeline. | TBD | 💡 Concept |

---

## 🌟 Featured Project: OKF Metadata Creator

### The Problem
When modern AI agents or developer copilots attempt to analyze a codebase, they are plagued by **context fragmentation**. They typically inspect surface-level files (`package.json`, `README.md`, `requirements.txt`) but remain completely blind to complex architecture and nested Git dependencies (`git+https://github.com/...`), resulting in wasted context windows and API halucinations.

### The Solution
This tool acts as a **semantic cartographer** for codebases. It automates:
1. **Ingestion:** Clones, tracks, and crawls hidden or nested Git dependencies.
2. **Analysis:** Leverages Abstract Syntax Trees (AST) to extract exposed interfaces, internal modules, and functional structures.
3. **Generation:** Packages the repository into structured, highly readable JSON/YAML outputs compliant with the Open Knowledge Format (OKF), offering immediate, concise operational roadmaps for LLMs.

---

