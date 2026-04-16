<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:334155&height=180&section=header&text=krnl-root&fontColor=e2e8f0&fontSize=56&fontAlignY=40&desc=agent%20infrastructure&descAlignY=65&descSize=16&descAlign=50" width="100%" />
</p>

## About

Agent infrastructure — recorders, replayers, tool protocols, evals, context compaction, multi-agent coordination. Building tooling that keeps LLM agents debuggable, reproducible, and portable across models.

Current focus: text-transcript-native agent runtimes. Representing an agent's context as a structured, replayable text record instead of a chain of SDK objects — so runs can be replayed against a different model, forked at any step, or diffed for non-determinism.

## Working On

- **agent-transcript** — model-agnostic agent run recorder and replayer. Records every LLM call, tool call, and memory mutation as a structured transcript. Framework-agnostic via thin adapters. First target: Vercel AI SDK.

More to come.

## Writing

Technical posts on agent infrastructure patterns — transcripts as context, cross-model replay, context compaction. *Blog — coming soon.*

## Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)

## Elsewhere

- X — [@xpranay_](https://x.com/xpranay_)
