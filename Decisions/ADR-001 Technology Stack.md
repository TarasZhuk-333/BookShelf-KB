---
type: decision
status: accepted
project: BookShelf
tags: [architecture, adr]
documents:
  - "[[Components/Streamlit UI]]"
  - "[[Components/SQLite Storage]]"
---
# ADR-001 Technology Stack

## Контекст
Потрібен невеликий локальний застосунок із простим інтерфейсом та автоматизованими тестами.

## Рішення
Використати Python, Streamlit, SQLite та pytest.

## Наслідки
Швидка розробка, мінімум залежностей, просте локальне тестування.

Пов'язані компоненти: [[Streamlit UI]], [[SQLite Storage]].
