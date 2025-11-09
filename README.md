<a id="readme-top"></a>

<!-- [![Contributors][contributors-shield]][contributors-url] -->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
<!-- [![LinkedIn][linkedin-shield]][linkedin-url] -->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/lfnovo/open-notebook">
    <img src="docs/assets/hero.svg" alt="Logo">
  </a>

  <h3 align="center">Open Notebook</h3>

  <p align="center">
    一个开源的、注重隐私的 Google Notebook LM 替代方案！
    <br /><strong>加入我们的 <a href="https://discord.gg/37XJPXfz2w">Discord 服务器</a>获取帮助、分享工作流想法和建议功能！</strong>
    <br />
    <a href="https://www.open-notebook.ai"><strong>查看我们的网站 »</strong></a>
    <br />
    <br />
    <a href="docs/getting-started/index.md">📚 快速开始</a>
    ·
    <a href="docs/user-guide/index.md">📖 用户指南</a>
    ·
    <a href="docs/features/index.md">✨ 功能特性</a>
    ·
    <a href="docs/deployment/index.md">🚀 部署</a>
  </p>
</div>

<p align="center">
<a href="https://trendshift.io/repositories/14536" target="_blank"><img src="https://trendshift.io/api/badge/repositories/14536" alt="lfnovo%2Fopen-notebook | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>
</p>

<div align="center">
  <!-- Keep these links. Translations will automatically update with the README. -->
  <a href="https://zdoc.app/en/lfnovo/open-notebook">English</a> | 
  <a href="https://zdoc.app/de/lfnovo/open-notebook">Deutsch</a> | 
  <a href="https://zdoc.app/es/lfnovo/open-notebook">Español</a> | 
  <a href="https://zdoc.app/fr/lfnovo/open-notebook">français</a> | 
  <a href="https://zdoc.app/ja/lfnovo/open-notebook">日本語</a> | 
  <a href="https://zdoc.app/ko/lfnovo/open-notebook">한국어</a> | 
  <a href="https://zdoc.app/pt/lfnovo/open-notebook">Português</a> | 
  <a href="https://zdoc.app/ru/lfnovo/open-notebook">Русский</a>
</div>

## 私有化、多模型、100% 本地部署的全功能 Notebook LM 替代方案

![New Notebook](docs/assets/asset_list.png)

在一个由人工智能主导的世界里，拥有思考 🧠 和获取新知识 💡 的能力不应该是少数人的特权，也不应该被限制在单一服务提供商。

**Open Notebook 赋予您以下能力：**
- 🔒 **掌控您的数据** - 保持您的研究私密和安全
- 🤖 **选择您的 AI 模型** - 支持 16+ 个提供商，包括 OpenAI、Anthropic、Ollama、LM Studio 等
- 📚 **组织多模态内容** - PDF、视频、音频、网页等
- 🎙️ **生成专业播客** - 高级多说话人播客生成
- 🔍 **智能搜索** - 跨所有内容的全文和向量搜索
- 💬 **上下文对话** - 由您的研究支持的 AI 对话

在 [https://www.open-notebook.ai](https://www.open-notebook.ai) 了解更多关于我们项目的信息

---

## ⚠️ 重要：v1.0 重大变更

**如果您正在从旧版本升级**，请注意：

- 🏷️ **Docker 标签已更改**：`latest` 标签现在**冻结**在最后一个 Streamlit 版本
- 🆕 **使用 `v1-latest` 标签**获取新的 React/Next.js 版本（推荐）
- 🔌 **需要端口 5055**：您必须暴露端口 5055 以使 API 正常工作
- 📖 **阅读迁移指南**：查看 [MIGRATION.md](MIGRATION.md) 获取详细的升级说明

**新用户**：您可以忽略此通知，直接使用下面的快速开始指南，使用 `v1-latest-single` 标签。

---

## 🆚 Open Notebook vs Google Notebook LM

| 功能 | Open Notebook | Google Notebook LM | 优势 |
|---------|---------------|--------------------|-----------|
| **隐私与控制** | 自托管，您的数据 | 仅限 Google 云 | 完全的数据主权 |
| **AI 提供商选择** | 16+ 个提供商（OpenAI、Anthropic、Ollama、LM Studio 等） | 仅限 Google 模型 | 灵活性和成本优化 |
| **播客说话人** | 1-4 个说话人，可自定义配置 | 仅限 2 个说话人 | 极致灵活性 |
| **上下文控制** | 3 个细粒度级别 | 全有或全无 | 隐私和性能调优 |
| **内容转换** | 自定义和内置 | 有限选项 | 无限处理能力 |
| **API 访问** | 完整的 REST API | 无 API | 完全自动化 |
| **部署** | Docker、云或本地 | 仅限 Google 托管 | 随处部署 |
| **引用** | 带来源的全面引用 | 基本参考 | 研究完整性 |
| **定制化** | 开源，完全可定制 | 封闭系统 | 无限扩展性 |
| **成本** | 仅支付 AI 使用费用 | 月度订阅 + 使用费 | 透明且可控 |

**为什么选择 Open Notebook？**
- 🔒 **隐私优先**：您的敏感研究完全私密
- 💰 **成本控制**：选择更便宜的 AI 提供商或使用 Ollama 本地运行
- 🎙️ **更好的播客**：完全的脚本控制和多说话人灵活性 vs 有限的 2 说话人深度对话格式
- 🔧 **无限定制**：根据需要修改、扩展和集成
- 🌐 **无供应商锁定**：切换提供商，随处部署，拥有您的数据

### 技术栈

[![Python][Python]][Python-url] [![Next.js][Next.js]][Next-url] [![React][React]][React-url] [![SurrealDB][SurrealDB]][SurrealDB-url] [![LangChain][LangChain]][LangChain-url]

## 🚀 快速开始

**可用的 Docker 镜像：**
- **Docker Hub**：`lfnovo/open_notebook:v1-latest-single`
- **GitHub 容器注册表**：`ghcr.io/lfnovo/open-notebook:v1-latest-single`

两个注册表包含相同的镜像 - 选择您喜欢的任何一个！

### 选择您的设置：

<table>
<tr>
<td width="50%">

#### 🏠 **本地机器设置**
如果 Docker 运行在您将访问 Open Notebook 的**同一台计算机**上，则非常适合。

```bash
mkdir open-notebook && cd open-notebook

docker run -d \
  --name open-notebook \
  -p 8502:8502 -p 5055:5055 \
  -v ./notebook_data:/app/data \
  -v ./surreal_data:/mydata \
  -e OPENAI_API_KEY=your_key_here \
  -e SURREAL_URL="ws://localhost:8000/rpc" \
  -e SURREAL_USER="root" \
  -e SURREAL_PASSWORD="root" \
  -e SURREAL_NAMESPACE="open_notebook" \
  -e SURREAL_DATABASE="production" \
  lfnovo/open_notebook:v1-latest-single
```

**访问地址：** http://localhost:8502

</td>
<td width="50%">

#### 🌐 **远程服务器设置**
用于服务器、树莓派、NAS、Proxmox 或任何远程机器。

```bash
mkdir open-notebook && cd open-notebook

docker run -d \
  --name open-notebook \
  -p 8502:8502 -p 5055:5055 \
  -v ./notebook_data:/app/data \
  -v ./surreal_data:/mydata \
  -e OPENAI_API_KEY=your_key_here \
  -e API_URL=http://YOUR_SERVER_IP:5055 \
  -e SURREAL_URL="ws://localhost:8000/rpc" \
  -e SURREAL_USER="root" \
  -e SURREAL_PASSWORD="root" \
  -e SURREAL_NAMESPACE="open_notebook" \
  -e SURREAL_DATABASE="production" \
  lfnovo/open_notebook:v1-latest-single
```

**将 `YOUR_SERVER_IP` 替换**为您的服务器 IP（例如，`192.168.1.100`）或域名

**访问地址：** http://YOUR_SERVER_IP:8502

</td>
</tr>
</table>

> **⚠️ 关键设置注意事项：**
>
> **两个端口都是必需的：**
> - **端口 8502**：Web 界面（您在浏览器中看到的）
> - **端口 5055**：API 后端（应用程序正常运行所需）
>
> **API_URL 必须与您访问服务器的方式匹配：**
> - ✅ 通过 `http://192.168.1.100:8502` 访问 → 设置 `API_URL=http://192.168.1.100:5055`
> - ✅ 通过 `http://myserver.local:8502` 访问 → 设置 `API_URL=http://myserver.local:5055`
> - ❌ 不要为远程服务器使用 `localhost` - 从其他设备无法工作！

### 使用 Docker Compose（推荐用于简化管理）

创建一个 `docker-compose.yml` 文件：

```yaml
services:
  open_notebook:
    image: lfnovo/open_notebook:v1-latest-single
    # 或使用：ghcr.io/lfnovo/open-notebook:v1-latest-single
    ports:
      - "8502:8502"  # Web UI
      - "5055:5055"  # API（必需！）
    environment:
      - OPENAI_API_KEY=your_key_here
      # 对于远程访问，取消注释并设置您的服务器 IP/域名：
      # - API_URL=http://192.168.1.100:5055
      # 数据库连接（单容器必需）
      - SURREAL_URL=ws://localhost:8000/rpc
      - SURREAL_USER=root
      - SURREAL_PASSWORD=root
      - SURREAL_NAMESPACE=open_notebook
      - SURREAL_DATABASE=production
    volumes:
      - ./notebook_data:/app/data
      - ./surreal_data:/mydata
    restart: always
```

启动命令：`docker compose up -d`

**将创建以下内容：**
```
open-notebook/
├── docker-compose.yml # 您的配置
├── notebook_data/     # 您的笔记本和研究内容
└── surreal_data/      # 数据库文件
```

### 🆘 快速故障排除

| 问题 | 解决方案 |
|---------|----------|
| **"无法连接到服务器"** | 设置 `API_URL` 环境变量以匹配您访问服务器的方式（参见上面的远程设置） |
| **空白页面或错误** | 确保在您的 docker 命令中暴露了两个端口（8502 和 5055） |
| **在服务器上工作但从其他计算机无法访问** | 不要在 `API_URL` 中使用 `localhost` - 使用您服务器的实际 IP 地址 |
| **"404" 或 "config endpoint" 错误** | 不要在 `API_URL` 中添加 `/api` - 只使用 `http://your-ip:5055` |
| **仍有问题？** | 查看我们的 [5 分钟故障排除指南](docs/troubleshooting/quick-fixes.md) 或 [加入 Discord](https://discord.gg/37XJPXfz2w) |

### Open Notebook 工作原理

```
┌─────────────────────────────────────────────────────────┐
│  您的浏览器                                              │
│  访问：http://your-server-ip:8502                       │
└────────────────┬────────────────────────────────────────┘
                 │
                 ▼
         ┌───────────────┐
         │   端口 8502   │  ← Next.js 前端（您看到的）
         │    前端       │    也在内部代理 API 请求！
         └───────┬───────┘
                 │ 代理 /api/* 请求 ↓
                 ▼
         ┌───────────────┐
         │   端口 5055   │  ← FastAPI 后端（处理请求）
         │     API       │
         └───────┬───────┘
                 │
                 ▼
         ┌───────────────┐
         │   SurrealDB   │  ← 数据库（内部，自动配置）
         │  （端口 8000） │
         └───────────────┘
```

**关键点：**
- **v1.1+**：Next.js 自动将 `/api/*` 请求代理到后端，简化了反向代理设置
- 您的浏览器从端口 8502 加载前端
- 前端需要知道在哪里找到 API - 远程访问时，设置：`API_URL=http://your-server-ip:5055`
- **使用反向代理？**现在您只需要代理到端口 8502！查看[反向代理指南](docs/deployment/reverse-proxy.md)

## Star 历史

[![Star History Chart](https://api.star-history.com/svg?repos=lfnovo/open-notebook&type=date&legend=top-left)](https://www.star-history.com/#lfnovo/open-notebook&type=date&legend=top-left)

### 🛠️ 完整安装
用于开发或定制：
```bash
git clone https://github.com/lfnovo/open-notebook
cd open-notebook
make start-all
```

### 📖 需要帮助？
- **🤖 AI 安装助手**：我们有一个[定制 GPT 帮助您安装 Open Notebook](https://chatgpt.com/g/g-68776e2765b48191bd1bae3f30212631-open-notebook-installation-assistant) - 它将指导您完成每一步！
- **Open Notebook 新手？**从我们的[入门指南](docs/getting-started/index.md)开始
- **需要安装帮助？**查看我们的[安装指南](docs/getting-started/installation.md)
- **想看它的实际效果？**尝试我们的[快速开始教程](docs/getting-started/quick-start.md)

## 提供商支持矩阵

感谢 [Esperanto](https://github.com/lfnovo/esperanto) 库，我们开箱即用地支持这些提供商！

| 提供商     | LLM 支持 | 嵌入支持 | 语音转文本 | 文本转语音 |
|--------------|-------------|------------------|----------------|----------------|
| OpenAI       | ✅          | ✅               | ✅             | ✅             |
| Anthropic    | ✅          | ❌               | ❌             | ❌             |
| Groq         | ✅          | ❌               | ✅             | ❌             |
| Google (GenAI) | ✅          | ✅               | ❌             | ✅             |
| Vertex AI    | ✅          | ✅               | ❌             | ✅             |
| Ollama       | ✅          | ✅               | ❌             | ❌             |
| Perplexity   | ✅          | ❌               | ❌             | ❌             |
| ElevenLabs   | ❌          | ❌               | ✅             | ✅             |
| Azure OpenAI | ✅          | ✅               | ❌             | ❌             |
| Mistral      | ✅          | ✅               | ❌             | ❌             |
| DeepSeek     | ✅          | ❌               | ❌             | ❌             |
| Voyage       | ❌          | ✅               | ❌             | ❌             |
| xAI          | ✅          | ❌               | ❌             | ❌             |
| OpenRouter   | ✅          | ❌               | ❌             | ❌             |
| OpenAI Compatible* | ✅          | ❌               | ❌             | ❌             |

*支持 LM Studio 和任何兼容 OpenAI 的端点

## ✨ 主要功能

### 核心能力
- **🔒 隐私优先**：您的数据始终在您的控制之下 - 无云依赖
- **🎯 多笔记本组织**：无缝管理多个研究项目
- **📚 通用内容支持**：PDF、视频、音频、网页、Office 文档等
- **🤖 多模型 AI 支持**：16+ 个提供商，包括 OpenAI、Anthropic、Ollama、Google、LM Studio 等
- **🎙️ 专业播客生成**：使用剧集配置文件生成高级多说话人播客
- **🔍 智能搜索**：跨所有内容的全文和向量搜索
- **💬 上下文感知聊天**：由您的研究材料支持的 AI 对话
- **📝 AI 辅助笔记**：生成见解或手动编写笔记

### 高级功能
- **⚡ 推理模型支持**：完全支持思考模型，如 DeepSeek-R1 和 Qwen3
- **🔧 内容转换**：强大的可自定义操作，用于总结和提取见解
- **🌐 全面的 REST API**：用于自定义集成的完全程序化访问 [![API Docs](https://img.shields.io/badge/API-Documentation-blue?style=flat-square)](http://localhost:5055/docs)
- **🔐 可选密码保护**：使用身份验证保护公共部署
- **📊 细粒度上下文控制**：准确选择要与 AI 模型共享的内容
- **📎 引用**：获取带有适当来源引用的答案

### 三列界面
1. **来源**：管理所有研究材料
2. **笔记**：创建手动或 AI 生成的笔记
3. **聊天**：使用您的内容作为上下文与 AI 对话

[![查看我们的播客示例](https://img.youtube.com/vi/D-760MlGwaI/0.jpg)](https://www.youtube.com/watch?v=D-760MlGwaI)

## 📚 文档

### 入门
- **[📖 介绍](docs/getting-started/introduction.md)** - 了解 Open Notebook 提供什么
- **[⚡ 快速开始](docs/getting-started/quick-start.md)** - 5 分钟内启动并运行
- **[🔧 安装](docs/getting-started/installation.md)** - 全面的设置指南
- **[🎯 您的第一个笔记本](docs/getting-started/first-notebook.md)** - 分步教程

### 用户指南
- **[📱 界面概述](docs/user-guide/interface-overview.md)** - 了解布局
- **[📚 笔记本](docs/user-guide/notebooks.md)** - 组织您的研究
- **[📄 来源](docs/user-guide/sources.md)** - 管理内容类型
- **[📝 笔记](docs/user-guide/notes.md)** - 创建和管理笔记
- **[💬 聊天](docs/user-guide/chat.md)** - AI 对话
- **[🔍 搜索](docs/user-guide/search.md)** - 查找信息

### 高级主题
- **[🎙️ 播客生成](docs/features/podcasts.md)** - 创建专业播客
- **[🔧 内容转换](docs/features/transformations.md)** - 自定义内容处理
- **[🤖 AI 模型](docs/features/ai-models.md)** - AI 模型配置
- **[🔧 REST API 参考](docs/development/api-reference.md)** - 完整的 API 文档
- **[🔐 安全性](docs/deployment/security.md)** - 密码保护和隐私
- **[🚀 部署](docs/deployment/index.md)** - 所有场景的完整部署指南

<p align="right">(<a href="#readme-top">返回顶部</a>)</p>

## 🗺️ 路线图

### 即将推出的功能
- **实时前端更新**：实时 UI 更新，获得更流畅的体验
- **异步处理**：通过异步内容处理实现更快的 UI
- **跨笔记本来源**：在项目之间重用研究材料
- **书签集成**：连接您喜欢的书签应用

### 最近完成 ✅
- **Next.js 前端**：基于 React 的现代前端，性能改进
- **全面的 REST API**：对所有功能的完全程序化访问
- **多模型支持**：16+ 个 AI 提供商，包括 OpenAI、Anthropic、Ollama、LM Studio
- **高级播客生成器**：使用剧集配置文件生成专业的多说话人播客
- **内容转换**：用于内容处理的强大可自定义操作
- **增强引用**：改进的布局和对来源引用的更精细控制
- **多个聊天会话**：在笔记本内管理不同的对话

查看[开放问题](https://github.com/lfnovo/open-notebook/issues)以获取建议功能和已知问题的完整列表。

<p align="right">(<a href="#readme-top">返回顶部</a>)</p>


## 🤝 社区与贡献

### 加入社区
- 💬 **[Discord 服务器](https://discord.gg/37XJPXfz2w)** - 获取帮助、分享想法并与其他用户联系
- 🐛 **[GitHub Issues](https://github.com/lfnovo/open-notebook/issues)** - 报告错误和请求功能
- ⭐ **Star 此仓库** - 显示您的支持并帮助其他人发现 Open Notebook

### 贡献
我们欢迎贡献！我们特别需要以下方面的帮助：
- **前端开发**：帮助改进我们现代的 Next.js/React UI
- **测试和错误修复**：使 Open Notebook 更强大
- **功能开发**：一起构建最酷的研究工具
- **文档**：改进指南和教程

**当前技术栈**：Python、FastAPI、Next.js、React、SurrealDB
**未来路线图**：实时更新、增强的异步处理

查看我们的[贡献指南](CONTRIBUTING.md)了解如何开始的详细信息。

<p align="right">(<a href="#readme-top">返回顶部</a>)</p>


## 📄 许可证

Open Notebook 采用 MIT 许可证。查看 [LICENSE](LICENSE) 文件了解详情。

## 📞 联系方式

**Luis Novo** - [@lfnovo](https://twitter.com/lfnovo)

**社区支持**：
- 💬 [Discord 服务器](https://discord.gg/37XJPXfz2w) - 获取帮助、分享想法并与用户联系
- 🐛 [GitHub Issues](https://github.com/lfnovo/open-notebook/issues) - 报告错误和请求功能
- 🌐 [网站](https://www.open-notebook.ai) - 了解更多关于项目的信息

## 🙏 致谢

Open Notebook 建立在令人惊叹的开源项目之上：

* **[Podcast Creator](https://github.com/lfnovo/podcast-creator)** - 高级播客生成功能
* **[Surreal Commands](https://github.com/lfnovo/surreal-commands)** - 后台作业处理
* **[Content Core](https://github.com/lfnovo/content-core)** - 内容处理和管理
* **[Esperanto](https://github.com/lfnovo/esperanto)** - 多提供商 AI 模型抽象
* **[Docling](https://github.com/docling-project/docling)** - 文档处理和解析

<p align="right">(<a href="#readme-top">返回顶部</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/lfnovo/open-notebook.svg?style=for-the-badge
[contributors-url]: https://github.com/lfnovo/open-notebook/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/lfnovo/open-notebook.svg?style=for-the-badge
[forks-url]: https://github.com/lfnovo/open-notebook/network/members
[stars-shield]: https://img.shields.io/github/stars/lfnovo/open-notebook.svg?style=for-the-badge
[stars-url]: https://github.com/lfnovo/open-notebook/stargazers
[issues-shield]: https://img.shields.io/github/issues/lfnovo/open-notebook.svg?style=for-the-badge
[issues-url]: https://github.com/lfnovo/open-notebook/issues
[license-shield]: https://img.shields.io/github/license/lfnovo/open-notebook.svg?style=for-the-badge
[license-url]: https://github.com/lfnovo/open-notebook/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/lfnovo
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white
[Next-url]: https://nextjs.org/
[React]: https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black
[React-url]: https://reactjs.org/
[Python]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[LangChain]: https://img.shields.io/badge/LangChain-3A3A3A?style=for-the-badge&logo=chainlink&logoColor=white
[LangChain-url]: https://www.langchain.com/
[SurrealDB]: https://img.shields.io/badge/SurrealDB-FF5E00?style=for-the-badge&logo=databricks&logoColor=white
[SurrealDB-url]: https://surrealdb.com/
