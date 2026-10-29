# CSC289 Programming Capstone

## Sprint #4 Status Update 1

**Project Name:** Task Management System  
**Team Number:** Group 2  
**Team Lead/Scrum Master:** Bethany Arielle Hill  
**Sprint:** Sprint 4  
**Status Update:** 1

### 1. Tasks Assigned

My assigned task is:

**Card 4.1 – Input and Save the Weekly Meeting Schedule (UR1)**

**Trello Card:**

![Sprint 4 Status Update 1](Screenshots/Sprint%20%234%20Status%20Update%201.png)

### Week 1 Evidence

**1. Code Implementation**

![Sprint 4 Week 1 Code](Screenshots/Sprint-4_week1_code.png)

**2. Automated Tests – Passing**

![Sprint 4 Week 1 Tests](Screenshots/Sprint-4_Week1_Tests.png)

**3. Continuous Integration (CI) – Passed**

![Sprint 4 Week 1 CI Passed](Screenshots/Sprint-4_Week1_CI-Passed.png)

### Additional Sprint 4 Work Evidence

**1. Re-save `requirements.txt` as UTF-8**

![Re-save requirements.txt as UTF-8](Screenshots/Re-save%20requirements.txt%20as%20UTF-8.png)

**2. Update CI Triggers**

![Run CI on pushes and PRs to main](Screenshots/Run%20CI%20on%20pushes%20and%20PRs%20to%20main.png)


The goal of Card 4.1 is to allow users to enter and save their weekly meeting schedules under their own accounts.

### 2. Work Completed

During Week 1, I worked on the basic meeting schedule functionality.

- Defined the Meeting model with the required meeting information and user relationship.
- Created the database migration.
- Built the meeting form and view for entering meetings manually.
- Implemented the ability to save meetings under the logged-in user's account.
- Worked on displaying saved meetings on the schedule page.

### 3. Additional Sprint 4 Work Completed

Along with my main assigned task, I completed work on two supporting tasks:

**Update the CI Triggers**
- Updated the GitHub Actions workflow to run CI on pushes to `main` and pull requests targeting `main`.
- Removed `develop` from the branch trigger list.
- Created a pull request and verified that the CI check passed.

**Re-save `requirements.txt` as UTF-8**
- Re-saved `requirements.txt` using UTF-8 encoding.
- Preserved the existing package names and versions.
- Verified the requirements installation.
- Created a pull request and confirmed that the CI check passed.

**Status:** Both pull requests passed their CI checks and are awaiting reviewer approval before merging.

### 4. Current Status

**Status: In Progress**

The basic meeting entry and saving functionality has been implemented, and saved meetings are appearing on the schedule page. The remaining work involves completing verification and testing to ensure the feature meets its acceptance criteria.

### 5. Remaining Work

I plan to complete the following tasks during Week 2:

- Finish verifying the weekly schedule display.
- Write tests to confirm that meetings can be saved and loaded correctly.
- Verify that users can access only their own meetings.
- Run the relevant tests and resolve any failures.
- Confirm that the Definition of Done is satisfied.

### 6. Challenges

I needed to troubleshoot the meeting form and schedule templates to ensure that the form fields and saved meeting information displayed correctly. I worked through these issues and was able to display saved meeting information on the schedule page.

### 7. Plan for Week 2

During Week 2, I will focus on completing the remaining Card 4.1 functionality, writing and running tests, verifying user-specific meeting access, and confirming that the feature meets the acceptance criteria.

I will also follow up on the two supporting pull requests and address any review feedback if needed.

### 8. Summary

During Sprint 4 Week 1, I made progress on Card 4.1 by working on the meeting model, form, saving functionality, and schedule display. I also completed the CI trigger and requirements encoding updates, with both pull requests passing their CI checks.

Card 4.1 remains in progress. I plan to complete the remaining testing and verification during Week 2 before marking the task as Done.
