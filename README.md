# Trending AI projects list

A curated overview of the top open-source AI repositories, organised by category. Each section covers a distinct layer of the modern AI stack — from orchestration frameworks and RAG pipelines to coding agents, evaluation tooling, and model serving infrastructure.
This list is subject to change and will be updated regularly.

*Maintained at [bobpage0451/ai-trending-repos](https://github.com/bobpage0451/ai-trending-repos) • Last updated: 2026-09-23 (refreshed bi-weekly)*

![banner_blackboard](banner_blackboard.png)
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
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 146.9k | 24584 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | 42.2k | 7138 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [appsmithorg/appsmith](https://github.com/appsmithorg/appsmith) | 40.9k | 4766 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents) | 29.7k | 4171 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 26.6k | 3175 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | MDX |
| [google/adk-python](https://github.com/google/adk-python) | 21.6k | 4058 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/agent-framework](https://github.com/microsoft/agent-framework) | 13.8k | 2368 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [Chainlit/chainlit](https://github.com/Chainlit/chainlit) | 12.5k | 1749 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [InternLM/lagent](https://github.com/InternLM/lagent) | 2.3k | 244 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [run-llama/llama-agents](https://github.com/run-llama/llama-agents) | 452 | 86 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## RAG, memory, and knowledge layer

This layer includes retrieval-augmented generation, semantic search, embeddings, vector storage, hybrid search, reranking, citations, document permissions, and short-term or long-term memory.

Give the model external, project, user, or company knowledge.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | 91.2k | 10814 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | 65.9k | 7748 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [MemPalace/mempalace](https://github.com/MemPalace/mempalace) | 59.2k | 7566 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | 52.3k | 8203 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [milvus-io/milvus](https://github.com/milvus-io/milvus) | 46.2k | 4268 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [VectifyAI/PageIndex](https://github.com/VectifyAI/PageIndex) | 35.8k | 3158 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [qdrant/qdrant](https://github.com/qdrant/qdrant) | 34.8k | 2691 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [chroma-core/chroma](https://github.com/chroma-core/chroma) | 29.4k | 2529 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [weaviate/weaviate](https://github.com/weaviate/weaviate) | 16.8k | 1407 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [memvid/memvid](https://github.com/memvid/memvid) | 16.6k | 1420 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |

## Agent and workflow layer

This layer covers tool-using agents, graph-based workflows, planner-executor patterns, multi-agent collaboration, human approval steps, state management, retries, and long-running task execution.

Build systems that can plan, call tools, perform multi-step tasks, and coordinate agents.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | 390.3k | 82117 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [langflow-ai/langflow](https://github.com/langflow-ai/langflow) | 155.2k | 10129 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [bytedance/deer-flow](https://github.com/bytedance/deer-flow) | 82.9k | 11475 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [FoundationAgents/MetaGPT](https://github.com/FoundationAgents/MetaGPT) | 70.6k | 8962 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | 59k | 8556 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [agno-agi/agno](https://github.com/agno-agi/agno) | 42.3k | 5997 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) | 34.4k | 4302 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [openai/openai-agents-python](https://github.com/openai/openai-agents-python) | 29.7k | 4801 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [huggingface/smolagents](https://github.com/huggingface/smolagents) | 29.5k | 2988 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [letta-ai/letta](https://github.com/letta-ai/letta) | 24.9k | 2628 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Tools, MCP, and integration layer

This layer includes Model Context Protocol servers and clients, tool schemas, function calling, API connectors, filesystem access, browser access, database access, and integrations with services like GitHub, Slack, Google Drive, and internal tools.

Let models and agents interact with external systems, APIs, databases, files, and tools.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | 116.1k | 12779 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | 107.1k | 14621 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 83.2k | 8484 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 52.6k | 4806 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | 37.5k | 3191 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [ComposioHQ/composio](https://github.com/ComposioHQ/composio) | 30.3k | 4819 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) | 27.9k | 2396 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [browser-use/browser-harness](https://github.com/browser-use/browser-harness) | 18.1k | 1763 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) | 17.3k | 5618 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Jupyter Notebook](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) |
| [mcp-use/mcp-use](https://github.com/mcp-use/mcp-use) | 10.7k | 1469 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## UI and generative interface layer

This layer is more than normal frontend. It includes chat UIs, streaming responses, agent dashboards, tool-call displays, generated UI, copilot components, diff viewers, file attachments, code previews, and human approval interfaces.

Build the user-facing interface for AI applications.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 124.5k | 10964 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [streamlit/streamlit](https://github.com/streamlit/streamlit) | 45.8k | 4392 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [gradio-app/gradio](https://github.com/gradio-app/gradio) | 43.6k | 3610 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) | 37.5k | 4655 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [simstudioai/sim](https://github.com/simstudioai/sim) | 29.7k | 3842 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) | 28.6k | 4785 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C#](https://img.shields.io/badge/-C%23-239120?logo=csharp&logoColor=white) |
| [assistant-ui/assistant-ui](https://github.com/assistant-ui/assistant-ui) | 12.3k | 1195 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [tambo-ai/tambo](https://github.com/tambo-ai/tambo) | 11.2k | 564 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [huggingface/chat-ui](https://github.com/huggingface/chat-ui) | 11k | 1688 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [thesysdev/openui](https://github.com/thesysdev/openui) | 9.8k | 683 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## AI coding agents and developer experience

This category includes AI coding assistants, autonomous coding agents, repo-editing agents, terminal agents, IDE extensions, pair programmers, code review tools, and systems that inspect, modify, test, and explain codebases.

Help developers write, edit, review, understand, and run code with AI.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 248.4k | 52489 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | 209.7k | 27663 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [openai/codex](https://github.com/openai/codex) | 126.2k | 19654 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |
| [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 107.5k | 6232 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) | 95.6k | 9581 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [cline/cline](https://github.com/cline/cline) | 69.2k | 7498 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [Aider-AI/aider](https://github.com/Aider-AI/aider) | 49.1k | 4985 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [continuedev/continue](https://github.com/continuedev/continue) | 36k | 5416 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) | 20.4k | 2233 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Evaluation and testing layer

This layer includes prompt tests, regression tests, model comparisons, RAG evaluation, hallucination checks, LLM-as-judge metrics, agent task success evaluation, red-team tests, and CI/CD quality gates.

Measure whether an AI app, prompt, RAG pipeline, model, or agent is improving or getting worse.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | 28.1k | 6347 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | 25.4k | 2365 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [vibrantlabsai/ragas](https://github.com/vibrantlabsai/ragas) | 15.8k | 1725 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [ifixai-ai/iFixAi](https://github.com/ifixai-ai/iFixAi) | 15.7k | 1334 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [EleutherAI/lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | 14.1k | 3596 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | 9.3k | 1305 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [truera/trulens](https://github.com/truera/trulens) | 3.6k | 346 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [huggingface/lighteval](https://github.com/huggingface/lighteval) | 2.5k | 559 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [msoedov/agentic_security](https://github.com/msoedov/agentic_security) | 2k | 290 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Observability, tracing, and prompt management

This layer gives visibility into what happened inside an AI system. It includes tracing, span trees, prompt logs, completion logs, token usage, cost monitoring, feedback capture, prompt versioning, and evaluation dashboards.

Track prompts, completions, costs, latency, errors, tool calls, traces, retrieved context, and feedback.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [headroomlabs-ai/headroom](https://github.com/headroomlabs-ai/headroom) | 73.6k | 5682 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [evidentlyai/evidently](https://github.com/evidentlyai/evidently) | 7.9k | 926 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Jupyter Notebook](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) |
| [traceloop/openllmetry](https://github.com/traceloop/openllmetry) | 7.4k | 1090 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [Helicone/helicone](https://github.com/Helicone/helicone) | 6.2k | 674 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [coze-dev/coze-loop](https://github.com/coze-dev/coze-loop) | 5.7k | 797 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [latitude-dev/latitude-llm](https://github.com/latitude-dev/latitude-llm) | 4.7k | 394 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |

## Guardrails, safety, governance, and policy layer

This layer includes input and output filters, PII detection, jailbreak and prompt-injection defenses, safe tool calling, policy engines, human approvals, governance, compliance, audit logs, and red-team testing.

Prevent harmful outputs, unsafe tool calls, prompt injection, data leakage, and uncontrolled agent behavior.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | 18.2k | 1573 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [data-privacy-stack/presidio](https://github.com/data-privacy-stack/presidio) | 11k | 1306 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/presidio](https://github.com/microsoft/presidio) | 11k | 1306 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails) | 7.4k | 707 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [superagent-ai/superagent](https://github.com/superagent-ai/superagent) | 6.8k | 963 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white) |
| [microsoft/agent-governance-toolkit](https://github.com/microsoft/agent-governance-toolkit) | 6.3k | 1126 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [agentcontrol/agent-control](https://github.com/agentcontrol/agent-control) | 313 | 52 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Structured output and prompt engineering layer

This layer covers JSON schema outputs, function calling, typed model responses, constrained generation, grammar-constrained decoding, Pydantic-style validation, prompt templates, retries, and prompt optimization.

Make model outputs reliable, parseable, schema-valid, and usable by software.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [microsoft/promptflow](https://github.com/microsoft/promptflow) | 11.2k | 1123 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [IBM/mcp-context-forge](https://github.com/IBM/mcp-context-forge) | 4.5k | 887 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/apm](https://github.com/microsoft/apm) | 3.9k | 372 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

## Document ingestion, parsing, and data preparation

This layer includes PDF parsing, OCR, HTML cleanup, document ingestion, markdown conversion, table extraction, metadata extraction, deduplication, web crawling, and connector-based ingestion for RAG systems.

Convert messy real-world content into LLM-ready text and metadata.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [scrapy/scrapy](https://github.com/scrapy/scrapy) | 64.5k | 11973 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [opendataloader-project/opendataloader-pdf](https://github.com/opendataloader-project/opendataloader-pdf) | 29.4k | 2797 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Java](https://img.shields.io/badge/-Java-ED8B00?logo=openjdk&logoColor=white) |
| [run-llama/liteparse](https://github.com/run-llama/liteparse) | 12.5k | 855 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white) |

## Model training, fine-tuning, and adaptation

For most app builders, this is not the first layer to learn, but it is part of the full picture. It includes supervised fine-tuning, LoRA, QLoRA, PEFT, DPO, RLHF, instruction tuning, adapter training, dataset formatting, and model export.

Customize models when prompting, RAG, and tool use are not enough.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [huggingface/transformers](https://github.com/huggingface/transformers) | 166.6k | 34660 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [unslothai/unsloth](https://github.com/unslothai/unsloth) | 76.6k | 7018 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [pandas-dev/pandas](https://github.com/pandas-dev/pandas) | 49.8k | 20421 | ![BSD-3-Clause](https://img.shields.io/badge/license-BSD%203--Clause-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI) | 41.4k | 4498 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [lm-sys/FastChat](https://github.com/lm-sys/FastChat) | 39.5k | 4775 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [microsoft/onnxruntime](https://github.com/microsoft/onnxruntime) | 21.9k | 4248 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white) |

## Deployment, local inference, and model serving layer

This layer includes local model runners, inference servers, OpenAI-compatible local APIs, high-throughput serving, GPU inference, batching, quantization, autoscaling, Kubernetes deployment, and model-serving infrastructure.

Run models and AI services reliably in local, cloud, or production environments.

| Repository | ⭐ Stars | 🍴 Forks | License | Language |
|---|---|---|---|---|
| [ollama/ollama](https://github.com/ollama/ollama) | 181.5k | 17982 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) | 129.3k | 23648 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white) |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | 92.5k | 22576 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [hiyouga/LlamaFactory](https://github.com/hiyouga/LlamaFactory) | 75k | 9183 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [mudler/LocalAI](https://github.com/mudler/LocalAI) | 49.2k | 4464 | ![MIT](https://img.shields.io/badge/license-MIT-blue) | ![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white) |
| [ray-project/ray](https://github.com/ray-project/ray) | 43.9k | 8074 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | 43.2k | 5000 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | 36.4k | 9100 | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) |

---

## Popular AI Models — Our Selection from Hugging Face

A hand-picked set of models we track — not necessarily the most popular or trending, just ones we find worth keeping an eye on, grouped by task area.

*Model metadata sourced from the [Hugging Face API](https://huggingface.co/docs/hub/api).*

- [🎵 Audio](#audio)
- [🖼️ Image & Vision](#image-vision)
- [🗣️ Language](#language)
- [🌐 Multimodal](#multimodal)

---

### 🎵 Audio

| Model | Author | Downloads (all time) | Likes | Subcategory | License |
|---|---|---|---|---|---|
| [pyannote/speaker-diarization-3.1](https://huggingface.co/pyannote/speaker-diarization-3.1) | pyannote | 348.4M | 3864 | Speech to Text | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [openai/whisper-large-v3](https://huggingface.co/openai/whisper-large-v3) | openai | 147.4M | 6349 | Speech to Text | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [openai/whisper-small](https://huggingface.co/openai/whisper-small) | openai | 135.4M | 603 | Speech to Text | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [hexgrad/Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) | hexgrad | 123.7M | 6991 | Text to Speech | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [openai/whisper-large-v3-turbo](https://huggingface.co/openai/whisper-large-v3-turbo) | openai | 118.5M | 3387 | Speech to Text | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [openai/whisper-base](https://huggingface.co/openai/whisper-base) | openai | 49.5M | 289 | Speech to Text | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [openai/whisper-tiny](https://huggingface.co/openai/whisper-tiny) | openai | 22.8M | 447 | Speech to Text | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [ResembleAI/chatterbox](https://huggingface.co/ResembleAI/chatterbox) | ResembleAI | 22.2M | 1798 | Text to Speech | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [openai/whisper-medium](https://huggingface.co/openai/whisper-medium) | openai | 20.3M | 302 | Speech to Text | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-ASR-1.7B](https://huggingface.co/Qwen/Qwen3-ASR-1.7B) | Qwen | 15.8M | 1116 | Speech to Text | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

### 🖼️ Image & Vision

| Model | Author | Downloads (all time) | Likes | Subcategory | License |
|---|---|---|---|---|---|
| [microsoft/table-transformer-structure-recognition](https://huggingface.co/microsoft/table-transformer-structure-recognition) | microsoft | 38.6M | 231 | Object Detection | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [microsoft/trocr-base-handwritten](https://huggingface.co/microsoft/trocr-base-handwritten) | microsoft | 30.7M | 523 | Image to Text | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [facebook/detr-resnet-50](https://huggingface.co/facebook/detr-resnet-50) | facebook | 27.8M | 977 | Object Detection | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [microsoft/table-transformer-structure-recognition-v1.1-all](https://huggingface.co/microsoft/table-transformer-structure-recognition-v1.1-all) | microsoft | 18.4M | 86 | Object Detection | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [hustvl/yolos-small](https://huggingface.co/hustvl/yolos-small) | hustvl | 13.3M | 98 | Object Detection | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [hustvl/yolos-tiny](https://huggingface.co/hustvl/yolos-tiny) | hustvl | 12M | 282 | Object Detection | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [facebook/detr-resnet-101](https://huggingface.co/facebook/detr-resnet-101) | facebook | 7.7M | 131 | Object Detection | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Salesforce/GPA-GUI-Detector](https://huggingface.co/Salesforce/GPA-GUI-Detector) | Salesforce | 54k | 20 | Object Detection | ![MIT](https://img.shields.io/badge/license-MIT-blue) |

### 🗣️ Language

| Model | Author | Downloads (all time) | Likes | Subcategory | License |
|---|---|---|---|---|---|
| [openai-community/gpt2](https://huggingface.co/openai-community/gpt2) | openai-community | 927.6M | 4167 | Text Generation | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [BAAI/bge-base-en-v1.5](https://huggingface.co/BAAI/bge-base-en-v1.5) | BAAI | 572.2M | 500 | Embeddings & Features | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [BAAI/bge-small-en-v1.5](https://huggingface.co/BAAI/bge-small-en-v1.5) | BAAI | 472.6M | 590 | Embeddings & Features | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [distilbert/distilbert-base-uncased-finetuned-sst-2-english](https://huggingface.co/distilbert/distilbert-base-uncased-finetuned-sst-2-english) | distilbert | 402.5M | 956 | Text Classification | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google-t5/t5-small](https://huggingface.co/google-t5/t5-small) | google-t5 | 269.3M | 636 | Translation | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3-0.6B](https://huggingface.co/Qwen/Qwen3-0.6B) | Qwen | 223.6M | 1672 | Text Generation | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google-t5/t5-base](https://huggingface.co/google-t5/t5-base) | google-t5 | 174M | 793 | Translation | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [BAAI/bge-large-en-v1.5](https://huggingface.co/BAAI/bge-large-en-v1.5) | BAAI | 165.1M | 742 | Embeddings & Features | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [facebook/bart-large-cnn](https://huggingface.co/facebook/bart-large-cnn) | facebook | 148.8M | 1625 | Summarization | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [Qwen/Qwen3-8B](https://huggingface.co/Qwen/Qwen3-8B) | Qwen | 125.1M | 2036 | Text Generation | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |

### 🌐 Multimodal

| Model | Author | Downloads (all time) | Likes | Subcategory | License |
|---|---|---|---|---|---|
| [Qwen/Qwen3.5-9B](https://huggingface.co/Qwen/Qwen3.5-9B) | Qwen | 64.7M | 2022 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-26B-A4B-it](https://huggingface.co/google/gemma-4-26B-A4B-it) | google | 62.9M | 1543 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it) | google | 60.4M | 3904 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) | Qwen | 28.5M | 2864 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3.6-27B](https://huggingface.co/Qwen/Qwen3.6-27B) | Qwen | 27M | 2309 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B) | Qwen | 9.8M | 16125 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | baidu | 8.1M | 4282 | Vision-Language | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF) | ISTA-DASLab | 1.4M | 1606 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |
| [deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash) | deepseek-ai | 570.9k | 3658 | Vision-Language | ![MIT](https://img.shields.io/badge/license-MIT-blue) |
| [Agnes-AI/Agnes-3.0-Flash](https://huggingface.co/Agnes-AI/Agnes-3.0-Flash) | Agnes-AI | 1.9k | 243 | Vision-Language | ![Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue) |