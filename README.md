# jira-azure Devops-integration.

This project demonstrates the integration of Jira with Azure DevOps using the Getint add-on. 
It enables bi-directional syncing of tasks, epics, and subtasks, along with status updates, 
comments, and attachments.

## Setup Steps

1. Installed the Getint add-on in Jira.
2. Generated API tokens for Jira and Azure DevOps.
3. Connected Jira and Azure DevOps accounts using the API tokens.
4. Verified that the integration connection is active.

## Issue Type and Field Mapping

- **Issue Types:**
  - Jira Task → Azure DevOps Task
  - Jira Epic → Azure DevOps Epic
  - Jira Subtask → Azure DevOps Issue

- **Fields Synced:**
  - Title / Summary
  - Description
  - Assignee / Assigned To
  - Reporter / Created By
  - Sprint / Iteration Path
  - Comments & Attachments

- **Status Mapping:**
  - To Do → To Do
  - In Progress → Doing
  - Done → Done


## Testing the Integration

1. Created a Task in Jira → appeared in Azure DevOps automatically.
2. Started a Sprint in Jira → all tasks appeared in Azure DevOps.
3. Updated task statuses in Jira → verified updates in Azure DevOps.
4. Updated task details, comments, and attachments → verified bi-directional sync.


## Screenshots

### Integration Setup

<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/375ac4c9-489b-4ed5-932c-542f3fc89d63" />
<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/2e208d34-e819-4dbc-8eb0-f83de3b78554" />

### Sample Task Synced

<img width="1920" height="1080" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/fcbcd52d-70cc-48a5-aa44-4e5b06ba4dd8" />
<img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/cd9f830e-e83c-4588-bc58-aadb2f24fbb4" />



