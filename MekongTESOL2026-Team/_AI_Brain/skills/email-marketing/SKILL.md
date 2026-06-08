---
name: mekong-email-marketing
description: Create and modify email marketing templates for Mekong TESOL 2026, strictly adhering to the project's Design System and table-based constraints.
---

# Mekong TESOL Email Marketing Skill

Use this skill whenever you need to create, format, or update an HTML email marketing template for the Mekong TESOL 2026 project.

## Context & Workspace
- **Workspace Root**: `/Users/macbookpro/Documents/03_MekongTESOL/2026_Active` (Mac) or the equivalent path on the current user's OS.
- **Design System**: `_Design_System/project/Mekong TESOL Design System.html`
- **Template Library**: `Communications_Hub/01_Email_Templates/` — clone the most recent file here as a skeleton.
- **Output (drafts)**: `Communications_Hub/_Drafts/` — save all new drafts here.
- **Knowledge Base**: `_AI_Brain/knowledge_base.md` — read this for context on the conference.

## Mandatory Rules
1. **Layout**: Use `<table>` based layouts only, with `max-width: 600px`, for Gmail/Outlook compatibility. NO `div`-based grids or flexbox for the main email structure.
2. **CSS**: ALL styling must be **inline** (`style="..."`). Do not rely on `<style>` blocks in `<head>` for rendering.
3. **Design System**: MUST read the Design System file before creating or editing. Use the exact color tokens (Primary, Secondary, Info, etc.) and font stacks defined there.
4. **Assets / Images**: Do NOT change or replace header/footer banner image URLs. They are hosted on WordPress and are sacred.
5. **Naming Convention**: `email-[type]-[YYYY-MM-DD].html` (e.g., `email-early-bird-2026-07-01.html`).
6. **Brand Tone**: Professional, welcoming. Use correct terminology: "Cuu Long Hall", "Mekong TESOL 2026", "Can Tho University".
7. **Language**: Match the language of the user's request (Vietnamese or English).

## Workflow
1. **Read** `_AI_Brain/knowledge_base.md` for conference context.
2. **Read** `_Design_System/project/Mekong TESOL Design System.html` for design tokens.
3. **Clone** the most recent template from `Communications_Hub/01_Email_Templates/` as the HTML skeleton.
4. **Draft**: Insert new content. Convert formatting (bold, links, lists) to inline-styled HTML table rows.
5. **Check**: Confirm `max-width: 600px` container present, all CSS is inline, no broken image links.
6. **Save**: Write output to `Communications_Hub/_Drafts/` with proper naming convention.
7. **Report**: Summarize what was created and the file path.
