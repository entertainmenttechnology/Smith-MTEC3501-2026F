# MTEC 3501 Student Guide
## Building your ENT 4501 roadmap in GitHub

Use your existing repository and GitHub Project. The shared class Project is the walkthrough example. By the end of this activity, you’ll have a draft LVP description and a semester roadmap that shows the major outcomes, the work behind them, and the dependencies that affect their timing.

### 1. Define your LVP and work backward

In your project documentation, write a short description of the Least Viable Product (LVP) you intend to deliver in ENT 4501. Describe the smallest complete version of your project someone can meaningfully use, operate, or experience. Identify who it serves, what it does, and what is outside its scope. Link to evidence from your MTEC 3501 Proof of Concept (PoC) and note what it demonstrated and what you still need to verify.

Start with the ENT 4501 final presentation as your calendar anchor. Use the confirmed date if available. Otherwise, mark it as late semester and note that the date is provisional. Work backward from the outcomes below, adapting them to your project.

| Milestone issue | Evidence of completion |
|---|---|
| LVP functions under intended conditions | A representative user, performer, or operator completes the essential interaction or workflow in a test. |
| User or operator guide verified | Someone follows the relevant instructions to set up, use, operate, or reset the LVP as appropriate. |
| Final presentation rehearsed and ready | A timed rehearsal covers the explanation and demonstrates what the LVP achieves. |

Identify the intermediate outcomes that make these possible. For example, an early end-to-end test gives you time to revise before the LVP and presentation are due. Use your PoC results to decide what to test first. For each milestone, ask **“What will exist or be decided, how will I know it’s complete, and what has to happen first?”**

### 2. Create or revise the milestone issues

1. In your repository, open **Issues → New issue**. If an existing issue already describes the same outcome, edit it.
2. Give the issue a title that describes the outcome, such as **LVP works under intended conditions**.
3. Use the issue body to describe the outcome and its completion evidence. List the work, decisions, resources, or access needed to get there. Record assumptions that could affect the plan.
4. Submit the issue. Repeat for the other major outcomes. If you want a milestone-only Roadmap view, apply a consistent repository label such as `milestone`.

Copy this structure into an issue body and adapt it:

```markdown
## Outcome
Describe what will exist or be decided.

## Evidence of completion
Describe the test, artifact, or observation that will show the outcome is complete.

## Work needed
- [ ] Add a concrete action.

## Assumptions and risks
Record any major constraints or unresolved questions.
```

### 3. Add the issues to your existing Project

1. Open a milestone issue and select **Projects** in its right sidebar.
2. Select your existing Project. Repeat for the other milestone issues.
3. Open your Project and verify that the issues appear in its **Table** view. Clear or adjust the view filter if it hides the issues.

### 4. Add supporting work and link dependencies

1. Keep short steps in the parent issue’s checklist. For work you want to track individually, open the parent issue and choose **Add sub-issue**. Create a new issue or use the dropdown to add an existing one. For example, add **Run the end-to-end interaction test** beneath **LVP works under intended conditions**.
2. Open the issue that needs a prerequisite. In the sidebar, choose **Relationships → Mark as blocked by**, then select the prerequisite issue. For example, open **Final presentation rehearsed and ready** and select **LVP works under intended conditions** if the final rehearsal requires the functioning LVP.
3. Open both issues and check the direction. The presentation issue should show the LVP issue under **Blocked by**. Drafting slides or writing the first version of the guide can still begin while the LVP is in development.

### 5. Put dates on the Roadmap

1. Open the Project’s **Table** view. Reuse suitable date fields or scroll to the rightmost column and choose **+ → New field**. Select the **Date** field type and create **Start** and **Target**.
2. Enter a **Start** date for when work toward the milestone can begin and a **Target** date for when you expect the completion evidence. Use provisional dates to represent early-, middle-, and late-semester windows if the calendar is still being finalized.
3. In the same Project, select **+ New view**. Open **View → Layout → Roadmap**, name the view **ENT 4501 Roadmap**, and save the view changes.
4. In the Roadmap, open **Date fields**. Map **Start date** to **Start** and **Target date** to **Target**. Use **Month** or **Quarter** zoom to inspect the schedule. If you labeled your milestone issues, you can filter the view with `label:milestone`.
5. Check that your final rehearsal is scheduled before the presentation and that prerequisite outcomes arrive before the work that needs them. If a milestone slips, review downstream issues and adjust their dates where needed. Dependency links record the relationship. Date changes are manual.

GitHub also has a repository feature called **Milestones**, which groups issues around a shared target date. For this activity, your milestone outcomes are dated **issues** in the Project. If your repository already uses a GitHub Milestone for the final presentation, you can display its due date as a vertical marker via **Markers** on the Roadmap when that milestone is associated with a Project item.

### 6. Review your draft with a partner

Ask your partner to trace one essential LVP capability to a roadmap issue. Can they tell what will exist, what evidence shows it is complete, and what work must come first? Record one change you’ll make based on their feedback. Leave the LVP description discoverable from your README and save the roadmap in your existing Project.

### GitHub reference

- [Adding issues to an existing Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-items-in-your-project/adding-items-to-your-project)
- [Adding sub-issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/adding-sub-issues)
- [Creating issue dependencies](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/creating-issue-dependencies)
- [Customizing the Roadmap layout](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/customizing-the-roadmap-layout)
