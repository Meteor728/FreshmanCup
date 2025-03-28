# FreshmanCup
# 🌍 大语言模型（LLM）框架

![GitHub stars](https://img.shields.io/github/stars/yourusername/LLM-Project?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/LLM-Project?style=social)
![License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)

🚀 **大语言模型（LLM）框架**，支持 **多模态、RAG、多语言对话、记忆、提示词工程**，适用于 AI 开发者、研究人员和企业应用。

---

## 📖 **项目简介**
本项目是一个功能强大的 **大语言模型（LLM）**，主要特性包括：
- ✅ **多模态**（Multimodal）：支持文本、音频等多种数据输入
- ✅ **RAG（检索增强生成）**：结合知识库提高回答的准确性
- ✅ **多语言对话**（Multilingual）：支持 50+ 语言的跨语言交流
- ✅ **记忆**（Memory）：支持短期和长期记忆，提高对话连贯性
- ✅ **提示词工程**（Prompt Engineering）：优化提示词，提高生成质量

**📌 主程序文件**：`EventHandler.py`（核心控制逻辑）

---

## 📂 **文件结构**
```plaintext
LLM-Project/
│── Dataset/                    # 存放数据集
│── .gitattributes               # Git 属性配置
│── .gitignore                   # Git 忽略文件
│── EventHandler.py              # 主程序入口（核心控制逻辑）
│── PromptEngine.py              # 处理提示词优化
│── PromptLab.py                 # 提示词实验与测试
│── QueryEngine.py               # 处理查询和知识库检索（RAG）
│── README.md                    # 项目文档
│── Reranker.py                  # 重新排序检索结果，提高 RAG 质量
│── TextInputApp.py               # 终端/GUI 文本交互应用
│── api_request_schema.py         # API 请求结构定义
│── audio_bedrock_wrapper.py      # 处理音频输入（多模态）
│── check_model.py                # 模型完整性检查
│── debug.json                    # 调试信息
│── knowledge_base.py             # 知识库管理（RAG）
│── requirements.txt              # 依赖库
│── text_bedrock_wrapper.py       # 处理文本输入（多模态）
```
**📌 主程序文件**：`EventHandler.py`（核心控制逻辑）

## 📝 **各文件用途说明**
| 文件名 | 作用 |
|--------|----------------------------------|
| `EventHandler.py` | **主程序入口**，协调所有模块，执行核心逻辑 |
| `PromptEngine.py` | 处理提示词优化，提高 LLM 生成质量 |
| `PromptLab.py` | 提示词实验和测试平台 |
| `QueryEngine.py` | 处理查询、知识库检索（RAG） |
| `Reranker.py` | 重新排序检索结果，提高 RAG 生成质量 |
| `TextInputApp.py` | 提供终端/GUI 交互的文本应用 |
| `api_request_schema.py` | 定义 API 请求结构和数据格式 |
| `audio_bedrock_wrapper.py` | 处理音频输入，实现多模态交互 |
| `check_model.py` | 确保模型完整性，检测依赖 |
| `debug.json` | 调试配置文件 |
| `knowledge_base.py` | 处理知识库管理（RAG） |
| `text_bedrock_wrapper.py` | 处理文本输入，集成 LLM |

---

## 🛠 **安装与使用**
### 1️⃣ **安装依赖**
```sh

```
### 2️⃣ **运行主程序**
```sh
python EventHandler.py
```
---

## 🎯 **功能详解**
### 🧠 1.记忆（Memory）
- **短期记忆**：保持对话上下文，提高连贯性


---

###  :smile: 2.提示词工程（Prompt Engineering）
- **优化 LLM 提示词，提高生成质量**



---

### 🌍 3.多语言对话（Multilingual）
支持 **多种语言**，自动检测用户语言，实现流畅的跨语言交流。
- 用户输入语音->使用 ***Amazon Transcribe*** 服务转录（Speech To Text）-> 内容生成(Text To Text) -> 机器说话(使用Amazon Polly服务 Text To Speech)
- 配置 ***language_code*** 和 ***voiceIndex*** 两部分，提供用户选择语言的代码来实现不同语言对话
- 结果：实现中文、英文、日语、韩语等对话。
  

---

### 📚 4. RAG（检索增强生成）
结合知识库，提高回答的准确性和信息性。



---

### 🎨 5. 多模态（Multimodal）
支持 **文本、图片、音频** 等多种输入类型，实现更丰富的 AI 交互。



---
---

## 🚀 **加入我们**
📢 **关注最新动态，欢迎 Star ⭐️ 支持！**  
