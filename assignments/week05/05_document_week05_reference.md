# MTEC 3501 – Supporting Document
## Week 5: Reference Guide — Infrastructure, Scope, and Research

---

## Why this guide exists

This guide provides definitions, examples, and step-by-step mechanics for the five parts of the [Week 5 Assignment](05_assignment_week05.md). The assignment prepares you for the [Weeks 7–8 midterm expert-feedback presentation](../../documents-Class/04_Detailed_Speculative_Proposal/02-Presentation_Deliverables.md):

1. GitHub project infrastructure (Issues, sub-issues, board, Discussions, README)
2. Scope levels (PoC / LVP / NSV)
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
5. Do not create or assign a milestone as part of this Week 5 preparation. In Week 6, follow the [GitHub Milestone Activity](../week06/06_activity_github_milestone.md) to create a milestone and assign the relevant Issues. A milestone groups Issues; it is not itself a Kanban card.
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

In Week 5, make sure the presentation Issues are on the board. Create the repository milestone and assign the Issues during the Week 6 activity. Start and Target Date fields and Roadmap scheduling are introduced in Week 8.

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

## 2) Scope Levels: PoC / LVP / NSV

| Level | What it means | Where it lives |
|---|---|---|
| **Proof of Concept (PoC)** | The focused demonstration planned for this semester to test an important part of the project. It does not need to be built for the midterm expert-feedback presentation. | Project proposal + PoC plan |
| **Least Viable Product (LVP)** | The minimum complete version planned for ENT 4501, the following course. | Project proposal + LVP design/planning document |
| **North Star Vision (NSV)** | The larger, aspirational direction that gives context to the LVP; it is not a required build. | Project proposal |

Your proposal should make it easy for a reader to identify all three without guessing. A short, explicitly labeled subsection for each is sufficient at this stage. Explain how the PoC informs the LVP and how the LVP relates to the NSV.

---

## 3) Research Consolidation

### A. Zotero

- Precedent, inspirational, and technical research categories are unchanged from prior weeks — see the archived [Week 5 Research Areas reference](archive/05_document_research_specificity_miracle.md#1-zotero-research-consolidation) for full definitions and examples of each category.
- Resource research may also be included when the project depends on ethically usable assets or materials; it is not a required category for every project.
- Use the Zotero **browser connector** to save sources directly into your sub-collection.
- Add **item notes** to entries to record findings and follow-up questions.
- You can drag items from a classmate's Zotero collection into your own, but do not remove items from someone else's collection.

### B. Generating a Bibliography

1. In Zotero, select the items (or the whole sub-collection).
2. Right-click → **Create Bibliography from Items**.
3. Choose a citation style (e.g., APA) and copy to clipboard.
4. Paste the generated citations into your research Markdown document in your project repository, organized by category. Zotero is your source library; the Markdown document is the shareable bibliography.

### C. Research Markdown Document

- Create `docs/research.md` (or similar) in your repository.
- Link it from your README.
- Start with citations generated from Zotero, organized by category (precedent / inspirational / technical; resource if relevant), and expand it as research continues.
- Add brief annotations or findings in the Markdown document, or link to the related Zotero item notes. Do not manually recreate citation metadata that Zotero can generate.

---

## 4) Make It Specific Refinement

Revise the Week 4 worksheet using the [Make It Specific Template](../../documents-Class/04_Detailed_Speculative_Proposal/Make_It_Specific_Template.md). See the [Make It Specific Examples](../../documents-Class/04_Detailed_Speculative_Proposal/Make_It_Specific_Examples.md) for worked examples, including a visual user-experience storyboard and system-flow diagram. The revised worksheet must have no placeholders; rough or unresolved work belongs in the unknowns and planning sections, not as unfilled template prompts.

---

## 5) Miracle Questions / Unknowns

See the archived [Week 5 Miracle Questions reference](archive/05_document_research_specificity_miracle.md#3-miracle-questions--unknowns) for the full definition, required dimensions, and the "Unknown / Why it matters / First test step" structure — this content is unchanged.

---

## Quality Checkpoint (all parts)

Before next class, verify:

- [ ] Every presentation deliverable has at least one Issue, labeled and on the milestone
- [ ] Presentation deck includes the project experience, scope, research, technologies and competencies, roadmap, and specific expert-feedback questions; see the [suggested slide sequence](../../documents-Class/04_Detailed_Speculative_Proposal/02-Presentation_Deliverables.md#suggested-slide-sequence)
- [ ] The board reflects real current status (not everything sitting in Backlog)
- [ ] Your Discussions post names a real, specific unknown
- [ ] README links all resolve (no dead links)
- [ ] PoC / LVP / NSV are each named and distinguishable in the proposal
- [ ] Zotero collection has entries in all three categories, with at least some annotations
- [ ] Zotero-generated bibliography exists in Markdown, is linked from the README, and includes annotations or links to Zotero notes
- [ ] Make It Specific document has no vague placeholders
- [ ] Miracle Questions list covers technical, design/UX, and narrative/content dimensions
