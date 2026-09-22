---
layout: default
title: Architecture
---

# ModelStore Architecture

## Structure

```mermaid
flowchart LR
  A[App] --> B[ModelStore]
  B --> C[ResolveModelHome]
  B --> D[ResolveModelPath]
  B --> E[EnsureModelDir]
  C --> F["~/.local/share/deepseek/models"]
```
