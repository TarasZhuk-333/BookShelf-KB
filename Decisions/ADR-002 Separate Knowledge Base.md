---
type: decision
status: accepted
project: BookShelf
tags: [architecture, knowledge]
---
# ADR-002 Separate Knowledge Base

## Контекст
База знань повинна бути відокремлена від коду застосунку.

## Рішення
Зберігати Obsidian vault у власному Git-репозиторії `BookShelf-KB`. Для доступу агента в наступній практичній роботі передбачити MCP-конектор.

## Наслідки
Окреме версіонування знань і контрольований доступ через [[Agent Harness]].
