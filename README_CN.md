![](./images/describe-cn.jpg)
<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README_CN.md">简体中文</a> |
  <a href="./README_JA.md">日本語</a> |
  <a href="./README_ES.md">Español</a>
</p>


####  [官方网站](https://dify.ai) •  [使用文档](https://docs.dify.ai/v/zh-hans)  · [部署文档](https://docs.dify.ai/v/zh-hans/getting-started/install-self-hosted)  ·  [FAQ](https://docs.dify.ai/v/zh-hans/getting-started/faq) • [Twitter](https://twitter.com/dify_ai) •  [Discord](https://discord.gg/FngNHpbcY7)

**Dify** 是一个易用的 LLMOps 平台，基于不同的大型语言模型能力，让更多人可以简易地创建可持续运营的原生 AI 应用。Dify 提供多种类型应用的可视化编排，应用可开箱即用，也能以“后端即服务”的 API 提供服务。

通过 Dify 创建的应用包含了：

- 开箱即用的的 Web 站点，支持表单模式和聊天对话模式
- 一套 API 即可包含插件、上下文增强等能力，替你省下了后端代码的编写工作
- 可视化的对应用进行数据分析，查阅日志或进行标注

https://github.com/langgenius/dify/assets/100913391/f6e658d5-31b3-4c16-a0af-9e191da4d0f6

## 核心能力
1. **模型支持：** 你可以在 Dify 上选择基于不同模型的能力来开发你的 AI 应用。Dify 兼容 Langchain，这意味着我们将逐步支持多种 LLMs ，目前支持的模型供应商：

- [x] **OpenAI**：GPT4、GPT3.5-turbo、GPT3.5-turbo-16k、text-davinci-003 
- [x] **Azure OpenAI Service**
- [x] **Anthropic**：Claude2、Claude-instant
- [x] **Replicate**
- [x] **Hugging Face Hub**
- [x] **ChatGLM**
- [x] **Llama2**
- [x] **MiniMax**
- [x] **讯飞星火大模型**
- [x] **文心一言**
- [x] **通义千问**


我们为所有注册云端版的用户免费提供以下资源（登录 [dify.ai](https://cloud.dify.ai) 即可使用）：
* 200 次 OpenAI 模型的消息调用额度，用于创建基于 OpenAI 模型的 AI 应用
* 300 万 讯飞星火大模型 Token 的调用额度，用于创建基于讯飞星火大模型的 AI 应用
* 100 万 MiniMax Token 的调用额度，用于创建基于 MiniMax 模型的 AI 应用
2. **可视化编排 Prompt：** 通过界面化编写 prompt 并调试，只需几分钟即可发布一个 AI 应用。
3. **文本 Embedding 处理（数据集）**：全自动完成文本预处理，使用你的数据作为上下文，无需理解晦涩的概念和技术处理。支持 PDF、txt 等文件格式，支持从 Notion、网页、API 同步数据。
4. **基于 API 开发：** 后端即服务。您可以直接访问网页应用，也可以接入 API 集成到您的应用中，无需关注复杂的后端架构和部署过程。
5. **插件能力：** Dify 「智聊」平台已支持网页浏览、Google 搜索、Wikipedia 查询等第一方插件，可在对话中实现联网搜索、分析网页内容、展示 AI 的推理过程。
6. **团队 Workspace：** 团队成员可加入 Workspace 编辑、管理和使用团队内的 AI 应用。
6. **数据标注与改进：** 可视化查阅 AI 应用日志并对数据进行改进标注，观测 AI 的推理过程，不断提高其性能。（Coming soon）
 -----------------------------
## 安装社区版

### 系统要求

在安装 Dify 之前，请确保您的机器满足以下最低系统要求：

- CPU >= 2 Core
- RAM >= 4GB

### 快速启动

启动 Dify 服务器的最简单方法是运行我们的 [docker-compose.yml](docker/docker-compose.yaml) 文件。在运行安装命令之前，请确保您的机器上安装了 [Docker](https://docs.docker.com/get-docker/) 和 [Docker Compose](https://docs.docker.com/compose/install/)：

```bash
cd docker
docker compose up -d
```

运行后，可以在浏览器上访问 [http://localhost/install](http://localhost/install) 进入 Dify 控制台并开始初始化安装操作。

### Helm Chart

非常感谢 @BorisPolonsky 为我们提供了一个 [Helm Chart](https://helm.sh/) 版本，可以在 Kubernetes 上部署 Dify。
您可以前往 https://github.com/BorisPolonsky/dify-helm 来获取部署信息。

### 配置

如果您需要自定义配置，请参考我们的 [docker-compose.yml](docker/docker-compose.yaml) 文件中的注释，并手动设置环境配置。更改后，请再次运行 `docker-compose up -d`。您可以在我们的[文档](https://docs.dify.ai/getting-started/install-self-hosted/environments)中查看所有环境变量的完整列表。

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=langgenius/dify&type=Date)](https://star-history.com/#langgenius/dify&Date)


## 社区与支持

我们欢迎您为 Dify 做出贡献，以帮助改善 Dify。我们以多种方式欢迎贡献：提交代码、问题、新想法，或分享您基于 Dify 创建的有趣且有用的 AI 应用程序。同时，我们也欢迎您在不同的活动、会议和社交媒体上分享 Dify。

- [GitHub 问题](https://github.com/langgenius/dify/issues)。👉：使用 Dify.AI 时遇到的错误和问题，请参阅[贡献指南](CONTRIBUTING.md)。
- [电子邮件支持](mailto:hello@dify.ai?subject=[GitHub]Questions%20About%20Dify)。👉：关于使用 Dify.AI 的问题。
- [Discord](https://discord.gg/FngNHpbcY7)。👉：分享您的应用程序并与社区交流。
- [Twitter](https://twitter.com/dify_ai)。👉：分享您的应用程序并与社区交流。
- [商业许可](mailto:business@dify.ai?subject=[GitHub]Business%20License%20Inquiry)。👉：有关商业用途许可 Dify.AI 的商业咨询。
## 安全

为了保护您的隐私，请避免在 GitHub 上发布安全问题。发送问题至 security@dify.ai，我们将为您做更细致的解答。

## License

本仓库遵循 [Dify Open Source License](LICENSE) 开源协议。
