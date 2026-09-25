# MTEC 3501 – Supporting Document
## Week 5: Reference Guide — Infrastructure, Scope, and Research

---

## Why this guide exists

This guide provides definitions, examples, and step-by-step mechanics for the five parts of the [Week 5 Assignment](05_assignment_week05.md):

1. GitHub project infrastructure (Issues, sub-issues, board, Discussions, README)
2. Scope levels (NSV / LVP / PoC)
3. Research consolidation (Zotero + research markdown doc)
4. Make It Specific refinement
5. Miracle Questions / Unknowns

**Note on repository structure:** Each student has their own individual repository this semester (created from the MTEC 3501 Student Project Repository Template), not a shared class repository. All steps below refer to *your own* repository unless stated otherwise.

---

## 1) GitHub Project Infrastructure

### A. Creating Issues and Sub-Issues

1. Go to the **Issues** tab in your repository.
2. Click **New Issue**.
3. Give it a clear title (e.g., "Slide Deck — Draft") and a description of what's needed.
4. Apply a label describing the type of work (see the SRDMPA label set below).
5. Assign it to the presentation milestone (create the milestone first if it doesn't exist: **Issues → Milestones → New Milestone**).
6. To break a large issue into sub-issues: open the parent issue, use the **Sub-issues** section (or a task list with `- [ ]` checkboxes referencing linked issues), and create child issues for each smaller piece (e.g., a "Slide Deck" parent issue with sub-issues for "Introduction slide," "Research & precedents slides," "Project breakdown slide").

### Suggested SRDMPA Label Set

Based on the course's Speculate → Research → Design → Make/Produce → Present/Publish → Assess framework, with a numbered stage prefix:

- `01_speculative`
- `02_research-precedent`, `02_research-inspirational`, `02_research-technical`, `02_research-resource`
- `03_design`
- `04_produce-make`
- `05_present-publish`
- `06_assess`

These labels aren't in your repository by default this semester — create them yourself under **Issues → Labels → New label** (future semesters will have them pre-loaded via the student repository template). Add more specific labels as needed.

### B. Kanban Project Board

1. Go to the **Projects** tab in your repository (create a new project if you haven't already — choose the **Board** template).
2. Set up columns: **Backlog, Ready, In Progress, In Review, Done**.
3. Add your Issues to the board (search by title/number, or use "Add item").
4. As work progresses, drag issues across columns to reflect current status.

### C. Enabling GitHub Discussions

1. Go to your repository's **Settings → General**.
2. Scroll to the **Features** section and check **Discussions**.
3. Go to the new **Discussions** tab and click **New Discussion**.
4. Post a question, unknown, or problem — something genuinely unresolved, not a rhetorical one.
5. Visit a classmate's repository Discussions tab and reply with a suggestion or idea.

### D. README Update

Your README should, at minimum, include:

- Project title and a one-paragraph description
- A link to your speculative proposal (in-repo, or a linked external doc)
- A link to your research markdown document
- A reference/link to your Zotero collection

Markdown basics (bold, bullets, headers) are enough — see [GitHub's Markdown guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) if you need a refresher. Files written in Google Docs can be exported/saved as `.md` and dragged directly into your repository.

---

## 2) Scope Levels: NSV / LVP / PoC

| Level | What it means | Where it lives |
|---|---|---|
| **North Star Vision (NSV)** | The full, ambitious version of the project — the larger intellectual and creative universe it belongs to. | Speculative proposal |
| **Least Viable Product (LVP)** | The minimum version of the project that still fulfills its essential purpose — the target for the end of ENT 4501. | Speculative proposal |
| **Proof of Concept (PoC)** | The focused demonstration you will build and present this semester to test feasibility. | Speculative proposal + prototype plan |

Your proposal should make it easy for a reader to identify all three without guessing. A short, explicitly labeled subsection for each is sufficient at this stage.

---

## 3) Research Consolidation

### A. Zotero

- Precedent, inspirational, and technical research categories are unchanged from prior weeks — see the archived [Week 5 Research Areas reference](archive/05_document_research_specificity_miracle.md#1-zotero-research-consolidation) for full definitions and examples of each category.
- Use the Zotero **browser connector** to save sources directly into your sub-collection.
- Add **item notes** to entries to record findings and follow-up questions.
- You can drag items from a classmate's Zotero collection into your own, but do not remove items from someone else's collection.

### B. Generating a Bibliography

1. In Zotero, select the items (or the whole sub-collection).
2. Right-click → **Create Bibliography from Items**.
3. Choose a citation style (e.g., APA) and copy to clipboard.
4. Paste into your research markdown document (or a Google Doc, then export as `.md`).

### C. Research Markdown Document

- Create `docs/research.md` (or similar) in your repository.
- Link it from your README.
- Start with your generated bibliography, organized by category (precedent / inspirational / technical), and expand it as research continues.

---

## 4) Make It Specific Refinement

See the archived [Week 5 Make It Specific reference](archive/05_document_research_specificity_miracle.md#2-make-it-specific-refinement) for the full required structure, section-by-section guidance, and dependency examples — this content is unchanged.

---

## 5) Miracle Questions / Unknowns

See the archived [Week 5 Miracle Questions reference](archive/05_document_research_specificity_miracle.md#3-miracle-questions--unknowns) for the full definition, required dimensions, and the "Unknown / Why it matters / First test step" structure — this content is unchanged.

---

## Quality Checkpoint (all parts)

Before next class, verify:

- [ ] Every presentation deliverable has at least one Issue, labeled and on the milestone
- [ ] The board reflects real current status (not everything sitting in Backlog)
- [ ] Your Discussions post names a real, specific unknown
- [ ] README links all resolve (no dead links)
- [ ] NSV / LVP / PoC are each named and distinguishable in the proposal
- [ ] Zotero collection has entries in all three categories, with at least some annotations
- [ ] Research markdown document exists and is linked from the README
- [ ] Make It Specific document has no vague placeholders
- [ ] Miracle Questions list covers technical, design/UX, and narrative/content dimensions
