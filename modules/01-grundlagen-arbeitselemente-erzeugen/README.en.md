# Module 01 - Basics of Creating Work Items

## Goal of this module
In this module, participants learn the most important basic functions of Azure DevOps Boards. After the lab, they will be able to:

1. navigate **Boards**, **Backlogs**, and **Work Items**
2. create **Product Backlog Items (PBIs)** from multiple entry points
3. add **comments**
4. upload **attachments**
5. change the **state/status** of a work item

## Scenario
You are supporting a project management team that is preparing a new mobility-related project. The first organizational tasks should be documented and tracked clearly in Azure DevOps Boards.

The exercises are intentionally **not software-development focused**. Instead, they use simple project management examples such as kickoff planning, stakeholder management, and communication planning.

## Prerequisites
- Access to the Azure DevOps Services organization **tuvsud10**
- Access to the project assigned to your participant pair
- Permission to create and edit work items
- A browser and a small sample file for a later attachment, such as a PDF, Word document, or image
- The Azure DevOps menu is expected to be primarily **in English**

## Process note
This basics module deliberately uses the **Product Backlog Item** work item type so that the Azure DevOps interface is easy to understand. In later modules, the same core actions can be transferred to the **TUV Scrum for Mobility** process with its own work item types.

## Collaboration note
Each project is shared by **two participants**. To avoid confusion inside the same project, use your **first name** in your sample titles, for example:

`[Maria] Prepare kickoff meeting`

---

## Exercise 1 - Orientation in Azure DevOps Boards

### Goal
Learn where the most important areas are located.

### Steps
1. Sign in to the Azure DevOps Services organization **tuvsud10**.
2. Open the project assigned to your pair for the training.
3. In the left navigation, click **Boards**.
4. Open these areas one after another:
   - **Boards > Backlogs**
   - **Boards > Boards**
   - **Boards > Work Items**
5. In each area, take a brief look at where new items can be created.
6. Return to **Boards > Backlogs** afterward.

### Expected result
You now know where to find the backlog, the board, and the central work item list.

---

## Exercise 2 - Create a Product Backlog Item in the backlog

### Goal
Create your first work item directly in the backlog.

### Steps
1. Stay in **Boards > Backlogs**.
2. Make sure the correct backlog level is shown. If several levels are available, choose the level for **Product Backlog Items** or the level specified by the trainer.
3. Click **New Work Item** or use the input line below the list.
4. Enter the title:
   `[YourFirstName] Prepare kickoff meeting`
5. Open the newly created work item.
6. Fill in at least these fields:
   - **Title**: already filled
   - **Description**: `Plan the kickoff, prepare the agenda, and align the participants.`
   - **Assigned To**: assign it to yourself if appropriate
7. Save the work item.

### Expected result
One Product Backlog Item has been created and saved directly from the backlog.

---

## Exercise 3 - Create a Product Backlog Item on the board

### Goal
Create another work item from a different place, directly on the Kanban board.

### Steps
1. Switch to **Boards > Boards**.
2. Find the first column on the left, such as **New**, **To Do**, or a similar starting column.
3. In that column, click **New item**, **+**, or the local add button.
4. Enter the title:
   `[YourFirstName] Create stakeholder list`
5. If Azure DevOps asks for the type, select **Product Backlog Item**.
6. Open the new card or work item.
7. Add this description:
   `Collect and document the key internal and external stakeholders.`
8. Save the change.

### Expected result
You have created a second Product Backlog Item directly from the board.

---

## Exercise 4 - Create a Product Backlog Item through "Work Items"

### Goal
Learn a third entry point for creating new work items.

### Steps
1. Switch to **Boards > Work Items**.
2. At the top, click **New Work Item**.
3. Select **Product Backlog Item**.
4. Enter the title:
   `[YourFirstName] Align communication plan`
5. In the description, enter:
   `Define how project status updates will be communicated.`
6. Save the work item.
7. Verify that the new item now appears in the work item list.

### Expected result
You have now created Product Backlog Items from three different areas: **Backlog**, **Board**, and **Work Items**.

---

## Exercise 5 - Add comments to a work item

### Goal
Document short feedback directly inside the work item.

### Steps
1. Open the work item `[YourFirstName] Prepare kickoff meeting`.
2. Find the **Discussion**, **Comments**, or **History** area.
3. Add a short comment, for example:
   `An initial proposal for the meeting date has been aligned with the team.`
4. Save the comment if your view requires it.
5. Check that the comment is visible in the history afterward.

### Expected result
The work item now contains a traceable update in the comments or history view.

---

## Exercise 6 - Upload an attachment

### Goal
Link additional material to a work item.

### Steps
1. Open the work item `[YourFirstName] Create stakeholder list`.
2. Find the icon or section for **Attachments**.
3. Upload a small sample file, for example:
   - an agenda
   - a PDF
   - an image
4. Wait until the upload is complete.
5. Save the work item again if needed.

### Expected result
At least one attachment is now visible in the work item.

---

## Exercise 7 - Change the status of a work item

### Goal
Learn how to maintain the progress status of work.

### Steps
1. Open the work item `[YourFirstName] Align communication plan`.
2. Find the **State** or **Status** field.
3. Change the value to the next meaningful state in your project, for example:
   - `New` to `Approved`
   - `Approved` to `Committed`
   - `To Do` to `Doing`
4. Save the change.
5. Return to **Boards > Boards** and observe whether the card moves to a different column.

### Expected result
You understand how Azure DevOps makes progress visible through the state or status field.

---

## Final check
By the end of this module, you should see the following:

1. at least **three Product Backlog Items**
2. one work item with a **comment**
3. one work item with an **attachment**
4. at least one work item with a **changed status**

If all of these are visible, you have successfully completed the absolute basics of Azure DevOps Boards.
