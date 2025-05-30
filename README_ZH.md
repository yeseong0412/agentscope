[English](https://github.com/modelscope/agentscope/blob/main/README.md) | 中文 | [日本語](https://github.com/modelscope/agentscope/blob/main/README_JA.md)

<a href="https://trendshift.io/repositories/10079" target="_blank"><img src="https://trendshift.io/api/badge/repositories/10079" alt="modelscope%2Fagentscope | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

# AgentScope

<h1 align="left">
<img src="https://img.alicdn.com/imgextra/i2/O1CN01cdjhVE1wwt5Auv7bY_!!6000000006373-0-tps-1792-1024.jpg" width="600" alt="agentscope-logo">
</h1>

更简单地构建基于LLM的多智能体应用。

[![](https://img.shields.io/badge/cs.MA-2402.14034-B31C1C?logo=arxiv&logoColor=B31C1C)](https://arxiv.org/abs/2402.14034)
[![](https://img.shields.io/badge/python-3.9+-blue)](https://pypi.org/project/agentscope/)
[![](https://img.shields.io/badge/pypi-v0.1.3-blue?logo=pypi)](https://pypi.org/project/agentscope/)
[![](https://img.shields.io/badge/Docs-English%7C%E4%B8%AD%E6%96%87-blue?logo=markdown)](https://modelscope.github.io/agentscope/#welcome-to-agentscope-tutorial-hub)
[![](https://img.shields.io/badge/Docs-API_Reference-blue?logo=markdown)](https://modelscope.github.io/agentscope/)
[![](https://img.shields.io/badge/Docs-Roadmap-blue?logo=markdown)](https://github.com/modelscope/agentscope/blob/main/docs/ROADMAP.md)

[![](https://img.shields.io/badge/Drag_and_drop_UI-WorkStation-blue?logo=html5&logoColor=green&color=dark-green)](https://agentscope.io/)
[![](https://img.shields.io/badge/license-Apache--2.0-black)](./LICENSE)
[![](https://img.shields.io/badge/Contribute-Welcome-green)](https://modelscope.github.io/agentscope/tutorial/contribute.html)

- 如果您觉得我们的工作对您有帮助，请引用我们的[论文](https://arxiv.org/abs/2402.14034)。

- 访问 [agentscope.io](https://agentscope.io/)，通过拖拽方式构建多智能体应用。

<h5 align="left">
  <a href="https://agentscope.io" target="_blank">
    <img src="https://img.alicdn.com/imgextra/i1/O1CN01RXAVVn1zUtjXVvuqS_!!6000000006718-1-tps-3116-1852.gif" width="500" alt="agentscope-workstation" style="box-shadow: 5px 10px 18px #888888;">
  </a>
</h5>

- 欢迎加入我们的社区

| [Discord](https://discord.gg/eYMpfnkG8h) | 钉钉群 |
|---------|----------|
| <img src="https://gw.alicdn.com/imgextra/i1/O1CN01hhD1mu1Dd3BWVUvxN_!!6000000000238-2-tps-400-400.png" width="100" height="100"> | <img src="https://img.alicdn.com/imgextra/i1/O1CN01LxzZha1thpIN2cc2E_!!6000000005934-2-tps-497-477.png" width="100" height="100"> |

----

## 新闻
- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-03-21]** AgentScope 已支持钩子函数，详细使用请参考 [tutorial](https://doc.agentscope.io/build_tutorial/hook.html)

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-03-19]** AgentScope 已支持 OpenAI，Anthropic, DashScope API 的工具 API 调用，请参考 [教程](https://doc.agentscope.io/build_tutorial/tool.html).

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-03-20]** Agentscope现已支持[MCP Server](https://github.com/modelcontextprotocol/servers)！您可以通过[此教程](https://doc.agentscope.io/build_tutorial/MCP.html)学习如何使用。

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-03-05]** 我们的[多信息源RAG应用](applications/multisource_rag_app/README.md)（钉钉答疑群中的机器人）已开源!

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-02-24]** [中文版教程](https://doc.agentscope.io/zh_CN)已上线

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-02-13]** 基于 AgentScope 的 [SWE-Bench(Verified)](https://www.swebench.com/) 解决方案[技术报告](https://doc.agentscope.io/tutorial/swe.html) 已上线

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-02-07]** 🎉 AgentScope 在 [SWE-Bench（Verified）](https://www.swebench.com/)榜单中取得 **63.4%** 的成绩！关于解决方案的更多细节即将发布

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2025-01-04]** AgentScope 已支持 Anthropic API

- <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>**[2024-12-12]** [AgentScope 开发路线图](https://github.com/modelscope/agentscope/blob/main/docs/ROADMAP.md) 已更新

- **[2024-09-06]** AgentScope v0.1.0 版本已上线

- **[2024-09-03]** AgentScope 已更新浏览器控制模块，利用 vision 模型实现智能体对浏览器的控制。请参考[**样例**](https://github.com/modelscope/agentscope/tree/main/examples/conversation_with_web_browser_agent)

<h5 align="left">
<video src="https://github.com/user-attachments/assets/6d03caab-6193-4ac6-8b1c-36f152ec02ec" width="45%" alt="web browser control" controls></video>
</h5>

[查看更多消息](https://github.com/modelscope/agentscope/blob/main/docs/news_zh.md)

---

## 什么是AgentScope？

AgentScope是一个创新的多智能体开发平台，旨在赋予开发人员使用大模型轻松构建多智能体应用的能力。

- 🤝 **高易用**： AgentScope专为开发人员设计，提供了[丰富的组件](https://doc.agentscope.io/build_tutorial/tool.html#), [全面的文档](https://doc.agentscope.io/index.html)和广泛的兼容性。同时，[AgentScope Workstation](https://agentscope.io/)提供了在线拖拉拽编程和在线小助手(copilot)功能，帮助开发者迅速上手！

- ✅ **高鲁棒**：支持自定义的容错控制和重试机制，以提高应用程序的稳定性。

- 🚀 **分布式**：支持以中心化的方式构建分布式多智能体应用程序。

**支持的模型API**

AgentScope提供了一系列`ModelWrapper`来支持本地模型服务和第三方模型API。

| API                    | Task            | Model Wrapper                                                                                                                   | Configuration                                                                                                                                                                                                                      | Some Supported Models                         |
|------------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| OpenAI API             | Chat            | [`OpenAIChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/openai_model.py)                 |  [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/openai_chat_template.json)                | gpt-4o, gpt-4, gpt-3.5-turbo, ...                     |
|                        | Embedding       | [`OpenAIEmbeddingWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/openai_model.py)            | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/openai_embedding_template.json)            | text-embedding-ada-002, ...                   |
|                        | DALL·E          | [`OpenAIDALLEWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/openai_model.py)                | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/openai_dall_e_template.json)               | dall-e-2, dall-e-3                            |
| DashScope API          | Chat            | [`DashScopeChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/dashscope_model.py)           | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/dashscope_chat_template.json)              | qwen-plus, qwen-max, ...                      |
|                        | Image Synthesis | [`DashScopeImageSynthesisWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/dashscope_model.py) | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/dashscope_image_synthesis_template.json)   | wanx-v1                                       |
|                        | Text Embedding  | [`DashScopeTextEmbeddingWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/dashscope_model.py)  | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/dashscope_text_embedding_template.json)   | text-embedding-v1, text-embedding-v2, ...     |
|                        | Multimodal      | [`DashScopeMultiModalWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/dashscope_model.py)     | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/dashscope_multimodal_template.json)       | qwen-vl-max, qwen-vl-chat-v1, qwen-audio-chat |
| Gemini API             | Chat            | [`GeminiChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/gemini_model.py)                 | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/gemini_chat_template.json)                 | gemini-pro, ...                               |
|                        | Embedding       | [`GeminiEmbeddingWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/gemini_model.py)            | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/gemini_embedding_template.json)            | models/embedding-001, ...                     |
| ZhipuAI API            | Chat            | [`ZhipuAIChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/zhipu_model.py)                 | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/zhipu_chat_template.json)                  | glm-4, ...                               |
|                        | Embedding       | [`ZhipuAIEmbeddingWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/zhipu_model.py)            |  [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/zhipu_embedding_template.json)            | embedding-2, ...                     |
| ollama                 | Chat            | [`OllamaChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/ollama_model.py)                 |  [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/ollama_chat_template.json)              | llama3, llama2, Mistral, ...                  |
|                        | Embedding       | [`OllamaEmbeddingWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/ollama_model.py)            | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/ollama_embedding_template.json)          | llama2, Mistral, ...                          |
|                        | Generation      | [`OllamaGenerationWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/ollama_model.py)           | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/ollama_generate_template.json)           | llama2, Mistral, ...                          |
| LiteLLM API            | Chat            | [`LiteLLMChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/litellm_model.py)               | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/litellm_chat_template.json)              | [models supported by litellm](https://docs.litellm.ai/docs/)...                               |
| Yi API                 | Chat            | [`YiChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/yi_model.py)                         |  [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/yi_chat_template.json)                           | yi-large, yi-medium, ...                                        |
| Post Request based API | -               | [`PostAPIModelWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/post_model.py)                 | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/postapi_model_config_template.json)  | -                                             |
| Anthropic API          | Chat            | [`AnthropicChatWrapper`](https://github.com/modelscope/agentscope/blob/main/src/agentscope/models/anthropic_model.py)           | [template](https://github.com/modelscope/agentscope/blob/main/examples/model_configs_template/anthropic_chat_model_config_template.json) | claude-3-5-sonnet-20241022, ... |
**支持的本地模型部署**

AgentScope支持使用以下库快速部署本地模型服务。

- [ollama (CPU inference)](https://github.com/modelscope/agentscope/blob/main/scripts/README.md#ollama)
- [Flask + Transformers](https://github.com/modelscope/agentscope/blob/main/scripts/README.md#with-transformers-library)
- [Flask + ModelScope](https://github.com/modelscope/agentscope/blob/main/scripts/README.md#with-modelscope-library)
- [FastChat](https://github.com/modelscope/agentscope/blob/main/scripts/README.md#fastchat)
- [vllm](https://github.com/modelscope/agentscope/blob/main/scripts/README.md#vllm)

**支持的服务**

- 网络搜索
- 数据查询
- 数据检索
- 代码执行
- 文件操作
- 文本处理
- 多模态生成
- 维基百科搜索
- TripAdvisor搜索
- 浏览器控制

**样例应用**

- 模型
  - [在AgentScope中使用Llama3](./examples/model_llama3)

- 对话
  - [基础对话](./examples/conversation_basic)
  - [带有@功能的自主对话](./examples/conversation_with_mentions)
  - [智能体自组织的对话](./examples/conversation_self_organizing)
  - [兼容LangChain的基础对话](./examples/conversation_with_langchain)
  - [与ReAct智能体对话](./examples/conversation_with_react_agent)
  - [通过对话查询SQL信息](./examples/conversation_nl2sql/)
  - [与RAG智能体对话](./examples/conversation_with_RAG_agents)
  - [与gpt-4o模型对话](./examples/conversation_with_gpt-4o)
  - [自定义工具函数](./examples/conversation_with_customized_services/)
  - [与SoftWare Engineering智能体对话](./examples/conversation_with_swe-agent/)
  - <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>[Mixture of Agents算法](https://github.com/modelscope/agentscope/blob/main/examples/conversation_mixture_of_agents/)
  - <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>[流式对话](https://github.com/modelscope/agentscope/blob/main/examples/conversation_in_stream_mode/)
  - <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>[与CodeAct智能体对话](https://github.com/modelscope/agentscope/blob/main/examples/conversation_with_codeact_agent/)
  - <img src="https://img.alicdn.com/imgextra/i3/O1CN01SFL0Gu26nrQBFKXFR_!!6000000007707-2-tps-500-500.png" alt="new" width="30" height="30"/>[与Router Agent对话](https://github.com/modelscope/agentscope/blob/main/examples/conversation_with_router_agent/)

- 游戏
  - [五子棋](./examples/game_gomoku)
  - [狼人杀](./examples/game_werewolf)

- 分布式
  - [分布式对话](./examples/distributed_conversation)
  - [分布式辩论](./examples/distributed_debate)
  - [分布式并行优化](./examples/distributed_parallel_optimization)
  - [分布式大规模仿真](./examples/distributed_simulation)

更多模型API、服务和示例即将推出！

## 安装

AgentScope需要Python 3.9或更高版本。

***注意：该项目目前正在积极开发中，建议从源码安装AgentScope。***

### 从源码安装

- 以编辑模式安装AgentScope：

```bash
# 从github拉取源代码
git clone https://github.com/modelscope/agentscope.git
# 以编辑模式安装包
cd agentscope
pip install -e .
```

### 使用pip

- 从pip安装的AgentScope

```bash
pip install agentscope
```

### 额外依赖

为了支持不同的部署场景，AgentScope提供了若干个可选的依赖项。
完整的可选依赖项列表请参考[tutorial](https://doc.agentscope.io/build_tutorial/quickstart.html)
以分布式模式为例，可以使用以下命令安装AgentScope：

#### On Windows

```bash
# From source
pip install -e .[distribute]
# From pypi
pip install agentscope[distribute]
```

#### On Mac & Linux

```bash
# From source
pip install -e .\[distribute\]
# From pypi
pip install agentscope\[distribute\]
```

## 快速开始

### 配置

AgentScope中，模型的部署和调用是通过`ModelWrapper`实现解耦的。

为了使用这些`ModelWrapper`, 您需要准备如下的模型配置文件：

```python
model_config = {
    # 模型配置的名称，以及使用的模型wrapper
    "config_name": "{your_config_name}",          # 模型配置的名称
    "model_type": "{model_type}",                 # 模型wrapper的类型

    # 用以初始化模型wrapper的详细参数
    # ...
}
```

以OpenAI Chat API为例，模型配置如下：

```python
openai_model_config = {
    "config_name": "my_openai_config",             # 模型配置的名称
    "model_type": "openai_chat",                   # 模型wrapper的类型

    # 用以初始化模型wrapper的详细参数
    "model_name": "gpt-4",                         # OpenAI API中的模型名
    "api_key": "xxx",                              # OpenAI API的API密钥。如果未设置，将使用环境变量OPENAI_API_KEY。
    "organization": "xxx",                         # OpenAI API的组织。如果未设置，将使用环境变量OPENAI_ORGANIZATION。
}
```

关于部署本地模型服务和准备模型配置的更多细节，请参阅我们的[教程](https://modelscope.github.io/agentscope/index.html#welcome-to-agentscope-tutorial-hub)。

### 创建Agent

创建AgentScope内置的`DialogAgent`和`UserAgent`对象.

```python
from agentscope.agents import DialogAgent, UserAgent
import agentscope

# 加载模型配置
agentscope.init(model_configs="./model_configs.json")

# 创建对话Agent和用户Agent
dialog_agent = DialogAgent(name="assistant",
                           model_config_name="my_openai_config")
user_agent = UserAgent()
```

#### 构造对话

在AgentScope中，**Message**是Agent之间的桥梁，它是一个python**字典**（dict），包含两个必要字段`name`和`content`，以及一个可选字段`url`用于本地文件（图片、视频或音频）或网络链接。

```python
from agentscope.message import Msg

x = Msg(name="Alice", content="Hi!")
x = Msg("Bob", "What about this picture I took?", url="/path/to/picture.jpg")
```

使用以下代码开始两个Agent（dialog_agent和user_agent）之间的对话：

```python
x = None
while True:
  x = dialog_agent(x)
  x = user_agent(x)
  if x.content == "exit": # 用户输入"exit"退出对话
    break
```

### AgentScope前端

AgentScope 提供了一个易于使用的运行时用户界面，能够在前端显示多模态输出，包括文本、图像、音频和视频。

参考我们的[教程](https://doc.agentscope.io/build_tutorial/visual.html)了解更多细节。

<h5 align="center">
<img src="https://img.alicdn.com/imgextra/i4/O1CN015kjnkd1xdwJoNxqLZ_!!6000000006467-0-tps-3452-1984.jpg" width="600" alt="agentscope-logo">
</h5>

## License

AgentScope根据Apache License 2.0发布。

## 贡献

欢迎参与到AgentScope的构建中！

我们提供了一个带有额外 pre-commit 钩子以执行检查的开发者版本，与官方版本相比：

```bash
# 对于windows
pip install -e .[dev]
# 对于mac
pip install -e .\[dev\]
# 安装pre-commit钩子
pre-commit install
```

请参阅我们的[贡献指南](https://modelscope.github.io/agentscope/zh_CN/tutorial/302-contribute.html)了解更多细节。

## 发表

如果您觉得我们的工作对您的研究或应用有帮助，请引用如下论文

1. [AgentScope: A Flexible yet Robust Multi-Agent Platform](https://arxiv.org/abs/2402.14034)

    ```
    @article{agentscope,
        author  = {Dawei Gao and
                   Zitao Li and
                   Xuchen Pan and
                   Weirui Kuang and
                   Zhijian Ma and
                   Bingchen Qian and
                   Fei Wei and
                   Wenhao Zhang and
                   Yuexiang Xie and
                   Daoyuan Chen and
                   Liuyi Yao and
                   Hongyi Peng and
                   Ze Yu Zhang and
                   Lin Zhu and
                   Chen Cheng and
                   Hongzhu Shi and
                   Yaliang Li and
                   Bolin Ding and
                   Jingren Zhou}
        title   = {AgentScope: A Flexible yet Robust Multi-Agent Platform},
        journal = {CoRR},
        volume  = {abs/2402.14034},
        year    = {2024},
    }
    ```

## 贡献者 ✨

感谢我们的贡献者:

<a href="https://github.com/modelscope/agentscope/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=modelscope/agentscope&max=999&columns=12&anon=1" />
</a>