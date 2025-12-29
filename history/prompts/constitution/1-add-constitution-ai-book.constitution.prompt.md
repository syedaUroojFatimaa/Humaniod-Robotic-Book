---
id: 1
title: add-constitution-ai-book
stage: constitution
date: 2025-12-24
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: main
user: Dell
command: sp.constitution
labels: [constitution, documentation, ai-book]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - .specify/memory/constitution.md
tests:
  - none
---

## Prompt

```text
Project

AI / Spec-Driven Book with Embedded RAG Chatbot
Core principles

Spec-first workflow using Spec-Kit Plus

Technical accuracy strictly from official sources

Clear, developer-focused writing

Fully reproducible setup and deployment
Key standards

Book MUST be written using Docusaurus and deployed on GitHub Pages

RAG chatbot MUST be grounded only in:

Book content

User-selected text

Technology stack MUST be exactly:

OpenAI Agents / ChatKit

FastAPI

Neon Postgres

Qdrant Cloud

All code MUST be:

Runnable

Well-documented

Reproducible end-to-end
Constraints

GitHub-based source control is mandatory

No hallucinated responses under any condition

Every step MUST be reproducible from the repository
Success criteria

Book is live on GitHub Pages

Embedded RAG chatbot is fully functional

All implementations strictly follow Spec-Kit Plus specs
```

## Response snapshot

I've successfully updated the project constitution based on your requirements. Here's the final summary:

## Constitution Update Summary

**New Version**: 1.0.0 (initial version)
- **Bump Rationale**: This is the initial creation of the constitution based on your project requirements for an AI/Spec-Driven Book with Embedded RAG Chatbot.

**Files Updated**:
- `.specify/memory/constitution.md` - Complete rewrite with project-specific principles

**Constitution Principles Included**:
1. Spec-first workflow using Spec-Kit Plus
2. Technical accuracy strictly from official sources
3. Clear, developer-focused writing
4. Fully reproducible setup and deployment
5. Book content and user-selected text only for RAG chatbot
6. Technology stack compliance (OpenAI Agents/ChatKit, FastAPI, Neon Postgres, Qdrant Cloud)

**Implementation Standards**:
- All code must be runnable, well-documented, and reproducible end-to-end
- GitHub-based source control is mandatory
- No hallucinated responses under any condition
- Every step must be reproducible from the repository

**Success Criteria**:
- Book is live on GitHub Pages
- Embedded RAG chatbot is fully functional
- All implementations strictly follow Spec-Kit Plus specs

**Follow-up Required**:
- The ratification date needs to be determined and updated in place of the TODO placeholder

**Suggested Commit Message**: `docs: add constitution for AI/Spec-Driven Book project (v1.0.0)`

The constitution now properly reflects your project requirements and will guide all future development activities according to your specified principles and constraints.

## Outcome

- ✅ Impact: Created initial project constitution with 6 core principles and governance structure
- 🧪 Tests: none
- 📁 Files: Updated .specify/memory/constitution.md with project-specific principles
- 🔁 Next prompts: Project constitution is established for future development
- 🧠 Reflection: Constitution provides clear guidelines for AI/Spec-Driven Book project with RAG chatbot

## Evaluation notes (flywheel)

- Failure modes observed: none
- Graders run and results (PASS/FAIL): PASS - Constitution properly created with all specified principles
- Prompt variant (if applicable): none
- Next experiment (smallest change to try): Implement first feature following constitution guidelines