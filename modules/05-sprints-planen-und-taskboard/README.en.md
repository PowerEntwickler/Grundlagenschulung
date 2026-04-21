# Module 05 - Planning Sprints and Using the Sprint Backlog

## Goal of this module
In this module, participants learn how to work with sprints and sprint backlogs in Azure DevOps Services. After the lab, they will be able to:

1. create **three sprints** in the project configuration
2. group the sprints under their own **team name**
3. assign those sprints to their team
4. assign existing work items to a sprint
5. add **tasks** to items in the **Sprint Backlog**
6. maintain **Remaining Work** for those tasks

## Scenario
After structuring the backlogs, queries, and Kanban board, the next project-management step is now practiced: planning work in time-boxed sprints.

Each person creates a clean sprint structure for their own team, plans existing work items into those sprints, and breaks the sprint work down into concrete tasks in the sprint backlog.

## Prerequisites
- Module 01 to Module 04 have been completed
- You have your own team named with your **first name**
- Several work items already exist in your team context
- Access to the Azure DevOps Services organization **tuvsud10**
- The menu labels are primarily **in English**

## Important note
In this module, you work with **Iteration Paths**. They are different from **Area Paths**:

- **Area Path** = which team or functional area owns the work item
- **Iteration Path** = in which sprint or time period it should be worked on

## Fixed sprint dates for this training
Use the following sprint dates in this module:

1. **Sprint 1:** 2026-04-20 to 2026-05-01
2. **Sprint 2:** 2026-05-04 to 2026-05-15
3. **Sprint 3:** 2026-05-18 to 2026-05-29

---

## Exercise 1 - Create the sprint structure in the project configuration

### Goal
Create three sprints under your own team name.

### Steps
1. Sign in to **tuvsud10** and open the project assigned to your pair.
2. Click **Project settings** in the lower left corner.
3. Open **Project configuration** or **Iterations**, depending on the menu that is visible.
4. First create a parent entry with your team name, meaning your **first name**, for example:
   `Maria`
5. Under that entry, create three child sprints:
   - `Sprint 1`
   - `Sprint 2`
   - `Sprint 3`
6. Enter the fixed dates for the three sprints:
   - **Sprint 1:** Start `2026-04-20`, End `2026-05-01`
   - **Sprint 2:** Start `2026-05-04`, End `2026-05-15`
   - **Sprint 3:** Start `2026-05-18`, End `2026-05-29`
7. Save the configuration.

### Expected result
Under your team name, there is now a clear sprint structure with three time-boxed sprints.

---

## Exercise 2 - Assign the sprints to your team

### Goal
Make the created sprints available for your team.

### Steps
1. Leave **Project settings** and return to the **Boards** area.
2. Open **Boards > Backlogs**.
3. Use the **team selector** to choose your own team named with your first name.
4. Open **Team configuration** under **Boards**.
5. Switch there to **Iterations**.
6. Add the three sprint paths you just created for your team, for example:
   - `Maria\\Sprint 1`
   - `Maria\\Sprint 2`
   - `Maria\\Sprint 3`
7. Save the selection if Azure DevOps requires it.
8. Verify that the sprints are now assigned to your team.

### Expected result
Your team can now work with its own sprints in **Boards > Sprints**.

---

## Exercise 3 - Assign work items to the sprints

### Goal
Plan existing work items into concrete timeboxes.

### Steps
1. Go to **Boards > Backlogs**.
2. Open the **Planning** panel on the right side if it is not already visible.
3. Find your own work items using your first name or your user prefix from earlier modules.
4. Drag suitable work items through the **Planning** panel into one of the new sprints.
5. Assign some items to **Sprint 1**, some to **Sprint 2**, and some to **Sprint 3**.
6. Spot-check one work item to verify that the **Iteration Path** was set correctly.

### Expected result
Your work items are now distributed across several sprints and scheduled over time.

---

## Exercise 4 - Open the Sprint Backlog

### Goal
Switch from the general backlog view into sprint-based planning.

### Steps
1. Go to **Boards > Sprints**.
2. Use the **team selector** to choose your own team.
3. Open **Sprint 1** in the sprint navigation.
4. Check whether the work items that you assigned through the **Iteration Path** are now visible there.
5. If items are missing, verify their **Iteration Path** again.

### Expected result
You now see the sprint backlog of your team for the selected sprint.

---

## Exercise 5 - Add tasks to sprint items

### Goal
Break a sprint item down into concrete work steps.

### Steps
1. Stay in **Boards > Sprints** inside **Sprint 1**.
2. Find a Product Backlog Item that you already planned into this sprint.
3. Use the function below that item to add a new child task, for example **+** or **Add Task**.
4. Use the work item type **Task**.
5. Create at least two tasks for one work item, for example:
   - `Draft agenda`
   - `Align participants`
6. Repeat this for at least one other work item in the sprint.

### Expected result
At least two sprint items have now been broken down into smaller, concrete tasks.

---

## Exercise 6 - Set Remaining Work

### Goal
Maintain the estimated remaining effort for the sprint tasks.

### Steps
1. Open one of the newly created tasks.
2. Find the **Remaining Work** field.
3. Enter a meaningful effort value, for example:
   - `2`
   - `4`
   - `6`
4. Save the task.
5. Repeat this for the other tasks in your sprint backlog.
6. If useful, switch to the **Taskboard** afterward so you can view the tasks and their effort in the sprint context.

### Expected result
The tasks in the sprint now contain specific **Remaining Work** values and can be planned and tracked more effectively.

---

## Typical pitfalls

- If the **Planning** panel is not visible, verify that you are really working in **Boards > Backlogs**.
- If a sprint backlog stays empty, the **Iteration Path** on the work items is usually not set correctly yet.
- **Remaining Work** is most useful on **Task** level and should be maintained there for sprint planning.

---

## Final check
By the end of this module, you should have:

1. three sprints under your own **team name**
2. those sprints assigned to your team
3. multiple work items distributed across the sprints through the **Iteration Path**
4. new **tasks** created in the **Sprint Backlog**
5. **Remaining Work** values maintained for those tasks

If these points are visible, you have successfully completed the basics of sprint planning, sprint backlog usage, and effort tracking in Azure DevOps.
