# Module 03 - Import, Bulk Editing, Queries and Charts

## Goal of this module
In this module, participants learn how to import larger sets of work items into Azure DevOps Services and evaluate them in a structured way afterward. After the lab, they will be able to:

1. import prepared **CSV files** into Azure DevOps
2. update multiple work items at once through **bulk editing**
3. move imported items into the correct team **Area Path**
4. create and save reusable **queries**
5. build and read a **chart** based on a query

## Scenario
In real project work, new tasks often arrive as a list or an early planning export instead of being created one by one. In this module, participants work with exactly that situation: they import a larger set of prepared Product Backlog Items from a CSV file.

Because **two participants still share one project**, there are two separate datasets. After the import, the items are moved into the correct team context through bulk editing. Finally, queries and a chart are created to evaluate the imported work items.

## Prerequisites
- Module 01 and Module 02 have been completed
- You already have your own team named with your **first name**
- A matching **Area Path** already exists for that team
- Access to the Azure DevOps Services organization **tuvsud10**
- The menu labels are primarily **in English**

## Files for this module
The CSV files are stored in the `assets` folder of this module:

- [nutzer-a-workitems.de.csv](assets/nutzer-a-workitems.de.csv)
- [nutzer-b-workitems.de.csv](assets/nutzer-b-workitems.de.csv)
- [user-a-workitems.en.csv](assets/user-a-workitems.en.csv)
- [user-b-workitems.en.csv](assets/user-b-workitems.en.csv)

## Important note before starting
Agree **before the import** who in your pair is **User A** and who is **User B**. Each person should import **only their own file**. This avoids duplicate or incorrectly assigned data in the shared project.

---

## Exercise 1 - Choose the correct CSV file

### Goal
Select the correct import dataset for your role.

### Steps
1. Coordinate with your training partner:
   - one person is **User A**
   - one person is **User B**
2. Open the module folder with the prepared CSV files.
3. Choose the file that matches your language and your role:
   - German: `nutzer-a-workitems.de.csv` or `nutzer-b-workitems.de.csv`
   - English: `user-a-workitems.en.csv` or `user-b-workitems.en.csv`
4. Briefly verify that the titles in the file start with the correct prefix, for example:
   - `User A - ...`
   - `User B - ...`
5. Close the file again without changing the content unnecessarily.

### Expected result
Each participant knows exactly which CSV file to import later.

---

## Exercise 2 - Import the work items

### Goal
Import a larger set of Product Backlog Items into the shared project.

### Steps
1. Sign in to **tuvsud10** and open the project assigned to your pair.
2. Go to **Boards > Work Items**.
3. Find the **Import work items** function. Depending on the current view, it may appear:
   - directly as a button
   - or in the **...** menu
4. Select the CSV file that was assigned to you.
5. Start the import.
6. Wait until Azure DevOps shows the preview or the import result.
7. Spot-check a few imported titles with your prefix, for example:
   - `User A - Finalize kickoff agenda`
   - `User A - Update stakeholder list`
8. Click **Save items** so that the imported work items are actually stored.
9. Then close the import dialog.

### Expected result
The work items from your CSV file are now available in the shared project.

---

## Exercise 3 - Adjust the imported items through bulk editing

### Goal
Learn how to update multiple work items in one action.

### Steps
1. Stay in **Boards > Work Items**.
2. If the filter panel is not already visible, open it by clicking the **Filter** icon in the upper right corner.
3. Use **Filter by keyword** and enter your matching user name, for example:
   - `User A`
   - or `User B`
4. For each matching work item, move the mouse to the left of the ID and set the checkbox there.
5. Repeat this until all relevant imported work items are marked.
6. Right-click one of the marked items and choose **Open selected items in Queries**.
7. The view should now switch to **Queries** and show your selected work items.
8. Click one of the displayed work items and then press **Ctrl+A** so that all visible work items are selected.
9. Right-click again and choose **Edit**.
10. In one shared update, change at least these fields:
   - **Area Path** to your own team area named with your first name
   - optionally **Assigned To** to yourself
   - optionally an additional **Tag** such as `import-module-03`
11. Save the changes for all selected items.
12. Spot-check two or three work items to confirm that the changes were applied correctly.

### Expected result
You have edited multiple items at once and prepared them for later evaluation.

---

## Exercise 4 - Bring the imported items into your team context

### Goal
Make sure the imported items appear in the correct team backlog and board.

### Steps
1. Open **Boards > Backlogs**.
2. Use the **team selector** to switch to your own team named with your first name.
3. Check whether your imported work items are now visible in your team backlog.
4. If some items are missing, verify their **Area Path** again.
5. If needed, correct remaining assignments through another **bulk edit**.
6. Then switch to **Boards > Boards** and check the visibility there as well.

### Expected result
Your imported work items now appear in the team context of your own backlog and board.

---

## Exercise 5 - Create a first query for the imported items

### Goal
Create a reusable query for your imported data.

### Steps
1. Go to **Boards > Queries**.
2. Create a new query of type **Flat list of work items**.
3. Give the query a meaningful name, for example:
   `My imported PBIs`
4. Add suitable filters, for example:
   - **Work Item Type** = `Product Backlog Item`
   - **Title** contains `User A` or `User B`
   - **Area Path** = your team area
5. Run the query.
6. Check that it mainly shows the items you just imported.
7. Save the query.

### Expected result
You have created a personal query that helps you find your imported work items quickly.

---

## Exercise 6 - Create a second query for evaluation

### Goal
Use queries for a more specific project question.

### Steps
1. Create a second query, again as a **Flat list of work items**.
2. Give it a name such as:
   `My open imported PBIs`
3. Use your prefix and your **Area Path** again as filters.
4. Add at least one more filter, for example:
   - **State** <> `Done`
   - or **Tags** contains `reporting`
   - or **Tags** contains `communication`
5. Run the query.
6. Compare the result with the first query.
7. Save this query as well.

### Expected result
You understand that queries are not only for searching, but also for targeted evaluation.

---

## Exercise 7 - Create a meaningful chart from a query

### Goal
Visualize your imported work items in a way that produces a useful training result immediately.

### Steps
1. Open one of your saved queries, preferably the one with several visible results.
2. Switch to the **Charts** area.
3. Click **New chart** or **Add chart**.
4. Choose an easy-to-read chart type, for example:
   - **Pie chart**
   - or **Bar chart**
5. Preferably configure the chart so that the items are grouped by **Tags**.
6. Give the chart a name such as:
   `Topics in my imported PBIs`
7. Save the chart.
8. Read the result briefly:
   - Which tags appear most often?
   - Which topics dominate your imported backlog?
   - Where do you see clusters such as `planning`, `communication`, or `reporting`?
9. Optionally, create a second chart by **State** later, once some items have been moved to other work states.

### Expected result
You have successfully created a chart from a query and can visually evaluate the distribution of your imported work items.

---

## Typical pitfalls

- If no imported items are visible afterward, the step **Save items** is often the missing action.
- If your items do not appear in your own backlog, check **Area Path** and the **team selector** first.
- If the chart shows almost no variation, start with **Tags** instead of **State**, because all CSV items initially start in **New**.

---

## Final check
By the end of this module, you should have:

1. imported the correct CSV file for **User A** or **User B**
2. a larger set of new **Product Backlog Items** in the project
3. adjusted the imported items through **bulk editing**
4. assigned the work items to your own **Area Path**
5. created at least **two saved queries**
6. saved at least **one chart**

If these points are visible, you have successfully completed the basics of imports, bulk editing, queries, and charts in Azure DevOps.
