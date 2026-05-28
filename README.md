# LLM / Agent 学习资源导航

面向中文开发者的大模型、RAG 与 Agent 学习资源导航仓库。

- 更快找到高质量学习资源
- 根据自己的目标选择合适路线
- 从 LLM 基础过渡到 RAG、Agent 与工程实践

## 目录

- [这个仓库适合谁](#这个仓库适合谁)
- [如何使用](#如何使用)
- [快速选资源](#快速选资源)
- [推荐学习路线](#推荐学习路线)
- [资源目录](#资源目录)
- [收录标准](#收录标准)
- [如何贡献](#如何贡献)
- [维护策略](#维护策略)
- [免责声明](#免责声明)
- [Roadmap](#roadmap)
- [License](#license)

## 这个仓库适合谁

- 想系统学习大模型基础原理的开发者
- 想做 RAG、知识库、文档问答系统的工程师
- 想学习 Agent、工作流、工具调用、多 Agent 协作的人
- 想找中文友好资料，但又不希望和官方英文文档脱节的人

## 如何使用

如果你是第一次接触这个方向，建议按下面顺序学习：

1. 先建立大模型基础认知
2. 再学习 Prompt、RAG、知识库等应用开发能力
3. 最后进入 Agent、工作流编排和工程化框架

如果你时间有限，优先从 `快速选资源` 和 `推荐学习路线` 开始。

说明：各分类页中的 GitHub 仓库资源会展示 `Stars`、`较上次变化` 和 `统计时间`，用于辅助判断资料热度与社区活跃度。这些数据按每日自动追踪更新，但 GitHub Actions 定时任务可能存在延迟，不保证分钟级实时。

## 快速选资源


| 目标                   | 优先看什么                                                                                                                                                                                                               | 适合原因               |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| 想先把大模型基础学明白          | [Happy-LLM](https://github.com/datawhalechina/happy-llm)、[LLMBook](https://github.com/datawhalechina/llmbook)                                                                                                       | 偏系统化、偏原理，适合建立完整认知  |
| 想尽快把开源模型跑起来          | [self-llm](https://github.com/datawhalechina/self-llm)、[llm-universe](https://github.com/datawhalechina/llm-universe)                                                                                               | 偏部署、微调、使用，适合快速上手   |
| 想做企业知识库 / RAG        | [all-in-rag](https://github.com/datawhalechina/all-in-rag)、[Advanced RAG](https://www.deeplearning.ai/courses/building-evaluating-advanced-rag)                                                                     | 理论、实战和课程三条线比较完整    |
| 想学 Agent 原理与实战       | [hello-agents](https://github.com/datawhalechina/hello-agents)、[Hugging Face Agents Course](https://huggingface.co/learn/agents-course/en)、[OpenAI Agents SDK](https://platform.openai.com/docs/guides/agents-sdk/) | 从概念到框架、再到官方实践比较顺   |
| 想做工作流 / 低代码 Agent 应用 | [Dify](https://github.com/langgenius/dify)、[Dify Docs](https://docs.dify.ai/en/use-dify/build/agent)                                                                                                                | 适合产品化原型、工作流编排和团队协作 |
| 想补全英文官方视角            | [OpenAI Cookbook](https://cookbook.openai.com/topic/agents)、[LangChain Learn](https://docs.langchain.com/oss/python/learn)、[LlamaIndex Agents](https://docs.llamaindex.ai/en/stable/understanding/agent/)           | 更新快，适合跟进主流实践       |


## 推荐学习路线

### 路线 A：普通开发者快速上手

1. [self-llm](https://github.com/datawhalechina/self-llm)
2. [llm-universe](https://github.com/datawhalechina/llm-universe)
3. [all-in-rag](https://github.com/datawhalechina/all-in-rag)
4. [hello-agents](https://github.com/datawhalechina/hello-agents)

适合：

- 想尽快做出 Demo
- 想验证业务场景
- 想先做知识库、问答系统、助手类应用

### 路线 B：想把原理学扎实

1. [Happy-LLM](https://github.com/datawhalechina/happy-llm)
2. [LLMBook](https://github.com/datawhalechina/llmbook)
3. [llms-from-scratch-cn](https://github.com/datawhalechina/llms-from-scratch-cn)
4. [Hugging Face LLM Course](https://huggingface.co/huggingface-course)

适合：

- 想长期做 AI 应用开发
- 想补齐 Transformer、预训练、微调、推理等基础
- 不满足于只会调接口

### 路线 C：想做 RAG / Agent 工程

1. [all-in-rag](https://github.com/datawhalechina/all-in-rag)
2. [Building and Evaluating Advanced RAG](https://www.deeplearning.ai/courses/building-evaluating-advanced-rag)
3. [hello-agents](https://github.com/datawhalechina/hello-agents)
4. [Hugging Face Agents Course](https://huggingface.co/learn/agents-course/en)
5. [LangChain Learn](https://docs.langchain.com/oss/python/learn)
6. [OpenAI Agents SDK](https://platform.openai.com/docs/guides/agents-sdk/)

适合：

- 企业知识库
- 工具调用型 Agent
- 多步骤工作流和研究型助手

## 资源目录

完整资源清单已拆分到 `resources/` 目录，README 只保留首页导航与精选入口。

- [LLM 基础](resources/llm.md)
- [RAG / 知识库](resources/rag.md)
- [Agent / Workflow](resources/agent.md)
- [课程 / 教程](resources/courses.md)
- [导航 / Awesome](resources/awesome.md)

推荐优先看这 6 个资源：

1. [Happy-LLM](https://github.com/datawhalechina/happy-llm)
2. [self-llm](https://github.com/datawhalechina/self-llm)
3. [all-in-rag](https://github.com/datawhalechina/all-in-rag)
4. [hello-agents](https://github.com/datawhalechina/hello-agents)
5. [Hugging Face Agents Course](https://huggingface.co/learn/agents-course/en)
6. [OpenAI Cookbook - Agents](https://cookbook.openai.com/topic/agents)

## 仓库结构

```text
.
├── .github/                # Issue / PR 模板与社区配置
├── resources/              # 分类资源清单
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── SECURITY.md
```

## 收录标准

本仓库优先收录满足以下条件的资源：

- 公开可访问，最好长期稳定可用
- 与 LLM、Prompt、RAG、Agent、Workflow 学习强相关
- 内容质量稳定，有明确教程、文档或系统化知识输出
- 对中文开发者有明显帮助，或属于高价值官方文档

以下内容原则上不收录：

- 纯营销页或导流页
- 几乎没有实质内容的项目
- 已长期停止维护且无明显参考价值的资源
- 与已有资源高度重复但质量更弱的项目

资源主分类固定为：

- `LLM 基础`
- `Prompt / 应用开发`
- `RAG / 知识库`
- `Agent / Workflow`
- `课程 / 教程`
- `导航 / Awesome`

每条资源至少应包含：

- 名称
- 链接
- 分类
- 简介
- 适合谁
- 推荐理由

## 如何贡献

欢迎通过 Issue 或 PR 参与维护，常见贡献类型包括：

- 新增优质资源
- 修复失效链接
- 补充简介或适合人群说明
- 调整分类
- 修正文案错误或过时信息

开始贡献前，建议先阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

默认协作方式：

1. 先通过 Issue 提议资源或问题
2. 确认方向后提交 PR
3. 维护者审核后合并

外部贡献默认优先修改 `resources/*.md`，不建议直接大幅重写 README。

## 维护策略

- 当前以人工维护为主
- 首发版本暂不引入自动化失效链接检查
- README 作为首页导航，详细内容进入 `resources/`
- 后续若资源量持续增长，再考虑引入数据化维护和自动化校验

## 免责声明

- 本仓库仅整理公开可访问的学习资源链接与简要说明，不对第三方网站内容负责
- 部分外部资源可能随时间发生失效、迁移、收费或内容变更
- 收录不代表对资源中所有观点、实现方式或商业行为的完全背书
- 如果你发现恶意链接、侵权内容或明显错误，请通过 Issue 或私下联系维护者处理

## Roadmap

- 完善 `resources/` 下的分类页内容密度和更新节奏
- 增加更明确的初学者路线、企业场景路线和进阶路线
- 逐步补充 Prompt / 应用开发专门分类
- 后续评估是否引入自动化链接检查
- 后续评估是否基于这些内容生成独立网站

## License

本仓库内容采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 许可协议。

这意味着你可以分享和改编本仓库内容，但需要：

- 保留原始署名
- 附上许可协议链接
- 说明是否做了修改

详细说明见 [LICENSE](LICENSE)。
