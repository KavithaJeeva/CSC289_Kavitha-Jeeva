# CSC289 Programming Capstone

## Sprint #2 Status Update 1

**Project Name:** Task Management System

**Team Number:** Group 2

**Team Lead/Scrum Master:** Bethany Arielle Hill

### Tasks Scheduled for this week

1. Complete **Card 2.6 – Data Access**.
2. Add authentication protection to the Tasks and Schedule pages.
3. Restrict task and schedule data to the logged-in user.
4. Add tests for unauthorized access to another user's records.

### Tasks Completed this week [by Name]

**Kavitha Jeeva**

1. Added `@login_required` to the Tasks and Schedule views.
2. Configured `LOGIN_URL = "/login/"`.
3. Added user-specific filtering for Tasks and Schedule data.
4. Added protection for direct URL access to another user's records.
5. Added tests for user-data isolation and unauthorized access.
6. All **9 tests passed**, and the CI check passed successfully.

### Problems/Challenges/Roadblocks

1. The Task and Schedule models were initially empty, so the data-access functionality could not be implemented until the required models were added. **Status: Resolved**
2. Initial tests had a missing import and trailing whitespace issues. These were corrected, and all tests now pass. **Status: Resolved**

### Current Status

**Card 2.6 – Data Access: Completed**

PR #3 has been updated and the CI check passed successfully. The pull request is awaiting the required team approval before merging.
