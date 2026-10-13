# Trending AI projects list

A curated overview of the top open-source AI repositories, organised by category. Each section covers a distinct layer of the modern AI stack — from orchestration frameworks and RAG pipelines to coding agents, evaluation tooling, and model serving infrastructure.
This list is subject to change and will be updated regularly.

*Maintained at [bobpage0451/ai-trending-repos](https://github.com/bobpage0451/ai-trending-repos) • Last updated: 2026-10-13 (refreshed bi-weekly)*

![banner_blackboard](banners/banner_blackboard.png)

- [App orchestration layer](#app-orchestration-layer)
- [RAG, memory, and knowledge layer](#rag-memory-and-knowledge-layer)
- [Agent and workflow layer](#agent-and-workflow-layer)
- [Tools, MCP, and integration layer](#tools-mcp-and-integration-layer)
- [UI and generative interface layer](#ui-and-generative-interface-layer)
- [AI coding agents and developer experience](#ai-coding-agents-and-developer-experience)
- [Evaluation and testing layer](#evaluation-and-testing-layer)
- [Observability, tracing, and prompt management](#observability-tracing-and-prompt-management)
- [Guardrails, safety, governance, and policy layer](#guardrails-safety-governance-and-policy-layer)
- [Structured output and prompt engineering layer](#structured-output-and-prompt-engineering-layer)
- [Document ingestion, parsing, and data preparation](#document-ingestion-parsing-and-data-preparation)
- [Model training, fine-tuning, and adaptation](#model-training-fine-tuning-and-adaptation)
- [Deployment, local inference, and model serving layer](#deployment-local-inference-and-model-serving-layer)

---

## App orchestration layer

This is the core application framework layer for building AI apps. It helps structure LLM calls, chains, workflows, tool use, retrieval, memory, callbacks, and agent execution.

Connect prompts, models, tools, memory, retrieval, agents, and workflows.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 147.8k | 24787 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | 43.2k | 7343 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [appsmithorg/appsmith](https://github.com/appsmithorg/appsmith) | 41.1k | 4806 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [agentscope-ai/QwenPaw](https://github.com/agentscope-ai/QwenPaw) | 35.7k | 3181 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents) | 30.2k | 4237 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | 28.5k | 3202 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 26.7k | 3280 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | MDX |
| [google/adk-python](https://github.com/google/adk-python) | 21.8k | 4140 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/agent-framework](https://github.com/microsoft/agent-framework) | 14.1k | 2465 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [Chainlit/chainlit](https://github.com/Chainlit/chainlit) | 12.5k | 1758 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## RAG, memory, and knowledge layer

This layer includes retrieval-augmented generation, semantic search, embeddings, vector storage, hybrid search, reranking, citations, document permissions, and short-term or long-term memory.

Give the model external, project, user, or company knowledge.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 92.2k | 10979 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | 67.1k | 7893 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [MemPalace/mempalace](https://github.com/MemPalace/mempalace) | 59.6k | 7563 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | 52.5k | 8335 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [milvus-io/milvus](https://github.com/milvus-io/milvus) | 46.4k | 4294 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex) | 39.1k | 3395 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [qdrant/qdrant](https://github.com/qdrant/qdrant) | 35.1k | 2743 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [chroma-core/chroma](https://github.com/chroma-core/chroma) | 29.5k | 2560 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [weaviate/weaviate](https://github.com/weaviate/weaviate) | 16.9k | 1420 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [memvid/memvid](https://github.com/memvid/memvid) | 16.6k | 1422 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |

## Agent and workflow layer

This layer covers tool-using agents, graph-based workflows, planner-executor patterns, multi-agent collaboration, human approval steps, state management, retries, and long-running task execution.

Build systems that can plan, call tools, perform multi-step tasks, and coordinate agents.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | 391.9k | 82417 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [langflow-ai/langflow](https://github.com/langflow-ai/langflow) | 155.6k | 10247 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 83.8k | 11671 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [FoundationAgents/MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 70.8k | 9005 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | 59.7k | 8717 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [agno-agi/agno](https://github.com/agno-agi/agno) | 42.7k | 6128 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) | 34.5k | 4324 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | 30k | 4878 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [huggingface/smolagents](https://github.com/huggingface/smolagents) | 29.8k | 3075 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [letta-ai/letta](https://github.com/letta-ai/letta) | 25.1k | 2642 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Tools, MCP, and integration layer

This layer includes Model Context Protocol servers and clients, tool schemas, function calling, API connectors, filesystem access, browser access, database access, and integrations with services like GitHub, Slack, Google Drive, and internal tools.

Let models and agents interact with external systems, APIs, databases, files, and tools.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | 117.9k | 13049 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | 107.3k | 14712 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 87.3k | 8952 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 62.7k | 5621 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | 38.1k | 3244 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [ComposioHQ/composio](https://github.com/ComposioHQ/composio) | 30.5k | 4849 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) | 28.1k | 2470 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [browser-use/browser-harness](https://github.com/browser-use/browser-harness) | 18.4k | 1808 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) | 17.4k | 5647 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Jupyter Notebook](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) |
| [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) | 10.8k | 1505 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## UI and generative interface layer

This layer is more than normal frontend. It includes chat UIs, streaming responses, agent dashboards, tool-call displays, generated UI, copilot components, diff viewers, file attachments, code previews, and human approval interfaces.

Build the user-facing interface for AI applications.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 125.5k | 13126 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [streamlit/streamlit](https://github.com/streamlit/streamlit) | 46k | 4423 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [gradio-app/gradio](https://github.com/gradio-app/gradio) | 43.8k | 3627 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) | 38k | 4729 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [simstudioai/sim](https://github.com/simstudioai/sim) | 29.8k | 3855 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | 28.7k | 4823 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C#](https://img.shields.io/badge/-C%23-239120?logo=csharp&logoColor=white) |
| [assistant-ui/assistant-ui](https://github.com/assistant-ui/assistant-ui) | 12.5k | 1255 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [tambo-ai/tambo](https://github.com/tambo-ai/tambo) | 11.2k | 573 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [huggingface/chat-ui](https://github.com/huggingface/chat-ui) | 11k | 1697 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [thesysdev/openui](https://github.com/thesysdev/openui) | 10.9k | 728 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## AI coding agents and developer experience

This category includes AI coding assistants, autonomous coding agents, repo-editing agents, terminal agents, IDE extensions, pair programmers, code review tools, and systems that inspect, modify, test, and explain codebases.

Help developers write, edit, review, understand, and run code with AI.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 253.5k | 54971 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | 213.2k | 28600 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 162.7k | 8792 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) |
| [openai/codex](https://github.com/openai/codex) | 129k | 20280 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 111.5k | 6459 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) | 95.7k | 9591 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [cline/cline](https://github.com/cline/cline) | 70.3k | 7655 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [Aider-AI/aider](https://github.com/Aider-AI/aider) | 49.5k | 5053 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [continuedev/continue](https://github.com/continuedev/continue) | 36.2k | 5465 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) | 20.5k | 2253 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Evaluation and testing layer

This layer includes prompt tests, regression tests, model comparisons, RAG evaluation, hallucination checks, LLM-as-judge metrics, agent task success evaluation, red-team tests, and CI/CD quality gates.

Measure whether an AI app, prompt, RAG pipeline, model, or agent is improving or getting worse.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | 28.4k | 6449 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [ifixai-ai/iFixAi](https://github.com/ifixai-ai/iFixAi) | 26k | 1467 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | 26k | 2473 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [vibrantlabsai/ragas](https://github.com/vibrantlabsai/ragas) | 16k | 1758 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | 14.2k | 3675 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | 9.6k | 1367 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/PyRIT](https://github.com/microsoft/PyRIT) | 4.6k | 950 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [truera/trulens](https://github.com/truera/trulens) | 3.6k | 363 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [huggingface/lighteval](https://github.com/huggingface/lighteval) | 2.6k | 577 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [msoedov/agentic_security](https://github.com/msoedov/agentic_security) | 2k | 295 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Observability, tracing, and prompt management

This layer gives visibility into what happened inside an AI system. It includes tracing, span trees, prompt logs, completion logs, token usage, cost monitoring, feedback capture, prompt versioning, and evaluation dashboards.

Track prompts, completions, costs, latency, errors, tool calls, traces, retrieved context, and feedback.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) | 75.2k | 5836 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [evidentlyai/evidently](https://github.com/evidentlyai/evidently) | 8k | 950 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Jupyter Notebook](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) |
| [traceloop/openllmetry](https://github.com/traceloop/openllmetry) | 7.5k | 1153 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [Helicone/helicone](https://github.com/Helicone/helicone) | 6.2k | 683 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [coze-dev/coze-loop](https://github.com/coze-dev/coze-loop) | 5.8k | 800 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [latitude-dev/latitude-llm](https://github.com/latitude-dev/latitude-llm) | 4.7k | 401 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## Guardrails, safety, governance, and policy layer

This layer includes input and output filters, PII detection, jailbreak and prompt-injection defenses, safe tool calling, policy engines, human approvals, governance, compliance, audit logs, and red-team testing.

Prevent harmful outputs, unsafe tool calls, prompt injection, data leakage, and uncontrolled agent behavior.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | 20.1k | 1770 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [data-privacy-stack/presidio](https://github.com/data-privacy-stack/presidio) | 11.3k | 1345 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/presidio](https://github.com/microsoft/presidio) | 11.3k | 1345 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails) | 7.5k | 717 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [superagent-ai/superagent](https://github.com/superagent-ai/superagent) | 6.8k | 962 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | 6.4k | 1133 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [agentcontrol/agent-control](https://github.com/agentcontrol/agent-control) | 327 | 55 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Structured output and prompt engineering layer

This layer covers JSON schema outputs, function calling, typed model responses, constrained generation, grammar-constrained decoding, Pydantic-style validation, prompt templates, retries, and prompt optimization.

Make model outputs reliable, parseable, schema-valid, and usable by software.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [microsoft/promptflow](https://github.com/microsoft/promptflow) | 11.2k | 1122 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [IBM/mcp-context-forge](https://github.com/IBM/mcp-context-forge) | 4.6k | 924 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/apm](https://github.com/microsoft/apm) | 4k | 390 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Document ingestion, parsing, and data preparation

This layer includes PDF parsing, OCR, HTML cleanup, document ingestion, markdown conversion, table extraction, metadata extraction, deduplication, web crawling, and connector-based ingestion for RAG systems.

Convert messy real-world content into LLM-ready text and metadata.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) | 91k | 11480 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) | 85.5k | 8875 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [scrapy/scrapy](https://github.com/scrapy/scrapy) | 64.8k | 12000 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf) | 29.7k | 2819 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white) |
| [run-llama/liteparse](https://github.com/run-llama/liteparse) | 12.8k | 880 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |

## Model training, fine-tuning, and adaptation

For most app builders, this is not the first layer to learn, but it is part of the full picture. It includes supervised fine-tuning, LoRA, QLoRA, PEFT, DPO, RLHF, instruction tuning, adapter training, dataset formatting, and model export.

Customize models when prompting, RAG, and tool use are not enough.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [huggingface/transformers](https://github.com/huggingface/transformers) | 167.7k | 34874 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | 77.9k | 7198 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [pandas-dev/pandas](https://github.com/pandas-dev/pandas) | 50.1k | 20505 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI) | 41.4k | 4486 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [lm-sys/FastChat](https://github.com/lm-sys/FastChat) | 39.6k | 4782 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/onnxruntime](https://github.com/microsoft/onnxruntime) | 22.1k | 4307 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white) |

## Deployment, local inference, and model serving layer

This layer includes local model runners, inference servers, OpenAI-compatible local APIs, high-throughput serving, GPU inference, batching, quantization, autoscaling, Kubernetes deployment, and model-serving infrastructure.

Run models and AI services reliably in local, cloud, or production environments.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [ollama/ollama](https://github.com/ollama/ollama) | 183k | 18263 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) | 131.1k | 24379 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white) |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 93.7k | 23338 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [hiyouga/LlamaFactory](https://github.com/hiyouga/LlamaFactory) | 75.5k | 9247 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [mudler/LocalAI](https://github.com/mudler/LocalAI) | 49.5k | 4498 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [ray-project/ray](https://github.com/ray-project/ray) | 44k | 8143 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | 43.2k | 5036 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | 37.1k | 9527 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

---

## AI Models — Our Selection from Hugging Face

A hand-picked set of models we track, organized by category and task using our mapping of Hugging Face `pipeline_tag` values. These are selected models, rather than a comprehensive popularity ranking.

Model metadata is sourced from the [Hugging Face API](https://huggingface.co/docs/hub/api). Counts reflect this selection.

![banner_models](banners/banner_models.png)

| Category | Tasks represented | Models |
|---|---|---|
| [Language](#language) | 7 | 71 |
| [Image & Vision](#image-vision) | 5 | 21 |
| [Audio](#audio) | 4 | 42 |
| [Multimodal](#multimodal) | 2 | 19 |
| [Other](#other) | 2 | 4 |

### Language

[Text Generation (21)](#text-generation) · [Text Classification (5)](#text-classification) · [Token Classification (9)](#token-classification) · [Question Answering (5)](#question-answering) · [Summarization (3)](#summarization) · [Translation (12)](#translation) · [Embeddings & Features (16)](#embeddings-features)

#### Text Generation

Creates new text by continuing a prompt or responding to instructions.

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B) | 1.3M | 1.5M | 1765 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf) | 4.7M | 4.7M | 2675 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [ConwayResearch/Underdog-Saluki-27B-1.0](https://huggingface.co/ConwayResearch/Underdog-Saluki-27B-1.0) | 269.8k | 269.8k | 418 | Oct 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [XingChen-AGI/Xing4.0-29B-A4B](https://huggingface.co/XingChen-AGI/Xing4.0-29B-A4B) | 52.4k | 52.4k | 1842 | Oct 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [nvidia/Qwen3.6-35B-A3B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-35B-A3B-NVFP4) | 4.7M | 38.3M | 654 | Aug 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [nvidia/Qwen3.8-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.8-27B-NVFP4) | 633.9k | 671.5k | 191 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [ornith-ai/Ornith-1.5-9B-GGUF](https://huggingface.co/ornith-ai/Ornith-1.5-9B-GGUF) | 5.1M | 9.9M | 533 | Aug 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [ornith-ai/Ornith-1.5-35B-A3B-GGUF](https://huggingface.co/ornith-ai/Ornith-1.5-35B-A3B-GGUF) | 3.7M | 7.8M | 508 | Aug 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731) | 4.4M | 10.7M | 4081 | Aug 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [Aleph-Alpha/Kolibri-1](https://huggingface.co/Aleph-Alpha/Kolibri-1) | 15.3k | 15.3k | 926 | Oct 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Text Classification

Assigns labels to a piece of text, such as its topic, sentiment, or whether it is spam.

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [fastino/GLiNER2.5-Decide](https://huggingface.co/fastino/GLiNER2.5-Decide) | 100.5k | 100.5k | 410 | Oct 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya) | 46.2k | 46.2k | 5572 | Oct 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [convaiinnovations/laya-multilingual](https://huggingface.co/convaiinnovations/laya-multilingual) | 9.6k | 9.6k | 389 | Oct 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [BAAI/bge-reranker-v2-m3](https://huggingface.co/BAAI/bge-reranker-v2-m3) | 16M | 153.1M | 1258 | Jun 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [distilbert/distilbert-base-uncased-finetuned-sst-2-english](https://huggingface.co/distilbert/distilbert-base-uncased-finetuned-sst-2-english) | 2.7M | 404.2M | 977 | Dec 2023 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Token Classification

Labels individual words or tokens in text, for example to identify people, organizations, and places.

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [fastino/gliner2-privacy-filter-PII-multi](https://huggingface.co/fastino/gliner2-privacy-filter-PII-multi) | 211.3k | 521.1k | 99 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [openai/privacy-filter](https://huggingface.co/openai/privacy-filter) | 330.2k | 2.1M | 1795 | Apr 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-ForcedAligner-0.6B-hf](https://huggingface.co/Qwen/Qwen3-ForcedAligner-0.6B-hf) | 72.5k | 320.8k | 47 | Jun 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [OpenMed/privacy-filter-multilingual](https://huggingface.co/OpenMed/privacy-filter-multilingual) | 186.3k | 388.4k | 24 | May 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [perplexity-ai/PII-Tracer](https://huggingface.co/perplexity-ai/PII-Tracer) | 3.5k | 5.4k | 73 | Sep 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [OpenMed/OpenMed-PII-SuperClinical-Large-434M-v1](https://huggingface.co/OpenMed/OpenMed-PII-SuperClinical-Large-434M-v1) | 100k | 615.3k | 25 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [microsoft/llmlingua-2-xlm-roberta-large-meetingbank](https://huggingface.co/microsoft/llmlingua-2-xlm-roberta-large-meetingbank) | 157.1k | 3.6M | 35 | Jan 2025 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [dslim/bert-base-NER](https://huggingface.co/dslim/bert-base-NER) | 1.3M | 98M | 743 | Oct 2024 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [dslim/distilbert-NER](https://huggingface.co/dslim/distilbert-NER) | 184.9k | 2.9M | 54 | Oct 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Question Answering

Finds the answer to a question in a supplied passage.

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [deepset/roberta-base-squad2](https://huggingface.co/deepset/roberta-base-squad2) | 519.1k | 92.5M | 971 | Sep 2024 | cc-by-4.0 |
| [distilbert/distilbert-base-cased-distilled-squad](https://huggingface.co/distilbert/distilbert-base-cased-distilled-squad) | 189.4k | 26.5M | 277 | May 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [distilbert/distilbert-base-uncased-distilled-squad](https://huggingface.co/distilbert/distilbert-base-uncased-distilled-squad) | 32.2k | 13.3M | 123 | May 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google-bert/bert-large-uncased-whole-word-masking-finetuned-squad](https://huggingface.co/google-bert/bert-large-uncased-whole-word-masking-finetuned-squad) | 36k | 37.4M | 191 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google-bert/bert-large-cased-whole-word-masking-finetuned-squad](https://huggingface.co/google-bert/bert-large-cased-whole-word-masking-finetuned-squad) | 47.1k | 2.4M | 2 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Summarization

Condenses longer text into a shorter version that preserves its main points.

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [facebook/bart-large-cnn](https://huggingface.co/facebook/bart-large-cnn) | 1.4M | 149.6M | 1638 | Feb 2024 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [Falconsai/text_summarization](https://huggingface.co/Falconsai/text_summarization) | 10.4k | 2.1M | 325 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/roberta2roberta_L-24_bbc](https://huggingface.co/google/roberta2roberta_L-24_bbc) | 367 | 30.6k | 7 | Jan 2023 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Translation

Converts text from one language into another while preserving its meaning.

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [ai4bharat/indictrans2-en-indic-dist-200M](https://huggingface.co/ai4bharat/indictrans2-en-indic-dist-200M) | 239.6k | 971k | 65 | Oct 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [tencent/Hy-MT2-1.8B](https://huggingface.co/tencent/Hy-MT2-1.8B) | 28.9k | 274.3k | 1251 | May 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [tencent/Hy-MT2-30B-A3B](https://huggingface.co/tencent/Hy-MT2-30B-A3B) | 3.9k | 236.9k | 507 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [netease-youdao/Confucius4-T3PO](https://huggingface.co/netease-youdao/Confucius4-T3PO) | 1.7k | 1.7k | 79 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google-t5/t5-base](https://huggingface.co/google-t5/t5-base) | 1.9M | 175.2M | 802 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google-t5/t5-3b](https://huggingface.co/google-t5/t5-3b) | 247.2k | 21.3M | 53 | Jan 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Helsinki-NLP/opus-mt-zh-en](https://huggingface.co/Helsinki-NLP/opus-mt-zh-en) | 140.5k | 69M | 564 | Aug 2023 | cc-by-4.0 |
| [google/madlad400-3b-mt](https://huggingface.co/google/madlad400-3b-mt) | 36.7k | 4.6M | 240 | Nov 2023 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google-t5/t5-small](https://huggingface.co/google-t5/t5-small) | 23.8M | 285.8M | 681 | Jun 2023 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Helsinki-NLP/opus-mt-es-en](https://huggingface.co/Helsinki-NLP/opus-mt-es-en) | 179.7k | 26.3M | 82 | Aug 2023 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Embeddings & Features

Turns text into numerical representations that help compare meanings, find similar content, or support other machine learning tasks.

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [ibm-research/MoLFormer-XL-both-10pct](https://huggingface.co/ibm-research/MoLFormer-XL-both-10pct) | 257.7k | 9.2M | 43 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-Embedding-0.6B](https://huggingface.co/Qwen/Qwen3-Embedding-0.6B) | 8.5M | 94.3M | 1286 | Apr 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [intfloat/multilingual-e5-large](https://huggingface.co/intfloat/multilingual-e5-large) | 6.8M | 114.5M | 1274 | Apr 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [ibm-granite/granite-embedding-small-english-r2](https://huggingface.co/ibm-granite/granite-embedding-small-english-r2) | 5.2M | 28.5M | 104 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-Embedding-8B](https://huggingface.co/Qwen/Qwen3-Embedding-8B) | 2.1M | 25.2M | 832 | Jul 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [intfloat/multilingual-e5-large-instruct](https://huggingface.co/intfloat/multilingual-e5-large-instruct) | 1.6M | 34.2M | 649 | Jul 2025 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [Xenova/all-MiniLM-L6-v2](https://huggingface.co/Xenova/all-MiniLM-L6-v2) | 4.3M | 31.6M | 167 | Jul 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-Embedding-4B](https://huggingface.co/Qwen/Qwen3-Embedding-4B) | 1.8M | 22.1M | 340 | Jun 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [BAAI/bge-large-zh-v1.5](https://huggingface.co/BAAI/bge-large-zh-v1.5) | 375.1k | 28M | 650 | Apr 2024 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [BAAI/bge-large-en-v1.5](https://huggingface.co/BAAI/bge-large-en-v1.5) | 10.1M | 172.2M | 773 | Feb 2024 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |

### Image & Vision

[Text to Image (2)](#text-to-image) · [Image Classification (6)](#image-classification) · [Object Detection (7)](#object-detection) · [Image to Text (1)](#image-to-text) · [Text to Video (5)](#text-to-video)

#### Text to Image

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [Tongyi-MAI/Z-Image-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | 629.5k | 9.4M | 5467 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [black-forest-labs/FLUX.1-schnell](https://huggingface.co/black-forest-labs/FLUX.1-schnell) | 591.1k | 23.3M | 6250 | Aug 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Image Classification

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [pixai-labs/pixai-tagger-v1.0](https://huggingface.co/pixai-labs/pixai-tagger-v1.0) | 18.6k | 18.6k | 105 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [PSRben/VisionHOPE](https://huggingface.co/PSRben/VisionHOPE) | 1.9k | 1.9k | 449 | Sep 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [microsoft/resnet-50](https://huggingface.co/microsoft/resnet-50) | 357k | 574.5M | 526 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [microsoft/resnet-18](https://huggingface.co/microsoft/resnet-18) | 561.7k | 29.8M | 92 | Apr 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/vit-base-patch16-224](https://huggingface.co/google/vit-base-patch16-224) | 12.7M | 193.8M | 1037 | Sep 2023 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/vit-large-patch16-224](https://huggingface.co/google/vit-large-patch16-224) | 25.9k | 2.9M | 54 | Jun 2022 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Object Detection

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [Salesforce/GPA-GUI-Detector](https://huggingface.co/Salesforce/GPA-GUI-Detector) | 262 | 54.2k | 22 | Feb 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [facebook/detr-resnet-50](https://huggingface.co/facebook/detr-resnet-50) | 174.7k | 27.9M | 987 | Apr 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [hustvl/yolos-small](https://huggingface.co/hustvl/yolos-small) | 722k | 13.8M | 99 | May 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [hustvl/yolos-tiny](https://huggingface.co/hustvl/yolos-tiny) | 83k | 12M | 282 | Apr 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [microsoft/table-transformer-structure-recognition-v1.1-all](https://huggingface.co/microsoft/table-transformer-structure-recognition-v1.1-all) | 223.8k | 18.6M | 92 | Nov 2023 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [microsoft/table-transformer-structure-recognition](https://huggingface.co/microsoft/table-transformer-structure-recognition) | 1.2M | 39.5M | 240 | Sep 2023 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [facebook/detr-resnet-101](https://huggingface.co/facebook/detr-resnet-101) | 15.2k | 7.7M | 135 | Dec 2023 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Image to Text

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [microsoft/trocr-base-handwritten](https://huggingface.co/microsoft/trocr-base-handwritten) | 163.6k | 30.8M | 528 | Feb 2025 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |

#### Text to Video

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [larryvrh/MiniMax-H3-Turbo-Lora](https://huggingface.co/larryvrh/MiniMax-H3-Turbo-Lora) | 209.2k | 978.7k | 1107 | Aug 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [QuantStack/Wan2.2-T2V-A14B-GGUF](https://huggingface.co/QuantStack/Wan2.2-T2V-A14B-GGUF) | 141.1k | 2.7M | 306 | Jul 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Wan-AI/Wan2.1-T2V-1.3B-Diffusers](https://huggingface.co/Wan-AI/Wan2.1-T2V-1.3B-Diffusers) | 249.7k | 2.9M | 162 | Apr 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Wan-AI/Wan2.1-T2V-14B](https://huggingface.co/Wan-AI/Wan2.1-T2V-14B) | 54.5k | 1.2M | 1579 | Mar 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Wan-AI/Wan2.1-T2V-1.3B](https://huggingface.co/Wan-AI/Wan2.1-T2V-1.3B) | 51.8k | 437.2k | 627 | Mar 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

### Audio

[Speech to Text (15)](#speech-to-text) · [Text to Speech (10)](#text-to-speech) · [Audio Classification (5)](#audio-classification) · [Audio to Audio (12)](#audio-to-audio)

#### Speech to Text

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [nvidia/parakeet-tdt-0.6b-v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3) | 622.8k | 3.4M | 1193 | Aug 2026 | cc-by-4.0 |
| [nvidia/parakeet-tdt-0.6b-v2](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v2) | 176.3k | 11.8M | 1558 | Jun 2026 | cc-by-4.0 |
| [Cactus-Compute/whistle](https://huggingface.co/Cactus-Compute/whistle) | 21k | 21k | 381 | Oct 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [moondream/parakeet-redux](https://huggingface.co/moondream/parakeet-redux) | 17k | 17k | 284 | Sep 2026 | cc-by-4.0 |
| [moondream/parakeet-ultra](https://huggingface.co/moondream/parakeet-ultra) | 13.6k | 13.6k | 88 | Sep 2026 | cc-by-4.0 |
| [mistralai/Voxtral-Mini-4B-Realtime-2602](https://huggingface.co/mistralai/Voxtral-Mini-4B-Realtime-2602) | 1.9M | 13.3M | 1028 | Mar 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-ASR-1.7B](https://huggingface.co/Qwen/Qwen3-ASR-1.7B) | 1.1M | 16.6M | 1177 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-ASR-0.6B](https://huggingface.co/Qwen/Qwen3-ASR-0.6B) | 590.7k | 9.3M | 377 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [openai/whisper-large-v3-turbo](https://huggingface.co/openai/whisper-large-v3-turbo) | 6.3M | 122.8M | 3445 | Oct 2024 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [openai/whisper-large-v3](https://huggingface.co/openai/whisper-large-v3) | 3.7M | 149.9M | 6635 | Aug 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Text to Speech

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [ResembleAI/chatterbox](https://huggingface.co/ResembleAI/chatterbox) | 1.6M | 23.3M | 1845 | Jun 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [tencent/AuK](https://huggingface.co/tencent/AuK) | 3.7k | 5.5k | 387 | Sep 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [Qwen/Qwen3-TTS-12Hz-1.7B-CustomVoice](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-1.7B-CustomVoice) | 2.2M | 16.9M | 2117 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [microsoft/VibeVoice-1.5B](https://huggingface.co/microsoft/VibeVoice-1.5B) | 629.8k | 3.8M | 2500 | Jan 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [Qwen/Qwen3-TTS-12Hz-1.7B-VoiceDesign](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-1.7B-VoiceDesign) | 356.3k | 4.6M | 437 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-TTS-12Hz-0.6B-Base](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-Base) | 572.9k | 4.9M | 332 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-TTS-12Hz-0.6B-CustomVoice](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-CustomVoice) | 1M | 7.5M | 204 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [microsoft/VibeVoice-Realtime-0.5B](https://huggingface.co/microsoft/VibeVoice-Realtime-0.5B) | 255.3k | 6.1M | 1303 | Dec 2025 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [hexgrad/Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) | 10.6M | 130.6M | 7248 | Apr 2025 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [microsoft/speecht5_tts](https://huggingface.co/microsoft/speecht5_tts) | 48.9k | 6.2M | 847 | Nov 2023 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |

#### Audio Classification

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [speechbrain/lang-id-voxlingua107-ecapa](https://huggingface.co/speechbrain/lang-id-voxlingua107-ecapa) | 128.4k | 6.9M | 168 | Nov 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [speechbrain/emotion-recognition-wav2vec2-IEMOCAP](https://huggingface.co/speechbrain/emotion-recognition-wav2vec2-IEMOCAP) | 51.6k | 10.2M | 198 | Jul 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [superb/wav2vec2-base-superb-er](https://huggingface.co/superb/wav2vec2-base-superb-er) | 52.4k | 1.9M | 18 | Nov 2021 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [superb/hubert-base-superb-er](https://huggingface.co/superb/hubert-base-superb-er) | 4.5k | 2M | 22 | Nov 2021 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [superb/wav2vec2-base-superb-sid](https://huggingface.co/superb/wav2vec2-base-superb-sid) | 370 | 1.5M | 23 | Nov 2021 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Audio to Audio

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [neuphonic/neucodec](https://huggingface.co/neuphonic/neucodec) | 53.3k | 1.8M | 164 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-TTS-Tokenizer-12Hz](https://huggingface.co/Qwen/Qwen3-TTS-Tokenizer-12Hz) | 209.2k | 1.1M | 98 | Jan 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [mispeech/dashengtokenizer](https://huggingface.co/mispeech/dashengtokenizer) | 724 | 16.3k | 16 | Apr 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [nvidia/bigvgan_v2_24khz_100band_256x](https://huggingface.co/nvidia/bigvgan_v2_24khz_100band_256x) | 32.1k | 584.7k | 28 | Sep 2024 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [speechbrain/metricgan-plus-voicebank](https://huggingface.co/speechbrain/metricgan-plus-voicebank) | 15k | 655.6k | 72 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [speechbrain/sepformer-whamr16k](https://huggingface.co/speechbrain/sepformer-whamr16k) | 3.6k | 40.1k | 13 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [speechbrain/mtl-mimic-voicebank](https://huggingface.co/speechbrain/mtl-mimic-voicebank) | 1.2k | 372.8k | 35 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [speechbrain/sepformer-whamr](https://huggingface.co/speechbrain/sepformer-whamr) | 1.3k | 39k | 15 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [speechbrain/sepformer-wham](https://huggingface.co/speechbrain/sepformer-wham) | 277 | 21.2k | 45 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [speechbrain/sepformer-whamr-enhancement](https://huggingface.co/speechbrain/sepformer-whamr-enhancement) | 343 | 30.5k | 14 | Feb 2024 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

### Multimodal

[Vision-Language (10)](#vision-language) · [Any to Any (9)](#any-to-any)

#### Vision-Language

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash) | 1.3M | 1.6M | 4469 | Oct 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF) | 1.5M | 2.3M | 2190 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B) | 7.1M | 15.1M | 17635 | Aug 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | 1.2M | 8.8M | 4609 | Jul 2026 | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it) | 9.5M | 67M | 4116 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-26B-A4B-it](https://huggingface.co/google/gemma-4-26B-A4B-it) | 11.5M | 70.5M | 1647 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) | 3.6M | 31.2M | 2980 | Apr 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3.6-27B](https://huggingface.co/Qwen/Qwen3.6-27B) | 2.3M | 28.6M | 2328 | Apr 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3.5-9B](https://huggingface.co/Qwen/Qwen3.5-9B) | 8.4M | 69.4M | 2161 | Mar 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Agnes-AI/Agnes-3.0-Flash](https://huggingface.co/Agnes-AI/Agnes-3.0-Flash) | 1.9k | 2.6k | 250 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

#### Any to Any

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [openbmb/MiniCPM-o-2_6](https://huggingface.co/openbmb/MiniCPM-o-2_6) | 150.3k | 5.4M | 1320 | Aug 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [openbmb/MiniCPM-o-4_5](https://huggingface.co/openbmb/MiniCPM-o-4_5) | 670.1k | 3.4M | 1521 | Aug 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-12B-it](https://huggingface.co/google/gemma-4-12B-it) | 1.6M | 12.4M | 1660 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-E4B-it](https://huggingface.co/google/gemma-4-E4B-it) | 4.2M | 35.2M | 1710 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-E2B-it](https://huggingface.co/google/gemma-4-E2B-it) | 3.2M | 21M | 1036 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-E4B](https://huggingface.co/google/gemma-4-E4B) | 654.9k | 4.1M | 464 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-12B-it-qat-w4a16-ct](https://huggingface.co/google/gemma-4-12B-it-qat-w4a16-ct) | 898.7k | 6.5M | 67 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [lmstudio-community/gemma-4-E4B-it-MLX-4bit](https://huggingface.co/lmstudio-community/gemma-4-E4B-it-MLX-4bit) | 1.1M | 6.4M | 31 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [lmstudio-community/gemma-4-E4B-it-MLX-8bit](https://huggingface.co/lmstudio-community/gemma-4-E4B-it-MLX-8bit) | 1.1M | 6.2M | 17 | Jul 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

### Other

[Reinforcement Learning (3)](#reinforcement-learning)

#### Reinforcement Learning

| Model | Downloads (30d) | Downloads (all time) | Likes | Last updated | License |
|---|---|---|---|---|---|
| [mradermacher/Aztec-Coder-4B-i1-GGUF](https://huggingface.co/mradermacher/Aztec-Coder-4B-i1-GGUF) | 5.5k | 5.5k | 2 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [mradermacher/Evidence-RL-9B-i1-GGUF](https://huggingface.co/mradermacher/Evidence-RL-9B-i1-GGUF) | 2.9k | 2.9k | 1 | Sep 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [mradermacher/Metis-8B-RL-GGUF](https://huggingface.co/mradermacher/Metis-8B-RL-GGUF) | 447 | 2.7k | 2 | Apr 2026 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |