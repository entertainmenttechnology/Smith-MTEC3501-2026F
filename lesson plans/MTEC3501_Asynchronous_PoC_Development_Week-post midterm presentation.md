# MTEC 3501 — Asynchronous Learning Activities and PoC Development Assignment

**Format:** Independent asynchronous work; materials released at the beginning of the scheduled class period  
**Next meeting:** Progress discussion at the following synchronous class  
**Project horizon:** From this week through the final PoC presentation at the end of the semester

## Purpose

You have presented your Culmination Project proposal, received oral feedback, and have had a week to consider how to modify and strengthen your proposal. This week you will continue that process, receive the written feedback from the panelists, review formative feedback on your GitHub repository, establish or refine your technology stack, and **begin practical development of your Proof of Concept (PoC)**.

The PoC is the target you will develop toward by the end of the semester and present at your final presentation. For this course, the PoC is a focused demonstration that tests important parts of your project's creative and technical approach and shows your readiness to continue developing the LVP in ENT 4501. It is not the LVP itself.

## Part I — Guided asynchronous learning activities

The following activities guide your independent work. They are **not timed exercises** and do not require you to be online or working at a particular moment during the scheduled class period. You may revisit them or adjust their order to suit your project, but make sure to complete these tasks by the Week 9 class.

### 1. Reconsider feedback and your PoC

Based on oral and written feedback, and considering the changes you have already made since presenting, review the repository feedback as well. Identify observations that affect your scope, research, technical approach, or documentation. Decide which suggestions to adopt, adapt, investigate, or decline, and why.

Clarify what your PoC needs to demonstrate and distinguish its essential capabilities from features that belong to the longer-term project. Refer to the Week 5 [assignment section defining the three scope levels](../assignments/week05/05_assignment_week05.md#part-2--define-your-three-scope-levels) and its [scope-level reference guide](../assignments/week05/05_document_week05_reference.md#2-scope-levels-poc--lvp--nsv).

### 2. Examine and improve your repository

Use the repository feedback to identify components that are already appropriate, those that need development, and those not yet present. Correct straightforward problems, update the README and navigation as needed, and identify more substantial work for your action plan.

Your GitHub repository is the **source of truth** for your project. If something is not documented or linked in the repository, it does not exist as part of the project record. Make clear which project materials are stored in the repository and which are hosted elsewhere, such as in Google Docs. External work is acceptable when the repository explicitly links to it and the link is accessible. Structure and maintain the repository according to the formats and guidelines established for this course.

#### Expected project materials and locations

Use the folders provided by the student repository template and the locations specified in course materials. Keep the root directory uncluttered: the root `README.md` is the project index, not a container for the entire project or a substitute for organized files.

| Project material | Expected location or record |
|---|---|
| Project overview and navigation | Root `README.md`, with links to the materials below |
| Make It Specific document | `docs/01_speculation/02_Make_It_Specific.md`, following the [course template](../documents-Class/04_Detailed_Speculative_Proposal/Make_It_Specific_Template.md) |
| Proposal and PoC / LVP / North Star Vision definitions | In the proposal document, in the course-template location or another clearly organized project-documents location; link it from the README |
| Research summary / shareable bibliography | A Markdown document in `docs/` (for example, `docs/research.md`), linked from the README |
| Zotero sources and collection | In the student's Zotero collection; link the collection from the README and connect relevant research to the repository's research document |
| Design documentation, technology choices, and diagrams | In the course-template's documentation structure or organized under `docs/`; store diagrams with related documentation or in an appropriate assets folder and link them |
| PoC implementation and practical-trial evidence | Working source in `/src`; place test notes in the relevant development documentation and supporting media in an appropriate assets folder |
| Feedback decisions and development record | In the relevant proposal, design document, or development log; link external documents from the README |
| Action plan and actionable work | GitHub Issues and the Project board, linked or made easy to find from the README |

The table identifies expected content and sensible locations, not a requirement to create duplicate documents or empty folders. Follow any more specific location already set by the student template or an assignment. Keep substantive materials in their appropriate files and folders; make each item findable through the README or the relevant project document. For externally hosted work, label it as external, link it explicitly, and check that the link is accessible.

The instructor's 2–1–0 indicators are **formative descriptions**, not a score or grade: 2 = meets current expectations; 1 = exists but needs improvement; 0 = absent, even in preliminary form.

### 3. Specify the technology stack and its relationships

For each hardware, software, material, tool, and production process needed for your PoC, make and document a current choice or working assumption. State whether it is available and tested, selected but not yet verified, or a provisional choice. If you are choosing among alternatives, name your preferred current option and explain what evidence could confirm or change that choice. Your decisions may change as research and practical work provide new information; record significant changes and why you made them. Consider how the components interact; a simple signal-flow, system, or production-workflow diagram may help.

Be specific: do not write only “a programming language” or “a game engine.” Name the currently proposed component, including the platforms you will use to develop and deploy your PoC.

Identify important dependencies and the technical or creative unknowns most likely to impede progress. It is critical that we are able to label where the "magical thinking" lies.

### 4. Begin using the components of your PoC

**Do practical work, not only planning.** Select a feasible starting activity using a real component, tool, material, or workflow required by your PoC. Examples include installing and configuring software, acquiring and manipulating sample media, establishing a signal path, testing a sensor, creating a simple interaction, or trying a basic integration.

The initial attempt need not succeed. What matters is that it is relevant to the PoC and that you learn something concrete from it. Record what you attempted, what happened, what you learned, and what you intend to try next. Retain evidence when appropriate, such as code, screenshots, photos, audio, video, or test notes.

### 5. Organize the path to the final PoC

Develop or revise an action plan covering the work through your final PoC presentation. Identify meaningful tasks, dependencies, milestones, resources, critical unknowns, and time for testing, revision, documentation, and final presentation preparation.

Use the GitHub Issues workflow introduced in the Week 4 [GitHub & Zotero Infrastructure Setup assignment](../assignments/week04/04b_github_zotero_infrastructure_setup.md) and demonstrated in the [September 24 class session](../documents-Class/Session_Notes/2026-09-24_Zoom_session_summary.md): review existing Issues, update them, and create new Issues for actionable work as appropriate. Issues should help manage the plan, not merely duplicate its text.

## Part II — Assignment: Work to advance before our next meeting

Complete the work initiated through the guided activities. Before the Week 9 class, your repository should reflect meaningful progress in these areas:

1. **Respond to presentation feedback:** Record which oral or written feedback you will adopt, adapt, investigate, or decline, and why.
2. **Review and update your repository:** Address manageable deficiencies and identify remaining corrections. Make clear which project materials are stored in the repository and which are externally hosted; ensure external materials are explicitly linked and accessible. Keep the repository structure and materials consistent with the formats and guidelines established for this course.
3. **Define the PoC and technology stack:** State what the PoC will demonstrate and document a current choice or working assumption for each required component and process, including development and deployment platforms. Identify dependencies and mark choices that are provisional or not yet verified.
4. **Begin practical development:** Work hands-on with at least one essential component or process. Document your attempt and its results; a functioning PoC is **not** required.
5. **Plan the remaining work:** Establish or update the roadmap through your final PoC presentation, including dependencies, and use GitHub Issues to organize actionable next steps.

All assignment components must be represented in your project repository. Use existing repository documents and your development log where possible; do not create separate submissions merely to repeat the same information. Work may be created or stored in other resources (such as Google Docs), but the repository must explicitly link to each external document or resource so it is discoverable as part of your project record. Continue independent project work as appropriate to your particular PoC.

## Part III — Preparations for next class

Be prepared to report briefly, using your repository and any available development evidence:

- **What changed?** Which feedback influenced your decisions or documentation?
- **What did you do?** What actual work did you begin on your PoC?
- **What did you discover?** What worked, failed, or remains uncertain about the technology stack or workflow?
- **What comes next?** Which tasks, dependencies, and GitHub Issues will guide your immediate work?

This is a progress report and discussion, **not the PoC deadline**.

---
