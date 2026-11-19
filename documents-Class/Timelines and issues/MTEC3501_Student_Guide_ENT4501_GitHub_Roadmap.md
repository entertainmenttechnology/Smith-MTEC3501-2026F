# MTEC 3501 Student Guide
## Building your MTEC 3501 roadmap in GitHub

Start in your own GitHub repository. The shared class Project is the walkthrough example. By the end of this activity, you’ll have a draft LVP description and a semester roadmap that shows the major outcomes, the work behind them, and the dependencies that affect their timing.

### 1. Define your LVP and work backward

In your project documentation, write a short description of the Least Viable Product (LVP) you intend to deliver in ENT 4501. Describe the smallest complete version of your project someone can meaningfully use, operate, or experience. Identify who it serves, what it does, and what is outside its scope. Link to evidence from your MTEC 3501 Proof of Concept (PoC) and note what it demonstrated and what you still need to verify.

Start with the ENT 4501 final presentation as your calendar anchor. Use the confirmed date if available. Otherwise, mark it as late semester and note that the date is provisional. Work backward from the outcomes below, adapting them to your project.

| Milestone issue | Evidence of completion |
|---|---|
| LVP functions under intended conditions | A representative user, performer, or operator completes the essential interaction or workflow in a test. |
| User or operator guide verified | Someone follows the relevant instructions to set up, use, operate, or reset the LVP as appropriate. |
| Final presentation rehearsed and ready | A timed rehearsal covers the explanation and demonstrates what the LVP achieves. |

Identify the intermediate outcomes that make these possible. For example, an early end-to-end test gives you time to revise before the LVP and presentation are due. Use your PoC results to decide what to test first. For each milestone, ask **“What will exist or be decided, how will I know it’s complete, and what has to happen first?”**

### 2. Create the milestone issues first

A **milestone issue** is a regular GitHub issue that tracks a major outcome on your roadmap. For example, **LVP works under intended conditions** is a milestone. **Run the end-to-end interaction test** is an issue for work that helps you reach that milestone. Create the milestone issues in this step. In step 5, you’ll create the prerequisite issues and link them to the milestones they support.

1. In your repository, open **Issues → New issue**. If an existing issue already describes the same outcome, edit it.
2. Give the issue a title that describes the outcome, such as **LVP works under intended conditions**.
3. Use the issue body to describe the outcome and its completion evidence. Jot down likely prerequisites and record assumptions that could affect the plan.
4. Submit the issue. Repeat for the other major outcomes. If you want a milestone-only Roadmap view, apply a consistent repository label such as `milestone`.

Copy this structure into an issue body and adapt it:

```markdown
## Outcome
Describe what will exist or be decided.

## Evidence of completion
Describe the test, artifact, or observation that will show the outcome is complete.

## Possible prerequisites
Note any work or decisions that may be needed to reach this milestone.

## Assumptions and risks
Record any major constraints or unresolved questions.
```

### 3. Create a Project from your repository and add issues

1. On the main page of **your repository**, click the **Projects** tab. Click **New project**, select the **Table** layout, enter **ENT 4501 Project** as the name, and click **Create project**. If you already see your ENT 4501 Project in this repository’s **Projects** tab, open it and continue to step 2.
2. In the same repository, click **Issues** and open **LVP works under intended conditions** or the equivalent milestone issue you created.
3. In the issue’s right sidebar, click **Projects** and select your Project. Confirm that the Project name now appears in the issue’s sidebar. If it was already listed on the issue, continue to the next step.
4. Go back to the repository’s **Projects** tab and open the linked Project. Open its **Table** view and find the issue by title or issue number. If the issue is hidden, check the view’s filters.
5. Repeat steps 2–4 for the other milestone issues. Selecting the Project on an issue adds that issue once, and the Table and Roadmap are views of those same Project items.

### 4. Date the milestone issues and verify their Roadmap bars

1. Open the linked Project and select its **Table** view. Look for two date columns you can use as **Start** and **Target**. If you need to create them, scroll to the far-right table header and click **+ → New field**. Name the field **Start**, select the **Date** type, and click **Save**. Repeat for **Target**.
2. In the Table, find the row for **LVP works under intended conditions**. Click its cell under **Start** and choose the day work toward that outcome can begin. On the **same row**, click its cell under **Target** and choose the day you expect to have the evidence that the LVP works. If the calendar is still being finalized, use provisional dates and record that assumption in the issue.
3. Open your existing Roadmap view if you have one. Otherwise, click **+ New view** in the same Project, choose **View → Layout → Roadmap**, name it **ENT 4501 Roadmap**, and save the view changes.
4. In the Roadmap, click **Date fields** in the upper right. Set **Start date** to your **Start** field and **Target date** to your **Target** field.
5. Find **LVP works under intended conditions** on the Roadmap. Its bar should span the two dates you entered. If the issue is missing, check that it appears in the Project’s Table and that the Roadmap filter includes it. If the issue is listed but you cannot see the bar, check both date cells and the date-field mapping, then scroll to the relevant month or use **Quarter** zoom.
6. Enter dates on the remaining issue rows and check their bars. If you labeled your milestone issues, you can use `label:milestone` to show only those issues in the Roadmap. Confirm that the final rehearsal comes before the presentation. Once the milestone bars are visible, use them to plan the prerequisite work in step 5.

GitHub also has a repository feature called **Milestones**, which groups issues around a shared target date. For this activity, your milestone outcomes are dated **issues** in the Project. If your repository already uses a GitHub Milestone for the final presentation, you can display its due date as a vertical marker via **Markers** on the Roadmap when that milestone is associated with a Project item.

### 5. Create prerequisite issues and link dependencies

1. Start with a milestone already on the Roadmap, such as **LVP works under intended conditions**. Read its completion criteria and identify concrete work that has to be done to meet them. For example, someone has to run the end-to-end interaction test before you can verify the LVP.
2. Go to your repository’s **Issues** tab and click **New issue**. Enter **Run the end-to-end interaction test** as the title. In the body, describe how the issue will be completed, such as running the full interaction and posting the test results. Submit the issue and note its number. If an existing issue already tracks that work, use it.
3. If you want to schedule this work in your Project, open the new issue, click **Projects** in its sidebar, and select your Project. Set its dates in the Table as you did for the milestone. If you use a milestone-only Roadmap filter, the prerequisite issue will still be available through the milestone’s relationship links.
4. Open the **milestone issue** that needs the work, **LVP works under intended conditions**. In the right sidebar, select **Relationships → Mark as blocked by**. Search by title or issue number and select **Run the end-to-end interaction test**.
5. Verify the direction. The milestone should list the test issue under **Blocked by**. The test issue should list the milestone under **Blocking**. Repeat for other prerequisites. Where one milestone truly depends on another, use the same steps to link those two milestone issues.
6. Return to the Table or Roadmap and check that each prerequisite is scheduled to finish before the point at which the downstream work needs it. If a date slips, review the dependent issues and adjust their dates manually.

Use a checklist for small actions you want to record inside a milestone. Use a separate issue for a prerequisite you want to track and link through **Relationships**.

### 6. Review your draft with a partner

Ask your partner to trace one essential LVP capability to a roadmap issue. Can they tell what will exist, what evidence shows it is complete, and what work must come first? Record one change you’ll make based on their feedback. Leave the LVP description discoverable from your README and save the roadmap in your repository’s Project.

### GitHub reference

- [Linking an existing Project to a repository](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-your-project/adding-your-project-to-a-repository)
- [Adding issues to an existing Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/managing-items-in-your-project/adding-items-to-your-project)
- [Adding sub-issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/adding-sub-issues)
- [Creating issue dependencies](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/creating-issue-dependencies)
- [Customizing the Roadmap layout](https://docs.github.com/en/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/customizing-the-roadmap-layout)
