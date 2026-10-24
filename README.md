# Manas Mohanty

**Forward-deployed AI leader turning enterprise data into context — knowledge graphs · semantic layers · agentic platforms.**

🌐 **Portfolio website: https://lookformaddy.github.io**

Senior Engineering Leader, Data & AI. I build end-to-end AI & data platforms the way enterprises actually run them: governed, observable, evaluated, shipped. This profile is a working portfolio — every project below is a complete, documented, runnable system, built clean-room on synthetic data.

## Portfolio — enterprise-grade, end to end

### AI Engineering
- [context-engineering-platform](https://github.com/lookformaddy/context-engineering-platform) — Context assembly service for enterprise LLM applications: chunking, semantic metadata, freshness policies, vector retrieval, citation-carrying context bundles, golden-set evals.
- [agentic-workflow-platform](https://github.com/lookformaddy/agentic-workflow-platform) — Durable agent orchestration: checkpointed workflows, retries with backoff, human approval gates, full run history.
- [enterprise-rag-governance](https://github.com/lookformaddy/enterprise-rag-governance) — Permission-aware RAG governance: ACL-filtered retrieval before ranking, PII redaction at ingestion, chunk-level citations, abstention, leak-rate evals.
- [llm-gateway](https://github.com/lookformaddy/llm-gateway) — LLM gateway: model routing policies (cost / latency / quality / round-robin), per-tenant rate limits and monthly budget caps, fallback chains, USD cost accounting, hash-only PII-safe observability.
- [llm-evaluation-platform](https://github.com/lookformaddy/llm-evaluation-platform) — LLM evaluation platform: versioned golden datasets, five deterministic scorers (exact match, token F1, semantic similarity, faithfulness, safety/PII screen), regression gates vs baseline with per-slice gates, experiment comparison, trend/flakiness detection.
- [mcp-ai-assistant](https://github.com/lookformaddy/mcp-ai-assistant) — MCP-style tool server (stdio + HTTP) and assistant client: schema-validated tools, read/write permission scopes, full audit log.
- [multi-agent-research-automation](https://github.com/lookformaddy/multi-agent-research-automation) — Planner / researcher / analyst / writer / critic agent system producing source-cited reports with a verification pass.
- [secure-rag-chatbot-guardrails](https://github.com/lookformaddy/secure-rag-chatbot-guardrails) — RAG with document-ACL-enforced retrieval and a full guardrail stack: injection screening, PII redaction, groundedness checks.
- [llm-evaluation-pipeline](https://github.com/lookformaddy/llm-evaluation-pipeline) — CI-grade LLM evaluation: versioned golden datasets, multiple scorers, baseline regression gating, trend reports.
- [human-approved-agent-audit](https://github.com/lookformaddy/human-approved-agent-audit) — Governed agent runtime: risk-tiered human approvals for consequential actions, hash-chained tamper-evident audit log.
- [lora-finetuned-llm](https://github.com/lookformaddy/lora-finetuned-llm) — End-to-end LoRA fine-tuning: from-scratch adapters on a small transformer, real training run, base-vs-tuned evaluation, model card.
- [knowledge-graph-rag-assistant](https://github.com/lookformaddy/knowledge-graph-rag-assistant) — GraphRAG: hybrid chunk + multi-hop graph retrieval with graph-path citations (multi-hop eval: 100% vs 0% chunk-only).
- [ai-copilot-backend](https://github.com/lookformaddy/ai-copilot-backend) — Streaming AI copilot backend: fail-closed request pipeline with per-user rate limits, prompt-injection/PII guardrails, two-tier conversational memory under token budgets, agentic tool orchestration (schema-validated args, parallel fan-out, retries, timeouts), SSE streaming, and a JSONL trace for every request outcome.
- [multi-agent-orchestration](https://github.com/lookformaddy/multi-agent-orchestration) — Multi-agent orchestration framework: planner/worker agents over a task DAG, capability-matched assignment, versioned shared blackboard, failure recovery (retry, reassign, fallback), human approval gates, per-agent budgets, and cost/latency tracing.

### Data Engineering
- [streaming-lakehouse-platform](https://github.com/lookformaddy/streaming-lakehouse-platform) — Kafka-style event ingestion, stream processing with event-time windows, lakehouse tables with a transaction log, data-quality gates, latency SLIs.
- [elt-data-contracts-platform](https://github.com/lookformaddy/elt-data-contracts-platform) — ELT pipelines governed by data contracts: schema enforcement, contract versioning, breaking-change detection, quality gates.
- [data-quality-observability](https://github.com/lookformaddy/data-quality-observability) — Data quality observability: table profiling, declarative quality checks, anomaly detection on metric history, alerting with dedup, quality SLOs.
- [semantic-layer-metrics-platform](https://github.com/lookformaddy/semantic-layer-metrics-platform) — Governed semantic layer: metric definitions compiled to deterministic SQL, join fan-out guards, certification gates, TTL caching, metric-to-column lineage, query API.
- [customer-data-platform](https://github.com/lookformaddy/customer-data-platform) — Customer data platform: multi-source ingestion, deterministic + probabilistic identity resolution with merge/split audit, unified profile store, consent & erasure enforcement, segment builder, activation APIs.
- [data-governance-lineage](https://github.com/lookformaddy/data-governance-lineage) — Data governance control plane: dataset catalog with evidence-gated certification, column-level lineage graph with BFS impact analysis, role × classification access policies with audited break-glass, PII masking and erasure tombstones, lineage-aware taint propagation with stakeholder impact reports.
- [cdc-pipeline-platform](https://github.com/lookformaddy/cdc-pipeline-platform) — CDC pipeline platform: LSN-ordered change capture, snapshot + incremental merge, schema evolution with quarantine for incompatible changes, idempotent sinks, checkpoint replay, and lag/throughput metrics.

### ML Engineering
- [ml-platform-registry-monitoring](https://github.com/lookformaddy/ml-platform-registry-monitoring) — Governed model registry with promotion gates, canary & shadow deployments, drift (PSI/KS) and fairness monitoring, automatic rollback.
- [feature-store](https://github.com/lookformaddy/feature-store) — Feature store with point-in-time correct training sets, online/offline stores, and freshness monitoring.
- [experimentation-platform](https://github.com/lookformaddy/experimentation-platform) — A/B experimentation platform: deterministic hash assignment with exclusion layers, exposure logging, pure-stdlib stats, SRM checks, ship/no-ship readouts.
- [recommendation-serving](https://github.com/lookformaddy/recommendation-serving) — Recommendation serving: two-stage candidate generation and ranking, MMR diversity re-ranking, eligibility filters, latency-budget fallback, feedback loop, offline evaluation.
- [model-serving-at-scale](https://github.com/lookformaddy/model-serving-at-scale) — Model serving at scale: dynamic request batching, canary releases with auto-rollback on error/latency breach, shadow mode with agreement scoring, deterministic A/B routing, version registry, latency percentiles, deadline handling and load-shedding.
- [ml-cicd-validation-gates](https://github.com/lookformaddy/ml-cicd-validation-gates) — ML CI/CD validation gates: data gates (schema drift, ranges, null-rate, class balance), model gates (metric floors, must-beat-baseline delta, slice gates, latency/size budgets), McNemar regression detection vs production, reproducibility manifests, promotion stage machine with signed human approvals.
- [forecasting-platform](https://github.com/lookformaddy/forecasting-platform) — Time-series forecasting platform: from-scratch forecasters (seasonal-naive, Holt-Winters, trend regression), hierarchical reconciliation, rolling-origin backtesting with prediction intervals, champion selection, and versioned forecast registry.

## Themes I build in

Knowledge graphs · Semantic layers · Context engineering · Agentic AI systems · Data platforms · LLMOps / MLOps · Experimentation · Responsible AI & governance · End-to-end AI products (React, APIs, backend)

New projects land here regularly — follow along.
