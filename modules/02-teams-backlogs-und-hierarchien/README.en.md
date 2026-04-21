# Module 02 - Teams, Backlogs and Hierarchies

## Goal of this module
In this module, participants learn how to work with their own teams and hierarchies inside a shared Azure DevOps project. After the lab, they will be able to:

1. create their own **team** based on their **first name**
2. understand that teams have their own **Backlogs** and **Boards**
3. explain the connection between **team**, **Area Path**, and visible work items
4. move existing work items into the correct team scope
5. use backlog levels such as **Epic**, **Feature**, and **Product Backlog Item**
6. create parent-child relationships between work items

## Scenario
In the first module, several Product Backlog Items were already created for a shared project. Now the project needs more structure: each person in the participant pair sets up a personal team and assigns their existing tasks to that team.

After that, larger planning elements such as **Epics** and **Features** are added so that the individual tasks become part of a clear hierarchy.

## Prerequisites
- Module 01 has been completed
- Access to the Azure DevOps Services organization **tuvsud10**
- Access to the project assigned to your participant pair
- The menu labels are primarily **in English**
- Several Product Backlog Items already exist from Module 01

## Collaboration note
Each person creates a team using their own **first name**, for example:

`Maria`

If the same first name appears twice in a group, add the first letter of the last name, for example `MariaS`.

---

## Exercise 1 - Review the existing work items

### Goal
Get an overview of the Product Backlog Items that were already created in Module 01.

### Steps
1. Sign in to the organization **tuvsud10**.
2. Open the project assigned to your pair.
3. Go to **Boards > Work Items**.
4. Find the work items that were created with your first name, for example:
   - `[YourFirstName] Prepare kickoff meeting`
   - `[YourFirstName] Create stakeholder list`
   - `[YourFirstName] Align communication plan`
5. Open one of these work items and look at the **Area Path** field.
6. Close the work item again.

### Expected result
You can see that the work items already exist, but they are not yet necessarily organized for your own team.

---

## Exercise 2 - Create your own team

### Goal
Create your own team inside the shared project.

### Steps
1. Click **Project settings** in the lower left corner.
2. Open **Teams**.
3. Click **New team**.
4. Enter your **first name** as the team name, for example:
   `Maria`
5. Enable the checkbox **Create an area path with the name of the team**.
6. If a description field is available, you can optionally enter:
   `Personal training team for Module 02`
7. Confirm with **Create**.
8. Check that your new team is now visible in the team list.

### Expected result
There is now a dedicated team in the project with your first name, and a matching **Area Path** was created automatically.

---

## Exercise 3 - Review the automatically created Area Path and assign it to your team

### Goal
Learn how teams are connected to their backlogs and boards through Area Paths.

### Steps
1. Stay in **Project settings**.
2. Open **Teams** and select your new team.
3. Open the team settings for **Areas**.
4. Check that an Area Path with your first name already exists and is available.
5. This entry should exist automatically because you enabled **Create an area path with the name of the team** in the previous exercise.
6. If the area is not yet active for your team, select it now.
7. Save the setting if Azure DevOps requires it.

### Expected result
Your team is now linked to its automatically created Area Path, which allows it to have its own backlog and board scope.

---

## Exercise 4 - Move your existing work items into your team

### Goal
Assign the tasks from Module 01 to the correct team scope.

### Steps
1. Return to **Boards > Work Items**.
2. Open the first work item with your first name.
3. Find the **Area Path** field.
4. Change the value to the Area Path that belongs to your team, using your first name.
5. Save the work item.
6. Repeat these steps for the other work items from Module 01 that belong to you.
7. Make sure you only update your own work items and not the items of the other participant.

### Expected result
Your existing Product Backlog Items are now assigned to your personal team through the Area Path.

---

## Exercise 5 - Open your team's own backlog and board

### Goal
Recognize that each team in Azure DevOps has its own view of work.

### Steps
1. First open **Boards > Backlogs**.
2. Briefly observe which items are visible in the current view.
3. Then use the **team selector** at the top left of the project view.
4. Select your own team, named with your first name.
5. Check how the visible work items in the backlog change.
6. Then open **Boards > Boards**.
7. Observe whether the board mainly shows the work items that were assigned to your team via the Area Path.
8. If your items are not visible, recheck the **Area Path** on the work items and the team settings.

### Expected result
You understand that teams have their own backlogs and boards, and that the Area Path determines which items appear there.

---

## Typical pitfalls

- If the wrong items appear in the backlog or board, first check the **team selector** in the upper left area.
- If your own work items are missing from your team view, verify the **Area Path** on those items.
- If you still see both your own and the other participant's items together, the separation by team and area path is usually not fully configured yet.

---

## Exercise 6 - Work with backlog levels: create an Epic and Features

### Goal
Learn the different planning levels in Azure DevOps.

### Steps
1. Stay in **Boards > Backlogs** within your own team.
2. Open the selector for the backlog level.
3. First switch to the **Epics** level.
4. Create a new Epic with a title such as:
   `[YourFirstName] Mobility project preparation`
5. Then switch to the **Features** level.
6. Create at least two Features, for example:
   - `[YourFirstName] Kickoff and governance`
   - `[YourFirstName] Stakeholder and communication`
7. Save the new items.
8. Take a moment to observe that **Epics**, **Features**, and **Product Backlog Items** are different backlog levels.

### Expected result
You have created an Epic and multiple Features and learned how backlog levels work in Azure DevOps.

---

## Exercise 7 - Build a hierarchy between the work items

### Goal
Link individual tasks to higher-level planning items.

In this exercise, you learn **two different ways** to create these relationships. Try both if possible.

### Option A - Use the Mapping view
1. Stay in **Boards > Backlogs** within your own team.
2. Choose the backlog level where your **Product Backlog Items** are visible.
3. Open the **Mapping** view or the **Parent/Child** area, if it is available in your project.
4. Show the higher backlog levels so that you can see your **Features** and **Epic**.
5. First map the **Features** to your **Epic**.
6. Then map your existing **Product Backlog Items** to the matching **Features**.
7. Make sure each lower-level item is connected to the correct higher-level planning item.
8. Save the changes if Azure DevOps requires it.

### Option B - Open the work item and add a link
1. Open one of your **Features** or **Product Backlog Items** directly.
2. In the work item, switch to the **Links** or **Related Work** section.
3. Click **Add link** or the comparable button in your view.
4. Choose the correct relationship type:
   - **Parent** if the current item should be assigned to a higher-level item
   - **Child** if you are adding a lower-level item from the perspective of the higher-level work item
5. Search for the work item that should be linked, such as your Epic or one of your Features.
6. Confirm the link and save the work item.
7. Repeat this until your structure is complete.

### Check the result afterward
1. Switch again between the **Epics**, **Features**, and **Product Backlog Item** backlog levels.
2. Verify that the relationships are displayed correctly.
3. If needed, reopen individual work items and review the **Links** section.

### Example of a useful hierarchy
- Epic: `[YourFirstName] Mobility project preparation`
  - Feature: `[YourFirstName] Kickoff and governance`
    - PBI: `[YourFirstName] Prepare kickoff meeting`
  - Feature: `[YourFirstName] Stakeholder and communication`
    - PBI: `[YourFirstName] Create stakeholder list`
    - PBI: `[YourFirstName] Align communication plan`

### Expected result
You can now see a clear hierarchy from Epic to Feature to the individual Product Backlog Items, and you know two ways to create these relationships.

---

## Final check
By the end of this module, you should have:

1. your own **team** named with your first name
2. a matching **Area Path** for that team
3. your existing work items visible in your **team backlog**
4. at least one **Epic**
5. at least two **Features**
6. a visible **hierarchy** between the Epic, the Features, and the Product Backlog Items

If these points are visible, you have successfully completed the basics of teams, Area Paths, backlog levels, and work item relationships in Azure DevOps.
