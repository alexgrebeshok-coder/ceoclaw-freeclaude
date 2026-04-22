# @freeclaude/coder — FreeClaude Coder

> **Multi-provider AI dev tool**: Claude, GPT-4o, Gemini · MCP-server · Hermes-compatible · Studio TMA

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Package](https://img.shields.io/badge/npm-%40freeclaude%2Fcoder-orange)](https://npm.pkg.github.com)

## Пакет

```ts
import { selectRoute, parseConfig, toSessionState } from '@freeclaude/coder'
```

## Модули

| Модуль | Описание |
|--------|----------|
| `types` | FreeClaude_QueryConfig, ProviderRoute, SessionState, ArtifactMeta |
| `session` | toSessionState, toSessionUpdate, appendMessage |
| `routing` | selectRoute, estimateCost, isModelAvailable |
| `config` | parseConfig, mergeConfig, DEFAULT_CONFIG |

## Установка

```bash
npm install @freeclaude/coder --registry=https://npm.pkg.github.com
```

## Часть экосистемы CEOClaw

- [@ceoclaw/engine](https://github.com/alexgrebeshok-coder/ceoclaw-engine) — AI engine (Apache 2.0)
- [@ochag/family](https://github.com/alexgrebeshok-coder/ceoclaw-ochag) — Семья (Apache 2.0)
- [@freeclaude/coder](https://github.com/alexgrebeshok-coder/ceoclaw-freeclaude) — Coder CLI (Apache 2.0)
