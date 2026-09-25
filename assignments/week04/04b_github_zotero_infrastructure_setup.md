# MTEC 3501 – Week 4 Technical Assignment
## GitHub & Zotero Infrastructure Setup

---

## Purpose

This is the mechanical companion to [Make It Specific](04a_assignment_make_it_specific.md). Where that document sharpens the project idea itself, this one covers the project **infrastructure** demonstrated live in the 9/24 class session — the GitHub and Zotero setup every project now needs. If you missed class (see the [session summary](../../documents-Class/Session_Notes/2026-09-24_Zoom_session_summary.md) for the full recap), work through this document to catch up.

**Note on repository structure:** Each student has their own individual repository this semester (created from the MTEC 3501 Student Project Repository Template), not a shared class repository.

---

## 1) GitHub Issues

- Create an Issue for each presentation deliverable and research task (e.g., precedent research, technical research, documentation).
- Apply a label describing the type of work, using the numbered SRDMPA-stage format (e.g., `02_research-precedent`, `02_research-technical`, `03_design`). These labels don't exist in your repository yet — create them yourself under **Issues → Labels → New label** (future semesters will have them pre-loaded in the template).
- Large deliverables (e.g., the slide deck) can be broken into **sub-issues** — for example, a "Slide Deck" parent issue with sub-issues for introduction, research & precedents, and project breakdown.

## 2) GitHub Kanban Project Board

- Create a Project Board (Projects tab → Board template) if you don't already have one.
- Set up columns for workflow stages: **Backlog, Ready, In Progress, In Review, Done**.
- Add your Issues to the board and place them in the correct column.

## 3) Repository Organization

- Keep source files in a `/src` directory.
- Add a `.gitignore` appropriate to your project — this matters especially for **Unity** or other large-asset workflows, so build artifacts and large binaries aren't pushed to the cloud repository.

## 4) Zotero

- Create your personal Zotero sub-collection under the class **Students** folder.
- Organize research by type: **inspirational**, **precedent**, **technical** (a fourth type, **resource** research — ethically usable assets/materials — is also part of the overall research model).
- Use the Zotero browser connector to save sources directly into your collection.
- Add item notes (annotations) to record findings and follow-up questions.
- You can generate a bibliography directly from Zotero (e.g., APA format) and paste it into Google Docs or your repository.

## 5) Project Scope Preview

Presentations will define three scope levels for your project: **North Star Vision**, **Least Viable Product**, and **Proof of Concept**. You'll formally write these into your proposal in Week 5 — for now, just be aware this is coming.

---

## Deliverable Checklist

- [ ] Issues created for each presentation deliverable/research task, labeled by type
- [ ] Sub-issues created for at least one large deliverable
- [ ] Kanban board created with Backlog / Ready / In Progress / In Review / Done columns
- [ ] `/src` directory and an appropriate `.gitignore` in place
- [ ] Zotero sub-collection created under Students, with entries begun in at least one category
