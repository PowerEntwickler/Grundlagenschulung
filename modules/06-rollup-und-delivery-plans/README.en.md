# Module 06 - Rollup Columns and Delivery Plans

## Goal of this module
In this module, participants learn how to make progress and time-based planning visible at a higher level in Azure DevOps Services. After the lab, they will be able to:

1. make hierarchy visible in the **Backlog** view
2. use **Rollup Columns** to display progress and totals
3. understand how **Epic**, **Feature**, and **Product Backlog Item** work together
4. create a **Delivery Plan**
5. visually understand timelines and planned work

## Scenario
In the previous modules, many individual work items were created, structured, imported, and planned into sprints. Now the focus shifts to making that information visible for project management and steering.

This module therefore introduces two especially useful features:

- **Rollup Columns** for progress and hierarchy in the backlog view
- **Delivery Plans** for timeline-based visualization of planned work

## Prerequisites
- Module 01 to Module 05 have been completed
- **Epics**, **Features**, **Product Backlog Items**, **Sprints**, and **Tasks** already exist
- Access to the Azure DevOps Services organization **tuvsud10**
- The menu labels are primarily **in English**

---

## Exercise 1 - Make the hierarchy visible in the backlog

### Goal
Prepare the backlog view so that the relationships between levels become easier to see.

### Steps
1. Go to **Boards > Backlogs**.
2. Use the **team selector** to choose your own team.
3. Make sure you are working in a view where **Epics**, **Features**, and **Product Backlog Items** are used in a meaningful way.
4. Open **View options** or the backlog display options if needed.
5. Enable the setting that shows **parents**, child levels, or hierarchy information.
6. Expand a few items so you can see the existing structure more clearly.

### Expected result
You can now see how the higher and lower planning levels are connected in the backlog view.

---

## Exercise 2 - Add rollup columns

### Goal
Extend the backlog view with automatic progress and summary information.

### Steps
1. Stay in **Boards > Backlogs**.
2. Open **Column options** or the function used to customize the visible columns.
3. Choose **Add rollup column**.
4. Add at least one or more **Rollup Columns**.
5. Try meaningful values such as:
   - number of child items
   - progress of completed work
   - totals for effort or remaining work, if available in your view
6. Arrange the new columns so they are easy to read.
7. Save or apply the changes.

### Expected result
The backlog view now shows additional metrics that help you estimate progress and scope more easily.

---

## Exercise 3 - Interpret progress across multiple levels

### Goal
Learn how Rollup Columns can support project steering.

### Steps
1. Look at one of the existing **Epics**.
2. Check which **Features** and **Product Backlog Items** are visible underneath it.
3. Compare the values in the rollup columns.
4. Look for signs of:
   - how many child items exist
   - how many of them have already progressed
   - where many open topics are still concentrated
5. Repeat this review for at least one more Epic or Feature.

### Expected result
You understand how progress can be tracked not only on a single work item, but also across higher planning levels.

---

## Exercise 4 - Create a Delivery Plan

### Goal
Create a high-level timeline view for planned work.

### Steps
1. Go to **Boards > Delivery Plans**.
2. Click **New plan** or **Create plan**.
3. Give the plan a meaningful name, for example:
   `Delivery Plan [YourFirstName]`
4. Select your own team for the plan.
5. Make sure the plan is based on the **Sprints** or **Iterations** you created earlier.
6. If needed, choose the relevant backlog levels to show, such as **Features** or **Product Backlog Items**.
7. Save the plan.

### Expected result
A dedicated Delivery Plan has now been created for your team.

---

## Exercise 5 - Configure and read the Delivery Plan

### Goal
Use the Delivery Plan to understand schedule relationships more clearly.

### Steps
1. Open the Delivery Plan you just created.
2. Check whether work items from your sprints and backlogs are visible there.
3. If needed, adjust the visible timeframe or the zoom level.
4. Observe:
   - which work is scheduled in which sprint
   - whether several topics run in parallel
   - whether there are time clusters or bottlenecks
5. Keep in mind that **Rollup Columns** are shown in the backlog, while the **Delivery Plan** is mainly used for time-based visualization.
6. If possible, show additional relevant levels or teams and compare the planning view.

### Expected result
You can now read project timing not only as a list, but also as a visual plan over time.

---

## Typical pitfalls

- If **Rollup Columns** are not offered, check that you are really in the **Backlog** view and not on a board or in a query.
- If **Delivery Plans** is not visible, tell the trainer. Depending on permissions or setup, access may need to be available first.
- If no items appear in the Delivery Plan, verify the team selection, sprint assignment, and visible timeframe.

---

## Final check
By the end of this module, you should have:

1. a backlog view with visible **hierarchy**
2. at least one actively used **Rollup Column**
3. a better understanding of progress across **Epic**, **Feature**, and **PBI**
4. a created **Delivery Plan**
5. a visual timeline of planned work

If these points are visible, you have successfully completed the basics of Rollup Columns and Delivery Plans in Azure DevOps.
