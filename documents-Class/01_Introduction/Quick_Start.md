# Quick Start — Onboarding & Git Workflow

This document lists the core applications and account connections used in MTEC 3501. Complete the startup sequence before beginning project work, then use the GitHub workflow to maintain your individual project repository.

Applications used in this course

- GitHub — repository hosting, Issues, Pull Requests, Projects (required)
- Git (command-line) or GitHub Desktop — clone, branch, commit, push (one is required; Desktop recommended for beginners)
- Visual Studio Code — primary code and text editor (recommended)
- Zotero + Zotero Connector — citation management and research collection
- Browser (Chrome, Firefox, Safari) — for GitHub, Zotero Connector, and web tools
- Optional/Project tools: Figma, Adobe XD, Blender, Unity, Unreal Engine, Python/Node.js runtimes — installed per project needs

## Startup Sequence

Complete these steps in order:

1. Create or confirm a GitHub account. Use an identifiable username containing your last name and at least the initial of your first name, and replace the default GitHub avatar with a recognizable, professional avatar.
2. Create or confirm a Zotero account, install Zotero Desktop and Zotero Connector, and sign in to sync them.
3. Accept the instructor's invitation to the MTEC 3501 Zotero group library. Locate the shared class-materials collection and create your own collection for project research.
4. Create or confirm a professional Google account and confirm access to the current course Google Drive and shared documents.
5. Join the current MTEC 3501 Discord server. Set your course server nickname so classmates and instructors can identify you, and enable notifications for important channels. Discord is for informal communication; official instructions and deadlines remain in the class repository and syllabus.
6. Read the current semester syllabus: [`Syllabus_MTEC3501.md`](../Syllabus_MTEC3501.md). Also review the current semester configuration, assignments, schedule, Discord instructions, Google materials, and Zotero access information.
7. Create your individual project repository from the [MTEC3501 Student Project Repository Template](https://github.com/entertainmenttechnology/MTEC3501-Student-Template), choosing your own personal GitHub account as the repository owner. Do not create it under the course organization unless the instructor gives different instructions.
8. Complete the project metadata in the new repository's root README, then create its first GitHub Project and initial Issues for the work ahead.
9. Install project-specific software or hardware as your project requires. Record those requirements in your project documentation.

The Week 1 onboarding assignment provides the submission checklist and account-identification requirements.

## Accounts & Tools

Before you begin, create or confirm the following accounts and install the recommended tools. These are the core applications used in this course.

- GitHub account: https://github.com/join (used for repository hosting, Issues, Projects, and version control)
- Git (command-line) or GitHub Desktop: https://desktop.github.com/ (Desktop recommended for beginners)
- Visual Studio Code (editor): https://code.visualstudio.com/
- Zotero account and Zotero Connector: https://www.zotero.org/download/ (Zotero desktop app is optional but recommended for full features)
- Web browser (Chrome, Firefox, or Safari) with cookie/logins enabled for GitHub and Zotero
- GitHub Projects / Issues (built into GitHub) — for task tracking and project planning

Optional / course-dependent tools (examples):

- Figma or Adobe XD (UI/UX and prototyping)
- Blender, Unity, or Unreal Engine (3D/interactive prototypes)
- Python / Node.js runtimes for lightweight prototyping (install as needed per project)

Notes:

- If you are new to Git, GitHub Desktop simplifies cloning, branching, committing, and PR creation. The CLI provides finer control and is recommended for students comfortable with the terminal.
- Zotero lets you collect citations and export bibliographies for precedent research.
- We will provide project-specific tooling notes in assignment prompts when needed.


## Individual Student Repository Workflow

Your individual repository is the primary workspace for your research, design, prototype, documentation, and project history. The class repository remains the authoritative source for course materials and assignments.

1. Create your repository from the [MTEC3501 Student Project Repository Template](https://github.com/entertainmenttechnology/MTEC3501-Student-Template) in your own GitHub account. Choose a clear repository name that identifies the project.

```bash
git clone git@github.com:your-username/your-project-repository.git
cd your-project-repository
```

2. Complete the root README metadata and confirm that the expected folders and Issue templates are present.

3. Commit regularly with messages that describe the change. Push completed work to your personal repository:

```bash
git add .
git commit -m "Describe the project change"
git push origin main
```

4. Use branches and Pull Requests when they help you isolate experiments, review changes, or collaborate. Branch names should describe their purpose, such as `experiment/sensor-test`, `docs/lvp-design`, or `feature/interaction-model`.

5. Link project Issues to your GitHub Project and milestones. Keep completed work, decisions, testing results, and revisions visible in the repository history.

## Class Repository Workflow

The class repository is for course materials, assignments, shared activities, and class resources. Do not place your individual project work there unless a specific assignment instructs you to submit or transfer an artifact.

## Pull Request Checklist

Use this checklist when a Pull Request is useful in your individual repository:

- Title: concise summary of changes
- Link to Week/Assignment issue
- Files changed: identify the relevant project path
- Description: what you added/changed and why
- AI use: disclose any AI assistance (prompts, tools, edits)
- Tests/Notes: how to preview or run any demos

If you prefer GitHub Desktop for onboarding, follow the steps in the course `README.md` under "Getting Started".

---

