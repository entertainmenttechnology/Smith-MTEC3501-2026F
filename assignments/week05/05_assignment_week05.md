# MTEC 3501 – Assignment
## Week 5: Project Infrastructure, Scope, and Research Consolidation

---

## Purpose

In Week 4's class session, everyone created their first GitHub Issues, set up a Kanban Project Board, and confirmed Zotero access. This week turns that infrastructure into a working system, while continuing to sharpen the project itself.

You are consolidating four threads at once:

1. **Project infrastructure** — Issues, sub-issues, Project Board, Discussions, README
2. **Scope** — Proof of Concept, Least Viable Product, North Star Vision
3. **Specificity** — refining your Make It Specific document
4. **Research** — Zotero consolidation and a research markdown document

This work prepares you for the **Weeks 7–8 midterm expert-feedback presentation**. The purpose of that presentation is to explain your developing project and receive advice from industry experts, not to present a finished project or a completed Proof of Concept (PoC). See the [Midterm Project Presentation and Deliverables](../../documents-Class/04_Detailed_Speculative_Proposal/02-Presentation_Deliverables.md) for the presentation purpose and a suggested slide sequence. Use placeholders only for work that is genuinely still in progress; your revised Make It Specific document must contain no placeholders.

For definitions, examples, and step-by-step mechanics for each part below, see the [Week 5 Reference Guide](05_document_week05_reference.md).

---

## Part 1 — GitHub Project Infrastructure

### A. Issues and Sub-Issues for the Midterm Presentation

- Create or update **Issues** for the Weeks 7–8 midterm expert-feedback presentation.
- Break the work into **Issues** for the project description and scope, research bibliography, slide deck and experience visual, technology and competency reflection, roadmap, and questions for the experts. Use the [suggested slide sequence](../../documents-Class/04_Detailed_Speculative_Proposal/02-Presentation_Deliverables.md#suggested-slide-sequence) to identify the presentation content.
- Where a deliverable is large, break it into **sub-issues** (for example, the slide deck could have issues for the Make It Specific experience, system explanation, research, scope, and next steps).
- Apply labels that reflect the type of work. A suggested starting set, using the course's SRDMPA stages with a numbered prefix:
  - `01_speculative`, `02_research-precedent`, `02_research-inspirational`, `02_research-technical`, `02_research-resource`, `03_design`, `04_produce-make`, `05_present-publish`, `06_assess`
  - These labels don't exist in your repository by default — create them yourself (Issues → Labels → New label). Add more specific labels as needed.

### B. Kanban Project Board

- Organize your Issues (including the ones created in class) into workflow columns: **Backlog, Ready, In Progress, In Review, Done**.
- Every Issue related to the presentation should be visible on the board in the correct column.
- **Do not create the GitHub milestone yet.** In Week 6, use the [GitHub Milestone Activity](../week06/06_activity_github_milestone.md) to create the milestone and assign the prepared Issues to it. Week 8 will cover scheduling work with dates in the Project Roadmap.

### C. GitHub Discussions

- Enable **Discussions** in your repository (Settings → General → Discussions).
- Post **at least one discussion item** this week: a question, unknown, or problem you want peer feedback on.
- Check at least one classmate's repository and respond to their discussion post.

### D. README Update

- Update your repository's main `README.md` with:
  - A brief project description
  - A link to your speculative proposal
  - A link to your research markdown document (Part 3 below)
  - A link (or reference) to your Zotero collection

---

## Part 2 — Define Your Three Scope Levels

In your project proposal (stored in your repository, or linked from your README if it lives elsewhere), explicitly define these scopes, from the focused work this semester outward:

1. **Proof of Concept (PoC)** — the focused demonstration you plan to build this semester to test an important part of the project. You should be able to describe it for the midterm presentation; it does not need to be built by then.
2. **Least Viable Product (LVP)** — the minimum complete project you plan to develop in ENT 4501, the following course. Explain how this semester's PoC could inform it.
3. **North Star Vision (NSV)** — the larger, aspirational direction of the project. It provides context for the LVP but is not a required build.

These three levels should be clearly labeled and easy to find in your proposal document.

---

## Part 3 — Research Consolidation

### A. Zotero

Using the research you started in Week 3/4, organize your personal Zotero sub-collection (under the class Students folder) so it includes references from these three core categories:

1. **Precedent Research**
2. **Inspirational Research**
3. **Technical Research**

Tag or organize entries clearly by category, and add annotations (item notes) where you have findings or follow-up questions.

If your project depends on ethically usable assets or materials, you may also organize **resource research**. This category is relevant when needed; every project is not required to have resource sources.

### B. Research Markdown Document

- Create a research markdown document in your repository (e.g., `docs/research.md`).
- Link it from your README.
- Generate citations from Zotero and include them in this Markdown document, organized by research category. Zotero remains your source library; the Markdown file is the shareable bibliography in your project repository.
- Include brief annotations or findings in the Markdown document, or link to relevant Zotero item notes. This document will grow into the annotated bibliography for the presentation.

---

## Part 4 — Make It Specific Refinement

Revise your **Make It Specific** document so it is clear, concrete, and internally consistent:

1. Working title
2. Format / technology
3. One-sentence project description
4. User / integrator experience
5. System description
6. Explicit dependency

Remove vague placeholders and ensure your project can be understood by someone outside your team.

Use the [Make It Specific Template](../../documents-Class/04_Detailed_Speculative_Proposal/Make_It_Specific_Template.md) and review the [Make It Specific Examples](../../documents-Class/04_Detailed_Speculative_Proposal/Make_It_Specific_Examples.md) as needed. This is a revision of the Week 4 document, not a new worksheet.

**Clarification: What "Explicit Dependency" means**

An explicit dependency is the critical condition your project relies on to function as intended. If this condition fails, the core experience breaks down.

Good dependency examples:

- "This depends on low-latency input response so users can perceive real-time cause and effect."
- "This depends on reliable tracking in low light so gesture interaction remains usable."
- "This depends on stable API access so generated outputs can be produced during use."

Weak (too vague) dependency examples:

- "This depends on users liking it."
- "This depends on good technology."
- "This depends on everything working."

---

## Part 5 — Miracle Questions / Unknowns

Identify the key "miracle steps" in your project: places where major assumptions, gaps, or unresolved questions still exist. List unknowns across at least these dimensions:

1. **Technical unknowns** (tools, implementation, performance, integration)
2. **Design / UX unknowns** (interaction clarity, user flow, usability)
3. **Narrative / content unknowns** (meaning, coherence, communication)

For each unknown, include one brief note on how you might investigate or test it. These are excellent candidates for your GitHub Discussions post in Part 1C.

---

## Deliverable Checklist

By next class, your repository should show:

- [ ] Issues (and sub-issues where appropriate) created for the midterm expert-feedback presentation, labeled by SRDMPA/work type and visible on the Project board
- [ ] Kanban board organized into Backlog / Ready / In Progress / In Review / Done
- [ ] Discussions enabled, with at least one post (question/unknown/problem) and one peer reply
- [ ] README updated with project description and links (proposal, research doc, Zotero)
- [ ] Project proposal with PoC / LVP / NSV clearly defined and distinguished
- [ ] Zotero sub-collection organized across precedent, inspirational, and technical research
- [ ] Zotero-generated bibliography in a research Markdown document, linked from the README, with annotations or links to Zotero notes
- [ ] Revised Make It Specific document, using the Week 4 template structure and containing no placeholders
- [ ] Miracle Questions list (technical, design/UX, narrative/content) with next-step notes

---

## A Preview: Agile Next Week

Next class formally introduces an **Agile-style weekly workflow**: reporting your goals for the coming week, problems encountered in the last week, and current unknowns. The GitHub Discussions habit you're starting this week (Part 1C) is the foundation for that reporting rhythm — keep it up.

---

## Reminder

This is not about inventing a new direction. It's about making your existing direction infrastructure-ready, research-ready, build-ready, and critique-ready.
