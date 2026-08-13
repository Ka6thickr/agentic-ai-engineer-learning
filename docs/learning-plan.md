# Agentic AI Engineer Learning Plan

This repository follows a 12-week practical path covering Microsoft Agent Framework, Microsoft Foundry, Azure AI Search, MCP, Microsoft 365 integration, GitHub Copilot Agent, and OpenAI Codex.

## Learning method

Each week follows four steps:
1. Understand the official documentation and architecture pattern.
2. Build the smallest working version manually.
3. Give one bounded extension to GitHub Copilot Agent and Codex.
4. Review the code, tests, documentation, and engineering tradeoffs yourself.

Recommended pace: Saturday and Sunday, 45–60 minutes per session. Use roughly 70% .NET/C# and 30% Python.

## Weekly plan

1. Agent fundamentals — first working agent, instructions, structured output, tests.
2. Tools and function calling — typed tools, validation, error handling, tests.
3. State, sessions and memory — conversation state and explicit memory boundaries.
4. RAG fundamentals — document ingestion, retrieval, grounded answers, citations.
5. Agentic retrieval — compare classic RAG and Azure AI Search agentic retrieval.
6. MCP — connect the agent to an MCP capability and test the integration.
7. Microsoft 365 and SharePoint — enterprise content integration through testable service interfaces.
8. Workflows and multi-agent patterns — orchestrate a repeatable multi-step business flow.
9. Microsoft Foundry Agent Service — deploy and operate a managed agent capability.
10. Evaluation and observability — build evaluation cases, tracing, latency and cost checks.
11. Security and enterprise architecture — document identity, authorization, service boundaries, data movement and approval points.
12. Capstone — complete an Enterprise SharePoint Knowledge & Action Agent with tests, documentation and demo scenarios.

## Capstone architecture

User → SPFx / Teams / Web UI → Agent API → Microsoft Agent Framework → retrieval, tools, Microsoft 365 integration and managed runtime.

Cross-cutting concerns: identity, authorization, evaluation, observability, configuration, deployment and testing.

## GitHub Copilot Agent workflow

Create one GitHub issue for each bounded engineering task. Include the expected result, constraints, test expectations, and relevant files or architecture boundaries. Review every change before merging.

## Codex workflow

Use `AGENTS.md` as repository guidance. Give Codex scoped tasks, require tests for behavior changes, ask it to run available validation, and require a final summary of files changed and anything it could not validate.

## Completion criteria

At the end of the track the repository should contain a working capstone, weekly implementation history, automated tests, a small evaluation suite, architecture and security notes, deployment guidance, and written comparisons of manual work, Copilot Agent and Codex.

See `resources/official-links.md` for the official documentation links and `ROADMAP.md` for the weekly checklist.
