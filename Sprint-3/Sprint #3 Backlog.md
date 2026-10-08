# CSC289 Programming Capstone

# Sprint #3 Backlog

**Project Name:** Task Management System

**Team Number:** Group 2

**Team Lead/Scrum Master:** Bethany Arielle Hill

## Overview

During Sprint #3, I will work on my assigned development tasks for the Task Management System. My assigned cards are **Card 3.2 – Per-task Notes and Priority Levels (UR2)** and **Card 3.3 – Edit and Update Task Status (BR2)**. My work will focus on improving task information, allowing users to manage notes, priority, and status, and making sure the changes are saved correctly while maintaining the existing user-data access protections.

## Card 3.2 – Per-task Notes and Priority Levels (UR2)

For **Card 3.2**, I will work on adding and improving task notes and priority functionality.

### Planned Development Activities

I will:

1. Ensure that task priority uses a defined choice set of **High, Medium, and Low**.
2. Ensure that task notes can be entered and edited for each task.
3. Update the Task model as needed to support notes and priority.
4. Add notes and priority fields to the task create and edit forms.
5. Display notes and priority information in the task list or task interface.
6. Add the ability to sort or filter the task list by priority.
7. Make sure notes and priority information belongs to the correct user task and does not expose another user's information.

### Testing Activities

I will write and run tests to verify that:

- Notes can be added and saved successfully.
- Existing notes can be edited and updated.
- Priority can be selected from the required choices.
- Priority changes are saved correctly.
- Notes and priority are displayed correctly.
- Tasks can be ordered or filtered by priority.
- Existing user-data access protections continue to work.
- The existing project tests continue to pass.

## Card 3.3 – Edit and Update Task Status (BR2)

For **Card 3.3**, I will build on the task editing functionality and allow users to update their task status and other task information.

### Planned Development Activities

I will:

1. Confirm the required task status choices: **To Do, In Progress, and Complete**.
2. Build or update the Django edit form for task information.
3. Create the edit view and URL for updating tasks.
4. Add a clear edit or quick status-change control to the task interface.
5. Allow users to update the status of their own tasks.
6. Make sure status changes persist in the database.
7. Preserve the existing authentication and user-data access protections.
8. Prevent users from editing another user's task through a direct URL.

### Testing Activities

I will write and run tests to verify that:

- A logged-in user can edit their own task.
- A user can change their task status.
- Status changes persist after saving.
- A user cannot edit another user's task.
- Unauthorized users cannot access task editing.
- Existing functionality continues to work after the changes.

## Documentation and Evidence

For both assigned cards, I will document my individual development activities and prepare the required evidence. This will include screenshots or other supporting evidence for the Trello cards, code changes, forms and UI, test results, and CI results. I will make sure the documentation clearly explains my own contributions to the Sprint #3 development work.

## Definition of Done

My assigned Sprint #3 work will be considered complete when:

- Tasks support notes and a defined priority level.
- Notes and priority can be entered, edited, saved, and displayed correctly.
- The task list can sort or filter tasks by priority.
- Users can edit their own tasks and change task status.
- Status changes persist correctly.
- Users cannot edit another user's task.
- Required tests pass.
- Existing functionality continues to work.
- CI checks pass.
- Required documentation and evidence are completed.
- The global Definition of Done is met.

## Expected Outcome

By completing Cards 3.2 and 3.3, I will gain additional experience working with Django models, ModelForms, views, URL routing, database updates, task filtering and sorting, authorization, automated testing, and CI. These tasks will extend the Task Management System while maintaining the user-data access protections developed during Sprint 2.