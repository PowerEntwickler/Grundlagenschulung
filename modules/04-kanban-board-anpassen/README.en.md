# Module 04 - Customizing the Kanban Board

## Goal of this module
In this module, participants learn how to configure their own Kanban board in Azure DevOps Services in a meaningful way. After the lab, they will be able to:

1. open and customize their own team board
2. create or rename **columns**
3. use **swimlanes** for different priorities or work types
4. set and interpret a **WIP limit**
5. add a **Definition of Done** for individual columns
6. split a column into **Doing** and **Done**
7. improve visibility with **styles** and **tag colors**

## Scenario
After the import and first evaluation in Module 03, the team now has a larger set of work items available. To manage them better in day-to-day work, the team board itself is now configured.

The goal is not just a nicer view, but a board that actually supports the project-management workflow.

## Prerequisites
- Module 01 to Module 03 have been completed
- You have your own team named with your **first name**
- Several Product Backlog Items are already visible in your team backlog and team board
- Access to the Azure DevOps Services organization **tuvsud10**
- The menu labels are primarily **in English**

## Collaboration note
Even though two participants share one project, each person should work on **their own team board** in this module. That keeps the changes as separate as possible.

## Compact best practices for this module

- Use only as many **columns** as you really need so the board stays readable.
- Keep additional **swimlanes** limited to one or two where possible.
- Set **WIP limits** deliberately low and realistic.
- Keep the **Definition of Done** short, concrete, and easy to verify.
- Use **styles** and **tag colors** sparingly so the board does not become visually noisy.

---

## Exercise 1 - Open your own team board

### Goal
Open the board that belongs to your own team.

### Steps
1. Sign in to **tuvsud10**.
2. Open the project assigned to your participant pair.
3. Go to **Boards > Boards**.
4. Use the **team selector** in the upper left area and choose your own team named with your first name.
5. Check that the displayed work items belong to your team through the configured **Area Path**.
6. Briefly review the existing board columns.

### Expected result
You are now working on the Kanban board of your own team and can customize its configuration.

---

## Exercise 2 - Create or adjust your own columns

### Goal
Learn how a board can be adapted to the actual workflow of the team.

### Steps
1. Stay on **Boards > Boards**.
2. Open the **Board settings** in the upper right area.
3. Switch to **Columns**.
4. Review the existing default columns, such as **New**, **Approved**, **Committed**, or similar names.
5. If useful, rename one column so it fits the training context better.
6. Add at least one extra custom column, for example:
   - `In Review`
   - or `Waiting`
7. Save the change.
8. Return to the board and check that the new or updated column structure is visible.

### Expected result
The board now contains columns that better reflect your workflow.

---

## Exercise 3 - Split a column into Doing and Done

### Goal
Learn an important way to make progress inside one phase more visible.

### Steps
1. Open the **Board settings** again.
2. Go to **Columns**.
3. Select a suitable working column, such as **Committed** or **In Review**.
4. Enable the option to split that column into **Doing** and **Done**.
5. Save the change.
6. Return to the board.
7. Observe that the selected column is now split into two parts.

### Expected result
You can now distinguish more clearly between items still in progress and items already completed within that phase.

---

## Exercise 4 - Create swimlanes

### Goal
Add another layer of structure to the board based on urgency or work type.

### Steps
1. Open the **Board settings**.
2. Switch to **Swimlanes**.
3. Review the existing swimlanes.
4. Add at least one new swimlane, for example:
   - `Urgent`
   - `Standard`
   - or `Management Attention`
5. Save the change.
6. Return to the board.
7. As a test, move one or two work items into another swimlane.

### Expected result
The board is now additionally structured in horizontal lanes that make differences in priority more visible.

---

## Exercise 5 - Set a WIP limit

### Goal
Learn how to make work in progress visibly limited.

### Steps
1. Open **Board settings** again and go to **Columns**.
2. Select a column where several active items could appear, such as **Committed** or **In Review**.
3. Enter a small **WIP limit**, for example `2` or `3`.
4. Save the setting.
5. Return to the board and observe how the WIP limit is shown in that column.
6. Think briefly about what it means if the limit is exceeded.

### Expected result
You understand that a WIP limit helps make too much parallel work visible and easier to manage.

---

## Exercise 6 - Add a Definition of Done

### Goal
Make transparent when a work step should really count as completed.

### Steps
1. Stay in **Board settings** within **Columns**.
2. Select a suitable column, such as a later work phase or the **Done** part of a split column.
3. Add a short **Definition of Done**, for example:
   - `Description updated`
   - `Responsibility clarified`
   - `Result documented`
   - `Next step known`
4. Save the setting.
5. Check whether the definition can now be easily found by the team.

### Expected result
At least one board column now has a clear definition of when an item is actually complete in that phase.

---

## Exercise 7 - Use styles and tag colors

### Goal
Improve how important information stands out on the board.

### Steps
1. Open the **Board settings**.
2. Switch to **Styles**.
3. Create at least one rule that visually highlights work items with a specific **tag**, for example:
   - `communication`
   - `reporting`
   - `risk`
4. Choose a clearly visible background or text color for that rule.
5. Save the setting and return to the board.
6. Check whether work items with that tag are now highlighted.
7. If **Tag colors** can be configured separately in your project, also assign different colors to important tags.

### Expected result
Important categories or topics can now be recognized much faster on the board.

---

## Typical pitfalls

- If the board looks different from expected, first check the **team selector**.
- If no highlighting appears, verify that the affected work items really contain the matching **tag**.
- Too many new columns or swimlanes quickly make the board harder to use. In most cases, simpler is better.

---

## Final check
By the end of this module, you should have:

1. a **Kanban board** tailored to your team
2. adjusted or newly added **columns**
3. at least one split column with **Doing** and **Done**
4. at least one extra **swimlane**
5. a visible **WIP limit**
6. a defined **Definition of Done**
7. visible highlighting through **styles** or **tag colors**

If these points are visible, you have successfully completed the most important basics of practical Kanban board usage in Azure DevOps.
