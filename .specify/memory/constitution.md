<!--
SYNC IMPACT REPORT
Version change: N/A → 1.0.0 (initial version)
Added sections: All principles and sections as specified
Removed sections: None (initial creation)
Templates requiring updates:
  - ✅ plan-template.md: Constitution Check section will now reference new principles
  - ✅ spec-template.md: No changes needed as it doesn't reference specific principles
  - ✅ tasks-template.md: No changes needed as it doesn't reference specific principles
Follow-up TODOs:
  - TODO(RATIFICATION_DATE): Need to determine original adoption date
-->

# AI / Spec-Driven Book with Embedded RAG Chatbot Constitution

## Core Principles

### Spec-first workflow using Spec-Kit Plus
All development must follow spec-first methodology using Spec-Kit Plus to ensure requirements are clearly defined before implementation. This ensures that all features are properly planned and documented before implementation begins.

### Technical accuracy strictly from official sources
All technical content must be grounded in official documentation and verified sources, with no hallucinated responses. This maintains the integrity and reliability of the information provided in the book and chatbot.

### Clear, developer-focused writing
All documentation and code examples must be written with developers in mind, providing clear, actionable guidance. This ensures the content is accessible and useful to the target audience.

### Fully reproducible setup and deployment
All implementations must be fully reproducible from the repository with clear setup and deployment instructions. This enables others to follow along and verify the implementations.

### Book content and user-selected text only
The RAG chatbot must be grounded only in book content and user-selected text, not external sources. This maintains the accuracy and consistency of the chatbot's responses.

### Technology stack compliance
Technology stack MUST be exactly: OpenAI Agents / ChatKit, FastAPI, Neon Postgres, Qdrant Cloud. This ensures consistency and compatibility across all implementations.

## Implementation Standards

All code MUST be runnable, well-documented, and reproducible end-to-end. GitHub-based source control is mandatory. No hallucinated responses under any condition. Every step MUST be reproducible from the repository. This ensures the quality and reliability of all implementations.

## Success Criteria

Book is live on GitHub Pages, embedded RAG chatbot is fully functional, all implementations strictly follow Spec-Kit Plus specs. This defines the measurable outcomes for the project.

## Governance

All implementations must follow the specified technology stack and deployment requirements. Changes must maintain reproducibility and technical accuracy. The constitution supersedes all other practices and must be referenced during all development activities.

**Version**: 1.0.0 | **Ratified**: TODO(RATIFICATION_DATE): Need to determine original adoption date | **Last Amended**: 2025-12-24