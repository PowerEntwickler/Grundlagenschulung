# Copilot Instructions

## Repository purpose
This repository is for an **Azure DevOps Boards Grundlagenschulung** built as hands-on labs. The content should focus on general project management workflows rather than software development scenarios.

## Current repository state
This repository currently only contains repository metadata and this instructions file. There is no checked-in application, library, README, CONTRIBUTING guide, or language-specific manifest yet, so do not assume a software stack until real project files are added.

## Build, test, and lint
No project-specific build, test, lint, or single-test commands are configured in the repository at this time. When manifests or CI files are added, use those as the source of truth and update this section with the exact commands that actually work in the repo.

## High-level architecture
The intended structure is **module-based training content**. Each module should contain Markdown lab guides in **German and English**, covering the same exercise flow for both audiences. The repository is documentation-first: the core "architecture" is a set of clearly separated hands-on lab modules rather than application code.

All labs should be written for participants who may be less technical, so steps should be highly explicit, clearly structured, and easy to follow without software engineering background knowledge.

The target environment is **Azure DevOps Services**. The training organization is **tuvsud10**, and the Azure DevOps menu labels are expected to be shown primarily in **English**.

The labs should use the **TUV Scrum for Mobility** process, based on the **System Scrum** process. Content should reflect its backlog model:
- portfolio backlog above Epic using **Strategy Epics** with the work item type **Strategic Epic**
- backlog **Prozess** with **IEP Milestone (default)**, **IEP Task**, and **IEP Checklist Item**

The first module should cover the absolute basics of Azure DevOps Boards. It should include hands-on exercises for creating **Product Backlog Item** work items from different entry points, adding comments, uploading attachments, and changing the work item state/status.

The second module should teach how participants create their own team based on their **first name**, explicitly enabling **"Create an area path with the name of the team"** during team creation. It should show how existing work items are moved into that team via **Area Path**, how each team has its own **Backlogs** and **Boards**, and how parent-child **relationships** between work items can be created both via the **Mapping** view and via **Links** inside an individual work item. It should also cover **Epic** and **Feature** creation and the use of different **backlog levels**.

The third module should include importable CSV assets for **Nutzer A / Nutzer B** or **User A / User B**, because two participants share one project. The lab should explicitly ask them to agree first who is **A** and who is **B**, then import the correct CSV and confirm the import with **Save items**. For the bulk edit flow, the instructions should guide them through **Filter by keyword**, selecting items via the checkbox left of the ID, using **Open selected items in Queries**, then **Ctrl+A** and **Edit** to move the imported items into their own **Area Path**. The module should finish with practical use of **queries** and at least one **chart**.

The fourth module should teach Azure DevOps **Kanban board** customization in a hands-on way. It should cover configuring custom **columns**, **swimlanes**, **WIP limits**, **Definition of Done**, splitting columns into **Doing** and **Done**, and visual **style rules** such as tag colors. The exercises should use the participant's own team board so they see the impact of each setting immediately.

The fifth module should teach **sprint planning** in Azure DevOps Services. It should instruct participants to create **three sprints** in the project configuration, grouped under their own **team name**, using concrete sprint dates based on the current training date, with the **current day falling inside Sprint 1**. Team sprint configuration should use **Boards > Team configuration**, sprint assignment should be shown in the backlog via the **Planning** panel, and task creation in the sprint backlog should use the standard work item type **Task** only. The module should then show how to move work items into the right sprint and set **Remaining Work** values.

The next module should teach how to use **Rollup Columns** in the backlog view to display hierarchy and progress, and how to create a **Delivery Plan** to visualize work over time. The exercises should focus on showing progress across Epics, Features, and Product Backlog Items in a way that is easy for project-management learners to understand.

## Key conventions
Keep German and English lab versions structurally aligned so both languages describe the same hands-on flow. Prefer detailed numbered instructions, clear section headings, and project-management examples over developer-centric exercises. Use the exact process and work item terminology from **TUV Scrum for Mobility** consistently across all future content.

In German lab guides, still reference the real **English Azure DevOps UI labels** such as **Boards**, **Backlogs**, **Work Items**, **Discussion**, **Attachments**, and **State** so participants can follow the cloud UI exactly.

Each training project is shared by **two participants**. Future labs should therefore include pair-friendly instructions and use each participant's **first name** in example work item titles to avoid collisions inside the shared project.

Maintain a professional, consistent lab structure across the repository: **goal**, **scenario**, **prerequisites**, **step-by-step exercises**, **expected result**, and **final check**. Add short troubleshooting notes when Azure DevOps UI pitfalls are likely, especially for **Team selector**, **Area Path**, **Iteration Path**, **Planning**, or **Delivery Plans** visibility.

Prefer one explicit click path over vague alternatives whenever a stable Azure DevOps UI route is known. For visualizations, make sure the prepared dataset leads to a meaningful result; for example, when imported items all start in **New**, prefer charts by **Tags** or another field with visible variation.

For Kanban-specific labs, keep best-practice guidance compact and actionable: use only as many columns as needed, keep swimlanes limited, set realistic WIP limits, define a short and checkable Definition of Done, and use styles sparingly for emphasis.
