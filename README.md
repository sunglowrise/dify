![](./images/describe-en.png)
<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README_CN.md">简体中文</a> |
  <a href="./README_JA.md">日本語</a> |
  <a href="./README_ES.md">Español</a>
</p>

#### [Website](https://dify.ai) • [Docs](https://docs.dify.ai) • [Deployment Docs](https://docs.dify.ai/getting-started/install-self-hosted) •  [FAQ](https://docs.dify.ai/getting-started/faq) • [Twitter](https://twitter.com/dify_ai) • [Discord](https://discord.gg/FngNHpbcY7)

**Dify** is an easy-to-use LLMOps platform designed to empower more people to create sustainable, AI-native applications. With visual orchestration for various application types, Dify offers out-of-the-box, ready-to-use applications that can also serve as Backend-as-a-Service APIs. Unify your development process with one API for plugins and datasets integration, and streamline your operations using a single interface for prompt engineering, visual analytics, and continuous improvement.

Applications created with Dify include:

Out-of-the-box web sites supporting form mode and chat conversation mode
A single API encompassing plugin capabilities, context enhancement, and more, saving you backend coding effort
Visual data analysis, log review, and annotation for applications


https://github.com/langgenius/dify/assets/100913391/f6e658d5-31b3-4c16-a0af-9e191da4d0f6


## Highlighted Features
**1. LLMs support:** Choose capabilities based on different models when building your Dify AI apps. Dify is compatible with Langchain, meaning it will support various LLMs. Currently supported:

- [x] **OpenAI**: GPT4, GPT3.5-turbo, GPT3.5-turbo-16k, text-davinci-003 
- [x] **Azure OpenAI Service**
- [x] **Anthropic**: Claude2, Claude-instant
- [x] **Replicate**
- [x] **Hugging Face Hub**
- [x] **ChatGLM**
- [x] **Llama2**
- [x] **MiniMax**
- [x] **Spark**
- [x] **Wenxin**
- [x] **Tongyi**


We provide the following free resources for registered Dify cloud users (sign up at [dify.ai](https://dify.ai)):
* 200 free OpenAI queries to build OpenAI-based apps

  
**2. Visual orchestration:** Build an AI app in minutes by writing and debugging prompts visually.

**3. Text embedding:** Fully automated text preprocessing embeds your data as context without complex concepts. Supports PDF, TXT, and syncing data from Notion, webpages, APIs.

**4. API-based:**  Backend-as-a-service. Access web apps directly or integrate via APIs without complex backend setup.

**5. Plugins:** Dify "Smart Chat" now supports first-party plugins like web browsing, Google search, Wikipedia to enable online lookup, analyzing web content, and explaining the AI's reasoning process conversationally.

**6. Team workspaces:** Team members can join workspaces to collaboratively edit, manage, and use team AI apps.

**7. Data labeling and improvement:**  Visually inspect AI app logs and improve data via labeling. Observe the AI's reasoning process to continuously enhance performance. (Coming soon)

## Install the Community Edition

### System Requirements

Before installing Dify, make sure your machine meets the following minimum system requirements:

- CPU >= 2 Core
- RAM >= 4GB

### Quick Start

The easiest way to start the Dify server is to run our [docker-compose.yml](docker/docker-compose.yaml) file. Before running the installation command, make sure that [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) are installed on your machine:

```bash
cd docker
docker compose up -d
```

After running, you can access the Dify dashboard in your browser at [http://localhost/install](http://localhost/install) and start the initialization installation process.

### Helm Chart

A big thanks to @BorisPolonsky for providing us with a [Helm Chart](https://helm.sh/) version, which allows Dify to be deployed on Kubernetes.
You can go to https://github.com/BorisPolonsky/dify-helm for deployment information.

### Configuration

If you need to customize the configuration, please refer to the comments in our [docker-compose.yml](docker/docker-compose.yaml) file and manually set the environment configuration. After making the changes, please run `docker-compose up -d` again. You can see the full list of environment variables in our [docs](https://docs.dify.ai/getting-started/install-self-hosted/environments).


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=langgenius/dify&type=Date)](https://star-history.com/#langgenius/dify&Date)


## Community & Support

We welcome you to contribute to Dify to help make Dify better. We welcome contributions in various ways, submitting code, issues, new ideas, or sharing the interesting and useful AI applications you have created based on Dify. At the same time, we also welcome you to share Dify at different events, conferences, and social media.

- [GitHub Issues](https://github.com/langgenius/dify/issues). Best for: bugs and errors you encounter using Dify.AI, see the [Contribution Guide](CONTRIBUTING.md).
- [Email Support](mailto:hello@dify.ai?subject=[GitHub]Questions%20About%20Dify). Best for: questions you have about using Dify.AI.
- [Discord](https://discord.gg/FngNHpbcY7). Best for: sharing your applications and hanging out with the community.
- [Twitter](https://twitter.com/dify_ai). Best for: sharing your applications and hanging out with the community.
- [Business License](mailto:business@dify.ai?subject=[GitHub]Business%20License%20Inquiry). Best for: business inquiries of licensing Dify.AI for commercial use.

## Security Disclosure

To protect your privacy, please avoid posting security issues on GitHub. Instead, send your questions to security@dify.ai and we will provide you with a more detailed answer.

## License

This repository is available under the [Dify Open Source License](LICENSE).
