# @freeclaude/coder

> Lightweight shared package for **FreeClaude** routing, config parsing, and session-state helpers.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Package](https://img.shields.io/badge/npm-%40freeclaude%2Fcoder-orange)](https://npm.pkg.github.com)

## Роль репозитория

Этот репозиторий хранит **не полный FreeClaude CLI**, а небольшой standalone package `@freeclaude/coder`.

- **`freeclaude`** — основной CLI / workspace repo
- **`ceoclaw-freeclaude`** — маленький shared package repo

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

## Что экспортируется

- `routing` — provider routing и cost helpers
- `config` — parse/merge FreeClaude config
- `session` — session-state adapters
- `types` — public types

## Часть экосистемы

- [freeclaude](https://github.com/alexgrebeshok-coder/freeclaude) — основной FreeClaude CLI / workspace
- [pyrfor](https://github.com/alexgrebeshok-coder/pyrfor) — runtime / engine surfaces
- [ochag](https://github.com/alexgrebeshok-coder/ochag) — family AI repo

## Статус

Если нужен **полный продуктовый FreeClaude experience**, используй репозиторий [`freeclaude`](https://github.com/alexgrebeshok-coder/freeclaude).
Этот репозиторий нужен только для lightweight package surface.
