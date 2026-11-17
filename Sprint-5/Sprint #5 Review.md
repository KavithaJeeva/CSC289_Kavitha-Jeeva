# CSC289 Programming Capstone
## Sprint #5 Review

**Project Name:** Task Management System  
**Team Number:** Group 2  
**Team Lead/Scrum Master:** Bethany Arielle Hill  
**Team Member:** Kavitha Jeeva  

### 1. My Sprint #5 Contributions

During Sprint 5, I worked on three tasks: K1 – Settings Configuration, K3 – Navbar and Messages, and K2 – PythonAnywhere Deployment.

During Week 1, I worked on improving the Django settings for production, including environment variables and security settings. I also updated the navigation bar, added success and error messages, and improved the logout functionality. I added and ran tests to check these changes.

During Week 2, I deployed the Task Management System to PythonAnywhere. I configured the production environment, database, static files, WSGI, and HTTPS. I also created a new superuser account and tested the live application.

The website is now live at [https://bahill3.pythonanywhere.com/](https://bahill3.pythonanywhere.com/). I also prepared `docs/deployment.md` to explain the deployment process.

### 2. Testing Results

During Week 1, the K1 settings tests passed, and the full project test run after the K3 updates completed with **41 tests passed**.

During Week 2, I successfully tested login, task creation, weekly meeting creation, and the Django Admin page on the live website.

### 3. CI Testing Results

The CI checks passed for PR #37 (K1), PR #38 (K3), and PR #51 (K2 deployment guide). The pull requests were submitted for review and approval.

### 4. Challenges and Solutions

One challenge was configuring the application to work correctly in the production environment. I also needed to create a new superuser because the local database users were not available on the server. I resolved these issues by updating the server configuration and creating a new account.

### 5. Summary

Overall, Sprint 5 gave me practical experience with Django settings, authentication, Bootstrap, automated testing, GitHub Actions, and deploying a web application. I contributed to improving the application and successfully deployed it to PythonAnywhere.