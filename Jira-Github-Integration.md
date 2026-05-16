Step 1: Open Jira Administration
Log in to Jira as an administrator.
Click Settings.
Select Apps.

Step 2: Find the GitHub for Jira App
In the Apps section, click Find new apps.
Search for GitHub for Jira.
Install the official app from Atlassian Marketplace.

Step 3: Connect Your GitHub Account
After installation, go to Apps → Manage apps → GitHub for Jira → Configure.
Click Connect GitHub organization.
Sign in to GitHub.
Authorize Jira to access your repositories.
Choose the GitHub organization or repositories you want to connect.
Save the configuration.

Step 4: Use Jira Issue Keys in GitHub
Include the Jira ticket ID in:
Branch names
Commit messages
Pull request titles
Example:
Branch: feature/PROJ-123-login-page
Commit: PROJ-123 Added login validation
PR Title: PROJ-123 Implement login page

Step 6: Verify Integration
Open a Jira issue such as PROJ-123. You will see:
Commits
Branches
Pull Requests
Deployment information (if configured)
