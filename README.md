<p align="center">
  <a href="https://www.agentlist.io"><img src="media/banner.png" width="800" alt="Awesome Agent Observability — Agent tracing, evaluation, session inspection, cost tracking, and OpenTelemetry instrumentation."></a>
</p>

# Awesome Agent Observability

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributions welcome](https://img.shields.io/badge/contributions-welcome-f04424.svg)](CONTRIBUTING.md) [![CC0](https://img.shields.io/badge/license-CC0_1.0-6b6a64.svg)](LICENSE)

> Agent tracing, evaluation, session inspection, cost tracking, and OpenTelemetry instrumentation.

14 projects · Upstream documentation checked 2026-09-29. Curated by [agentlist.io](https://www.agentlist.io).

**Understand what your agent did, and whether it helped.**

Start with the question you cannot answer today: why a run failed, where the cost went, which tool call caused trouble, or whether a change improved the result. Traces, evaluations, and cost reports answer different questions. Choose the evidence you need before choosing a dashboard.

Tools for inspecting agent behavior, measuring usage, or evaluating outcomes. Tracing backends, instrumentation libraries, local session tools, and evaluation frameworks are distinct categories; one does not automatically replace another.

## Contents

- [How to choose](#how-to-choose)
- [Tracing and evaluation platforms](#tracing-and-evaluation-platforms)
- [Instrumentation](#instrumentation)
- [Usage and gateway monitoring](#usage-and-gateway-monitoring)
- [Evaluation and regression checks](#evaluation-and-regression-checks)
- [Related awesome lists](#related-awesome-lists)
- [More from Agentlist](#more-from-agentlist)
- [Contributing](#contributing)

## How to choose

- Works with: Does it capture your agent framework, model calls, and tools? Can you instrument custom steps and export standard telemetry?
- Runs where: Where are traces stored and evaluations executed? Which features are available when self-hosted?
- Needs access to: Will prompts, outputs, files, or credentials appear in telemetry? What redaction and access controls can you configure?
- Keeps what: Can you retain and export traces, datasets, evaluation results, and cost records? What are the retention boundaries?
- Human involvement: Can you follow a failed run, review examples, and turn findings into regression checks? Who reviews automated evaluation judgments?
- Main limitation: Which steps or costs remain invisible? A successful request, a low bill, and a useful task outcome are different measurements.

Use these questions to narrow your shortlist. An entry’s source link records the documentation used for its description; it does not mean every question above has been answered or tested. Treat undocumented capabilities as unknown, and confirm requirements against the linked project before adopting it.

## Tracing and evaluation platforms

- [AgentOps](https://github.com/AgentOps-AI/agentops) - Agent monitoring platform and SDK for execution traces, debugging, and cost tracking. **Platform and SDK.**
- [Langfuse](https://github.com/langfuse/langfuse) - Platform for tracing AI applications, managing prompts, and evaluating runs. **Self-hosted or cloud.**
- [LangSmith SDK](https://github.com/langchain-ai/langsmith-sdk) - Client libraries for sending traces and evaluation data to LangSmith. **Platform SDK.**
- [Opik](https://github.com/comet-ml/opik) - Platform for agent traces, evaluation datasets, and experiment monitoring. **Self-hosted or cloud.**
- [Phoenix](https://github.com/Arize-ai/phoenix) - AI observability platform for traces, evaluation, and dataset experiments. **Observability platform.**
- [Weave](https://github.com/wandb/weave) - Toolkit for tracing AI application functions and evaluating their outputs. **Toolkit and platform.**

## Instrumentation

- [OpenInference](https://github.com/Arize-ai/openinference) - OpenTelemetry instrumentation and conventions for AI application traces. **Instrumentation libraries.**
- [OpenLLMetry](https://github.com/traceloop/openllmetry) - OpenTelemetry extensions for instrumenting LLM applications and their integrations. **Instrumentation libraries.**

## Usage and gateway monitoring

- [ccusage](https://github.com/ccusage/ccusage) - CLI reports for coding-agent token usage and estimated costs from local session data. **Local CLI.**
- [Helicone](https://github.com/Helicone/helicone) - LLM observability platform for monitoring requests, usage, and experiments. **Request monitoring.**
- [LiteLLM](https://github.com/BerriAI/litellm) - Model gateway and SDK with spend tracking, logging, and provider routing. **Gateway and SDK.**

## Evaluation and regression checks

- [DeepEval](https://github.com/confident-ai/deepeval) - Evaluation framework for testing LLM applications, agent steps, and trajectories. **Python framework.**
- [Promptfoo](https://github.com/promptfoo/promptfoo) - CLI and library for evaluations and red-team testing of AI applications. **CLI and library.**
- [TruLens](https://github.com/truera/trulens) - Tracing and evaluation tools for examining agent behavior and application outcomes. **Evaluation toolkit.**

## Related awesome lists

Independent collections for deeper discovery. These are references, not affiliations or endorsements.

- [ContextJet-ai/awesome-llm-observability](https://github.com/ContextJet-ai/awesome-llm-observability) - Observability tools and practical evaluation resources.
- [tensorchord/Awesome-LLMOps](https://github.com/tensorchord/Awesome-LLMOps) - The wider LLM operations toolchain.
- [backblaze-labs/awesome-agent-infrastructure](https://github.com/backblaze-labs/awesome-agent-infrastructure) - Agent infrastructure including observability and evaluation.

## More from Agentlist

- [Awesome Agent List](https://github.com/AgentListIO/awesome-agent-list)
- [Awesome Personal Assistants](https://github.com/AgentListIO/awesome-personal-assistants)
- [Awesome Agent Clients](https://github.com/AgentListIO/awesome-agent-clients)
- [Awesome Agent Memory](https://github.com/AgentListIO/awesome-agent-memory)
- [Awesome Agent Sandboxes](https://github.com/AgentListIO/awesome-agent-sandboxes)
- [Awesome Agent Orchestration](https://github.com/AgentListIO/awesome-agent-orchestration)

**[Browse agents](https://www.agentlist.io/list-of-ai-agents) · [Compare agents](https://www.agentlist.io/compare) · [GitHub organization](https://github.com/AgentListIO)**

## Contributing

Missing something useful? Read the [contribution guide](CONTRIBUTING.md) and open an issue or pull request with an official source.

The machine-readable [list.json](list.json) includes a primary-source link and a documentation-check date for every entry. Descriptions are editorial summaries of upstream documentation; inclusion does not imply hands-on testing, a security audit, or endorsement. Hosted services and source code may have different terms.

To update the list, edit `list.json`, run `bun run build`, then `bun run check`. The README is generated; avoid editing it directly.

[CC0](LICENSE) applies to this list’s text and data. Linked projects retain their own licenses.
