# CLAUDE.md

You are working on the repository **vibe-coding-playbook**.

Your task is to help generate and maintain a Russian-language textbook:

# Вайб-кодинг для ИТ-интегратора

## Project goal

Create a practical textbook for employees of KORUS Consulting with zero programming experience who want to learn AI-first development beyond a typical modern vibe coder.

The textbook must teach the reader to move from product idea to working web application using:

- Lovable
- GitHub
- Supabase
- Vercel
- v0 by Vercel
- Bolt.new
- Anthropic API
- Claude Code
- OpenClaw

The main learning project is:

**AI Advisory Intake Assistant**

This is a web application for an IT integrator employee that helps collect initial information about a client request before advisory, presales, or discovery.

---

## Repository structure

Use this structure:

```text
chapters/      — textbook chapters
appendices/    — advanced appendices
prompts/       — generation and review prompts
templates/     — practical artifact templates
sources/       — source notes and official documentation links
book.md        — final assembled textbook
chapters.yaml  — chapter manifest
README.md      — project overview
```

## Key input files

Before generating or editing the textbook, always read:
1. README.md
2. chapters.yaml
3. prompts/style_guide.md
4. prompts/universal_chapter_prompt.md
5. sources/source_notes.md

For full book generation, also read:
- prompts/book_orchestrator_prompt.md

For quality review, read:
- prompts/quality_review_prompt.md

For appendices, read:
- prompts/appendix_generation_prompt.md

## Writing rules

Write in Russian.
Write for a smart beginner, not for a child.
Do not write an abstract textbook. Write a practical learning playbook.

Every chapter must include:
1. clear purpose;
2. simple explanation;
3. connection to AI Advisory Intake Assistant;
4. practical hands-on steps;
5. AI prompts;
6. practical artifact;
7. typical beginner mistakes;
8. AI helps / AI should not / Human review required;
9. minimum security and quality guidance;
10. self-check questions;
11. Quality Gate;
12. concrete outputs after the chapter;
13. short executive summary for a manager.

## Style rules

Follow prompts/style_guide.md.

Avoid:
- generic consulting language;
- marketing tone;
- “AI will do everything” claims;
- vague phrases without action;
- pretending a prototype is production-ready.

Prefer:
- concrete steps;
- examples;
- checklists;
- templates;
- warnings;
- human review;
- honest limitations.

## Safety rules

Never include real:
- client data;
- personal data;
- passwords;
- tokens;
- API keys;
- OAuth secrets;
- private corporate information.

Never recommend pasting secrets into AI chats.

Never claim that a prototype is secure or production-ready without review.

For security-sensitive topics, use this default wording:
| In this chapter we cover the learning minimum. This is not a full security review. For corporate use, human review is required.

## AI and human review rules

Always separate:
- AI helps: What AI can prepare, explain, draft, test, or speed up.
- AI should not: What AI must not decide or execute alone.
- Human review required: What must be checked by a human.

This is mandatory for every chapter and appendix.

## Generation workflow

When asked to generate the textbook:
1. Do not write the entire book into the chat.
2. Work with repository files.
3. Generate one chapter per Markdown file.
4. Save chapters in chapters/.
5. Use filenames from prompts/book_orchestrator_prompt.md.
6. After all chapters are created, assemble book.md.
7. Do not skip Quality Gates.
8. Do not create chapters without practical artifacts.
9. Do not silently change the 24-chapter structure unless asked.

## Chapter generation checklist

Before saving a chapter, verify:
- Is it suitable for a beginner?
- Is it practical?
- Is it connected to AI Advisory Intake Assistant?
- Does it include the required artifact?
- Does it include prompts?
- Does it include beginner mistakes?
- Does it include human review?
- Does it include security minimum?
- Does it include a Quality Gate?
- Does it state what remains after the chapter?

If not, improve the chapter before saving.

## Source discipline

Use sources/source_notes.md.

Prefer official documentation.

Do not invent tool capabilities.

Do not describe UI buttons too precisely when interfaces may change.

Use durable wording:
- “open project settings”;
- “find the deployments section”;
- “create an environment variable”;
- “check the current official documentation”.

## Special caution for OpenClaw

Treat OpenClaw as an advanced topic.

Do not present it as a universal secure corporate multi-tenant platform.

Always mention:
- trust boundary;
- human approval;
- minimal permissions;
- logging;
- no destructive actions without confirmation.

## Final textbook standard

The final result must feel like a practical course for KORUS Consulting employees, not a collection of AI tool reviews.

A reader should finish the textbook with:
- a working learning project;
- GitHub repository;
- product brief;
- prototype;
- data model;
- Supabase backend;
- auth flow;
- Vercel deployment;
- AI feature;
- agent rules;
- demo script;
- final readiness checklist;
- clear understanding of risks and limitations.
