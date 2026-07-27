---
name: karpathy-llm-wiki
description: Use when planning or building LLM apps, agents, RAG, evals, prompts, model-context workflows, AI knowledge systems, or architecture that may benefit from the Karpathy LLM Wiki in ~/Second_Brain.
---

# Karpathy LLM Wiki

Use the local Karpathy LLM Wiki as prior art and planning context.

## Location

- Vault: `~/Second_Brain`
- Entry point: `~/Second_Brain/index.md`
- Schema: `~/Second_Brain/AGENTS.md`
- Pattern overview: `~/Second_Brain/karpathy-llm-wiki.md`
- Wiki pages: `~/Second_Brain/wiki/`

## Query Workflow

1. Read `~/Second_Brain/index.md` first.
2. Identify relevant pages from the index.
3. Read only relevant pages under `~/Second_Brain/wiki/`.
4. If the task concerns the wiki pattern itself, also read `~/Second_Brain/karpathy-llm-wiki.md`.
5. Use findings as planning or implementation context, not as unquestioned truth.
6. Cite wiki files in plans, implementation notes, and swarm shared context.

## Write Policy

Default to read-only.

Only modify `~/Second_Brain` when the user explicitly asks to ingest, update, lint, or maintain the wiki.

Never edit files in `~/Second_Brain/raw/processed/`.
Only move files from `raw/unprocessed/` to `raw/processed/` during an explicit ingest workflow.

## Swarm Usage

For swarm planning:

- The planner should consult the wiki before decomposition when the task involves LLMs, agents, RAG, prompts, evals, AI infrastructure, or knowledge systems.
- Relevant wiki findings should be passed into subtask descriptions and shared context.

For swarm workers:

- Workers should consult the wiki when their assigned subtask touches LLM behavior, prompt design, model context, retrieval, evals, agent workflows, or knowledge-system code.
- Workers should summarize any wiki-derived constraints in progress and completion notes.
