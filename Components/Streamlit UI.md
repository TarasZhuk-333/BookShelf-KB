---
type: component
project: BookShelf
tags: [ui, python]
depends_on:
  - "[[Components/SQLite Storage]]"
implements:
  - "[[Decisions/ADR-001 Technology Stack]]"
---
# Streamlit UI

Мінімальний вебінтерфейс для перегляду списку книг, додавання, редагування, видалення, пошуку та зміни статусу.

Інтерфейс взаємодіє з [[SQLite Storage]] і відображає сутності [[Book]].

Технологічне рішення: [[ADR-001 Technology Stack]].
