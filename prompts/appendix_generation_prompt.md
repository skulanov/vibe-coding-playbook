# Appendix Generation Prompt

Ты — методист, AI-first product engineer, security-aware reviewer и редактор учебника для ИТ-интегратора.

Твоя задача — создать приложения к учебнику **«Вайб-кодинг для ИТ-интегратора»**.

Учебник предназначен для сотрудников КОРУС Консалтинг с нулевым опытом программирования, поэтому основной текст должен быть практичным и понятным. Приложения нужны для более глубокого изучения тем, которые нельзя полностью раскрывать в главах без перегруза новичка.

## Входные материалы

Используй:

- `README.md`
- `chapters.yaml`
- все главы в папке `chapters/`
- `book.md`, если он уже создан

## Главная задача

Создай приложения в папке `appendices/` как отдельные Markdown-файлы.

Нужно создать 6 файлов:

```text
appendices/A-security.md
appendices/B-code-quality.md
appendices/C-web-app-architecture.md
appendices/D-ai-features.md
appendices/E-agentic-development.md
appendices/F-useful-sources.md
```

## Приложение A. Безопасность

Файл: appendices/A-security.md

Раскрой:

1. клиентские данные и персональные данные;
2. secrets, tokens, passwords, API keys;
3. environment variables;
4. GitHub repository visibility;
5. Supabase RLS;
6. OAuth risks;
7. публичные preview deployments;
8. prompt injection;
9. data leakage;
10. agent permissions;
11. destructive actions;
12. human approval.

Обязательно дай:

- объяснение простым языком;
- чек-лист безопасности новичка;
- таблицу “можно / нельзя”;
- типовые ошибки;
- что должен проверить человек.

## Приложение B. Качество кода

Файл: appendices/B-code-quality.md

Раскрой:

1. зачем нужен code review;
2. README;
3. commit discipline;
4. branch и pull request;
5. linting;
6. тесты;
7. dependency updates;
8. rollback;
9. технический долг;
10. признаки плохого AI-generated code.

Обязательно дай:
- code review checklist;
- pull request checklist;
- таблицу признаков плохого кода;
- простой план улучшения проекта.

## Приложение C. Архитектура web-приложения

Файл: appendices/C-web-app-architecture.md

Раскрой:
1. frontend;
2. backend;
3. API;
4. database;
5. auth;
6. storage;
7. serverless;
8. hosting;
9. environments;
10. observability;
11. error handling;
12. интеграции.

Обязательно дай:
- схему “как web-приложение работает целиком”;
- словарь терминов;
- архитектуру сквозного проекта AI Advisory Intake Assistant;
- список типовых архитектурных ошибок новичка.

## Приложение D. AI-фичи внутри продукта

Файл: appendices/D-ai-features.md

Раскрой:
1. prompt design;
2. system instructions;
3. structured output;
4. JSON schema;
5. hallucination control;
6. evals;
7. prompt caching;
8. rate limits;
9. cost control;
10. fallback behavior;
11. logging;
12. privacy;
13. user consent.

Обязательно дай:
- AI Feature Checklist;
- пример JSON-контракта;
- eval checklist;
- таблицу рисков AI-фичи.

## Приложение E. Агентная разработка

Файл: appendices/E-agentic-development.md

Раскрой:
1. что такое coding agent;
2. CLAUDE.md;
3. Skills;
4. subagents;
5. hooks;
6. permissions;
7. tool access;
8. sandboxing;
9. audit logs;
10. human approval;
11. agent task board;
12. опасные сценарии.

Обязательно дай:
- Agent Rules Checklist;
- Human Approval Checklist;
- пример структуры CLAUDE.md;
- таблицу “агенту можно / агенту нельзя”.

## Приложение F. Полезные источники

Файл: appendices/F-useful-sources.md

Собери список полезных официальных и качественных источников по темам учебника.

Темы:
1. Lovable;
2. GitHub;
3. Supabase;
4. Vercel;
5. v0 by Vercel;
6. Bolt.new;
7. Anthropic API;
8. Claude Code;
9. OpenClaw;
10. OWASP;
11. secure coding;
12. web app architecture;
13. testing;
14. prompt injection;
15. AI evals.

Для каждого источника укажи:
- название;
- зачем читать;
- к каким главам относится;
- уровень сложности;
- что именно искать внутри источника.

Не вставляй сомнительные ссылки. Предпочитай официальную документацию и признанные инженерные материалы.

## Общие требования к приложениям
- Пиши на русском.
- Не перегружай новичка.
- Объясняй сначала простым языком, потом технически.
- Не обещай полной безопасности после чек-листа.
- Всегда разделяй:
  - что можно сделать самому;
  - что должен проверить эксперт;
  - что нельзя делать без разрешения.
- Не используй реальные клиентские данные, токены, пароли или API-ключи.
- Где уместно, добавляй таблицы и чек-листы.
- Каждое приложение должно быть применимо как справочник во время работы над главами.
