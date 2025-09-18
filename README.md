# 董老师的基础AI课 (基于Microsoft产品)

## 1. 简介
### 适用人群
- 所有人 

### 学习收获
- 掌握微软 AI 生态的核心工具与服务  
- 能够构建基础的 AI 应用（多轮对话、智能体、辅助编程工具）  
- 掌握 AI 与 GitHub 工作流结合的实践经验  

### 为什么需要学习
- AI 已成为开发与工作的核心生产力工具  
- 微软产品体系提供了从开发、托管到 AI 服务的完整链路  
- 通过实际案例快速上手，降低入门难度  

### 课程内容概览
- VS Code、GitHub、Azure AI Fountry、Copilot Studio的环境配置与使用  
- 从小程序到多轮对话系统的实战项目  
- AI 辅助开发（Vibe Coding、Copilot Studio）  

### 局限性
- 课程侧重入门，不涉及复杂算法或模型训练  
- 部分服务（如 GitHub Copilot、Azure AI Fountry和Copilot Studio）需要付费订阅或企业账号

---

## 2. 环境准备
### 必备条件
- Windows 10/11 或 macOS 环境  
- 稳定的网络（可访问 GitHub 与 Azure 服务）  
- Git 与 Node.js 基础环境  

### 工具安装清单
- **Visual Studio Code**  
- **GitHub 账号与 Git 工具**  
- **Azure AI Foundry** 订阅
- **Copilot Studio** 订阅
- **插件**

---

## 3. Visual Studio Code
### 什么是 VS Code
轻量级、跨平台的代码编辑器，支持丰富的插件与 AI 辅助开发功能。  

### 安装与配置
- 下载并安装 VS Code  
- 配置常用开发语言扩展（Python、JavaScript、C# 等）  

### 必备组件
- GitHub Copilot 插件  
- Azure AI Foundry 插件
- 中文插件
- 其他

---

## 4. GitHub
### 什么是 GitHub
全球最大的代码托管与协作平台，支持版本管理与开源协作。  

### 用途
- 托管代码与文档  
- 协作开发与分支管理  
- 自动化 CI/CD 工作流  

### 如何注册与配置
- 注册 GitHub 账号  
- 创建第一个仓库
- 在VS Code中打开库

---

## 5. Azure AI Foundry
### 什么是 Azure AI Foundry
微软提供的 AI 服务平台（包括 Azure OpenAI、模型管理、数据集成）。  

### 用途
- 提供 GPT/LLM 模型 API  
- 管理 AI 应用的生命周期  
- 支持企业级安全与合规  

### 如何获取 API
- 创建 Azure 账号  
- 在 Azure AI Foundry门户中启用LLM  
- 获取 API Key 与 Endpoint  

---

## 6. GitHub Copilot
### 什么是 GitHub Copilot
由 OpenAI Codex 驱动的 AI 编程助手。  

### 用途
- 辅助代码生成与优化  
- 提供实时编程建议  
- 提升开发效率  

### 收费与订阅
- 免费试用（学生/教育优惠）  
- 个人订阅 / 企业订阅模式  

### 环境配置
- 在 GitHub 账户中启用 Copilot  
- 在 VS Code 中安装并绑定 Copilot 插件  

### 使用模式
- **代码补全**  
- **Ask模式**
- **Edit模式**
- **Agent模式**  

---

## 7. 实战项目 1：生成彩票号码与俄罗斯方块
### 创建代码仓库
- 新建仓库  
- 使用分支进行开发  

### 项目一：彩票号码生成器
- 使用自然语言生成代码  
- 通过 LLM 优化逻辑  
- 输出结果到 Markdown 文档  
- 提交并上传至 GitHub  

### 项目二：俄罗斯方块游戏
- 使用自然语言生成初始版本  
- 通过 LLM 优化界面与逻辑  
- 输出Markdown文档  
- 提交并上传至 GitHub

---

## 8. 实战项目 2：多轮对话 AI 程序
### 模拟 Copilot 功能
- 简单代码补全与问答  

### LangChain 入门
- 介绍 LangChain 框架  
- 构建对话链路  

### 前端实现
- 调用 Azure AI Fountry API  
- 使用 HTML/JS 简单实现聊天界面  

### 后端与记忆存储
- Python/Node.js 服务端  
- 使用内存/数据库存储会话上下文  

---

## 9. Vibe Coding
### 概念
以“氛围驱动”的轻量化编程方式，让 AI 辅助开发更加沉浸。  

### 实践内容
- 仓库介绍与克隆  
- 项目汉化
- 项目说明  
- Step-by-Step 流程  
  - 文件结构  
  - 前端实现  
  - 后端实现  
  - 数据库实现  

---

## 10. 智能体与 Copilot Studio
### 什么是 Copilot Studio
微软提供的低代码 AI 应用构建工具，可快速生成智能体。  

### 与 Power Automate 的区别
- **Copilot Studio**：自然语言驱动、构建智能体对话流程  
- **Power Automate**：偏向自动化流程编排  

### 实战案例：请假与 HR 查询
- 构建请假申请智能体  
- 构建 HR 数据查询智能体  
- 集成 Teams / Outlook 使用  

---
