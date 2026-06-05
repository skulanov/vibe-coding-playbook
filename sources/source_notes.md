# Source Notes

Этот файл содержит официальные и приоритетные источники для учебника **«Вайб-кодинг для ИТ-интегратора»**.

Назначение файла:

- дать агенту опору на реальные источники;
- снизить риск выдумывания возможностей инструментов;
- зафиксировать, какие темы нужно проверять по документации;
- собрать ссылки для будущего приложения F “Полезные источники”.

Важно: интерфейсы AI-инструментов быстро меняются. Перед финальной публикацией учебника нужно проверить актуальность ссылок и формулировок.

---

# 1. Lovable

## Основные источники

- Lovable Documentation  
  https://docs.lovable.dev/

- Welcome to Lovable  
  https://docs.lovable.dev/introduction/welcome

- Quick start  
  https://docs.lovable.dev/introduction/getting-started

## Как использовать в учебнике

Lovable использовать как первый AI-builder для быстрого перехода от product brief к рабочему прототипу.

В главах важно раскрыть:

- создание первого проекта;
- итерации через natural language;
- проверку результата;
- ограничения прототипа;
- связь с backend, database, auth и deploy;
- почему прототип нельзя автоматически считать production-ready.

## Главы

- Глава 1
- Глава 4
- Глава 5
- Глава 6
- Глава 17
- Глава 18

---

# 2. GitHub

## Основные источники

- GitHub Docs  
  https://docs.github.com/

- About branches  
  https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches

- About commits  
  https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits

- About pull requests  
  https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests

- GitHub Pages  
  https://docs.github.com/en/pages

## Как использовать в учебнике

GitHub нужен как контур контроля AI-generated code.

В главах важно раскрыть:

- репозиторий;
- README;
- commit;
- branch;
- pull request;
- review;
- rollback mindset;
- GitHub Pages как простой первый публичный результат;
- почему нельзя хранить secrets в репозитории.

## Главы

- Глава 3
- Глава 7
- Глава 8
- Глава 9
- Глава 13
- Глава 15
- Глава 24

---

# 3. Supabase

## Основные источники

- Supabase Docs  
  https://supabase.com/docs

- Supabase Database  
  https://supabase.com/docs/guides/database

- Supabase Auth  
  https://supabase.com/docs/guides/auth

- Supabase Realtime  
  https://supabase.com/docs/guides/realtime

- Row Level Security  
  https://supabase.com/docs/guides/database/postgres/row-level-security

## Как использовать в учебнике

Supabase использовать как первый backend-контур: Postgres database, auth, realtime и RLS.

В главах важно раскрыть:

- таблицы;
- поля;
- связи;
- seed data;
- подключение приложения;
- auth;
- RLS;
- тестовых пользователей;
- негативные тесты доступа.

Особенно важно: RLS объяснять просто, но не упрощать до “галочки безопасности”. RLS — это часть authorization logic, и её должен проверить человек.

## Главы

- Глава 10
- Глава 11
- Глава 12
- Глава 14
- Глава 15
- Глава 21
- Глава 24

---

# 4. Vercel

## Основные источники

- Vercel Docs  
  https://vercel.com/docs

- Deploying Git Repositories with Vercel  
  https://vercel.com/docs/git

- Deploying GitHub Projects with Vercel  
  https://vercel.com/docs/git/vercel-for-github

- Environment Variables  
  https://vercel.com/docs/environment-variables

- Deployments  
  https://vercel.com/docs/deployments

## Как использовать в учебнике

Vercel использовать как основной deployment-контур.

В главах важно раскрыть:

- подключение GitHub repository;
- preview deployment;
- production deployment;
- логи сборки;
- environment variables;
- secrets;
- отличие preview от production;
- почему публичная ссылка не означает production-ready.

## Главы

- Глава 13
- Глава 14
- Глава 15
- Глава 21
- Глава 24

---

# 5. v0 by Vercel

## Основные источники

- v0 Docs  
  https://v0.app/docs/

- v0 Quickstart  
  https://v0.app/docs/quickstart

- Full-stack apps  
  https://v0.app/docs/full-stack-apps

- Deployments  
  https://v0.app/docs/deployments

- Agentic features  
  https://v0.app/docs/agentic-features

## Как использовать в учебнике

v0 использовать как UI-first и full-stack AI-инструмент для генерации интерфейсов, компонентов и прототипов.

В главах важно раскрыть:

- генерацию UI по prompt;
- компонентный подход;
- формы;
- dashboard;
- перенос идей в основной проект;
- ограничения UI-first подхода;
- human review для UX и доступности.

## Главы

- Глава 16
- Глава 18

---

# 6. Bolt.new

## Основные источники

- Bolt.new  
  https://bolt.new/

- Bolt.new GitHub repository  
  https://github.com/stackblitz/bolt.new

- Introduction to Bolt  
  https://support.bolt.new/building/intro-bolt

## Как использовать в учебнике

Bolt.new использовать как альтернативный AI-stack для full-stack экспериментов и сравнения с Lovable.

В главах важно раскрыть:

- prompt-to-app workflow;
- создание мини-проекта;
- отличие от Lovable;
- скорость;
- контроль;
- качество результата;
- ограничения браузерной разработки.

## Главы

- Глава 17
- Глава 18

---

# 7. Anthropic API

## Основные источники

- Claude API Docs  
  https://platform.claude.com/docs/

- Structured outputs  
  https://platform.claude.com/docs/en/build-with-claude/structured-outputs

- Prompt caching  
  https://platform.claude.com/docs/en/build-with-claude/prompt-caching

- Rate limits  
  https://platform.claude.com/docs/en/api/rate-limits

- Error handling  
  https://platform.claude.com/docs/en/api/errors

## Как использовать в учебнике

Anthropic API использовать как основу для AI-фич внутри продукта.

В главах важно раскрыть:

- API request;
- system и user instructions;
- structured outputs;
- JSON schema;
- prompt caching;
- rate limits;
- cost control;
- fallback;
- evals;
- обработку ошибок.

Важно: API key нельзя вставлять в frontend-код, публичный репозиторий или открытый AI-чат.

## Главы

- Глава 19
- Глава 20
- Глава 21

---

# 8. Claude Code

## Основные источники

- Claude Code overview  
  https://docs.anthropic.com/en/docs/claude-code/overview

- How Claude Code works  
  https://code.claude.com/docs/en/how-claude-code-works

- Best practices  
  https://code.claude.com/docs/en/best-practices

- CLAUDE.md / memory  
  https://docs.anthropic.com/en/docs/claude-code/memory

- Skills  
  https://docs.anthropic.com/en/docs/claude-code/skills

- Subagents  
  https://docs.anthropic.com/en/docs/claude-code/sub-agents

- Hooks guide  
  https://docs.anthropic.com/en/docs/claude-code/hooks-guide

- Hooks reference  
  https://docs.anthropic.com/en/docs/claude-code/hooks

- Common workflows  
  https://docs.anthropic.com/en/docs/claude-code/common-workflows

## Как использовать в учебнике

Claude Code использовать как переход от простого вайб-кодинга к agentic development workflow.

В главах важно раскрыть:

- CLAUDE.md как контекст проекта;
- Skills;
- subagents;
- hooks;
- permissions;
- работу с repository;
- анализ кода;
- тесты;
- refactoring;
- human approval;
- запрет destructive actions без подтверждения.

## Главы

- Глава 1
- Глава 3
- Глава 18
- Глава 22
- Глава 23
- Глава 24

---

# 9. OpenClaw

## Основные источники

- OpenClaw Docs  
  https://docs.openclaw.ai/

- Gateway architecture  
  https://docs.openclaw.ai/concepts/architecture

- Security  
  https://docs.openclaw.ai/gateway/security

- CLI Security  
  https://docs.openclaw.ai/cli/security

- Delegate architecture  
  https://docs.openclaw.ai/concepts/delegate-architecture

- Skills  
  https://docs.openclaw.ai/tools/skills

## Как использовать в учебнике

OpenClaw использовать только как advanced-тему по агентным сценариям.

В главах важно раскрыть:

- агентный gateway;
- delegate architecture;
- skills;
- агентные сценарии аудита, тестов и рефакторинга;
- trust boundary;
- human approval;
- логи действий;
- ограничения безопасности.

Особенно важно: не подавать OpenClaw как универсальную безопасную корпоративную multi-tenant платформу. В официальной документации есть предупреждение про personal assistant trust model и single-user boundary.

## Главы

- Глава 23
- Приложение E

---

# 10. OWASP и безопасность web-приложений

## Основные источники

- OWASP  
  https://owasp.org/

- OWASP Top 10  
  https://owasp.org/www-project-top-ten/

- OWASP Cheat Sheet Series  
  https://cheatsheetseries.owasp.org/

- OWASP API Security Top 10  
  https://owasp.org/www-project-api-security/

- OWASP LLM Top 10  
  https://owasp.org/www-project-top-10-for-large-language-model-applications/

## Как использовать в учебнике

OWASP использовать в приложениях, а не перегружать основной текст.

Темы:

- web application security;
- API security;
- secrets;
- auth;
- injection;
- prompt injection;
- data leakage;
- insecure output handling;
- excessive agency.

## Главы и приложения

- Глава 12
- Глава 14
- Глава 15
- Глава 19
- Глава 20
- Глава 21
- Глава 22
- Глава 23
- Приложение A
- Приложение D
- Приложение E

---

# 11. Как агент должен использовать источники

При генерации глав агент должен:

1. опираться на официальную документацию;
2. не выдумывать функции инструментов;
3. не обещать, что инструмент делает то, что не подтверждено документацией;
4. не описывать интерфейс слишком детально, если он может измениться;
5. писать устойчиво: “откройте настройки проекта”, “создайте deployment”, “добавьте environment variable”;
6. отмечать темы, которые требуют проверки по актуальной документации;
7. отделять учебный минимум от production-ready практик;
8. отправлять сложные темы в приложения.

---

# 12. Что проверить перед публикацией учебника

Перед публикацией версии 1.0 нужно проверить:

- актуальность ссылок;
- актуальность названий инструментов;
- не изменились ли интерфейсы Lovable, v0, Bolt.new, Supabase, Vercel;
- не изменились ли возможности Claude Code;
- не изменились ли условия и ограничения Anthropic API;
- не изменились ли security-предупреждения OpenClaw;
- нет ли ссылок на устаревшие или неофициальные материалы там, где нужна официальная документация.
