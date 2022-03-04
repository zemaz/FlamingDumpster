
# Redmine Initial Setup Guide
### Note. use "ctrl + f" if what you are looking for not visible

1. login to redmine w/ admin creds
	1. Create CCL Account
		1. Go to Administration
		2. Go to Users
		3. Click New User
		4. Fill in the appropriate fields to create and account for the CCL
			* Login : <first.last>
			* Check "Administrator"
			* ensure the "generate Password" and Must change password at next logon" is unchecked
		5. Click create
	2. Create Groups
		1. Go to Groups under administration
		2. Click "New Group"
		3. Name the Group 856CPT
		4. Click Create
		5. Click the 856CPT group
		6. Click on the "users" tab
		7. click on "New user"
		8. Check the CCL user
		9. click add
	3. Create Roles and Permission
		1. CLick on the "Roles and Permission" under Administration
		2. Delete the following Roles:
			* Manger
			* Developer
			* Reporter
		3. click on "New Role"
		4.  Name the role e.g. 856CPT
		5. Ensure that "Issues can be assigned to users with this role" is checked
		6. Set "issue visibility" to "All issues"
		7. set "Time logs visibility" to "All time entries"
		8. set "users visibility" to "All active users"
		9. ignore the "Copy workflow from"
		10. Under Permissions ensure the following are selected:
			* All Check boxes under Project
			* All checkboxes under "Issue tracking"
		11. Click create Button
	4. Create Trackers
		1. Click on "Trackers" under Administation
		2. Delete all the listed trackers
		3. Click "New Tracker"
		4. Name the tracker: e.g. 856CPT
		5. Change default status to New
		6. Ensure that "Issues displayed in roadmap" is checked
		7. Populate the Decription appropriately
		8. Ensure all checkboxes for "standard fields" are checked
		9. Click "Create"
	5. Verify "Issue Status"
		1. Click on Issue Statuses under Administration
		2. Ensure the the following statuses are available
			* New
			* In Progress
			* Resolved
			* Closed
		3. Delete the rest
	6. Check Workflow
		1. Under Administration click Workflow
		2. Click edit
		3. Ensure the following exists under "Current Status"
			* New issue
			* New
			* In Progress
			* Rsolved
			* Closed
		4. Ensure that all the checkboxes are checked
		5. Select Save
	7. Create a Project
		1. Select "Project" under "Administration"
		2. Click on "New Project"
		3. Name the project w/ Mission Name
		4. ensure "Public" and "Inherit members" checkboxes are checked
		5. Under Modules ensure that "Isuse Tracking" and "Time Tracking" are checked
			1. Uncheck the rest
		7. Click the "Create" button
		8. Go to the "Members" Tab
		9. click "New Members"
		10. Select the "856CPT" Group
		11. Select the "856CPT" Roles
		12. Click "Add"
		13. Click the Issue Tracking Tab
		14. Select the "856CPT" checkbox under Tracker
		15. Click "Save"
	8. Verify that configuration
		1. Click "Issues" (blue)
		2. Ensure "New Issue" button is present
			1. If not present, reverify settings.	
