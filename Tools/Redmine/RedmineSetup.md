
# Redmine Initial Setup Guide

1. login to redmine w/ admin creds
	1. Create CCL Account
		1. Go to Administration
		2. Go to Users
		3. Click New User
		4. Fill in the appropriate fields to create and account for the CCL
			Login : <first.last>
			Check "Administrator"
			ensure the "generate Password" and Must change password at next logon" is unchecked
		5. Click create
	2. Create Groups
		1. Go to Groups under administrationf
		2. Click "New Group"
		3. Name the Group. e.g. 856CPT
		4. Click Create
		5. Click the create group
		6. Click on the "users" tab
		7. Check the CCL user
		8. click add
	3. Create Roles and Permission
		1. CLick on the "Roles and Permission" under Administration
		2. Delete the following Roles:
			Manger
			Developer
			Reporter
		3. click on "New Role"
		4.  Name the role e.g. 856CPT
		5. Ensure that "Issues can be assigned to users with this role" is checked
		6. Set "issue visibility" to "All issues"
		7. set "Time logs visibility" to "All time entries"
		8. set "users visibility" to "All active users"
		9. Under Permissions ensure the following are selected
			All under Project, and Issues
		10. Click create Button
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
			New
			In Progress
			Resolved
			Closed
	6. Check Workflow
		1. Under Administration click Workflow
		2. Click edit
		3. Ensure the following exists under "Current Status"
			New issue
			New
			In Progress
			Rsolved
			Closed
		4. Check ALL the checkboxes
		5. Select Save
	7. Create a Project
		1. Select "Project" under "Administration"
		2. Click on "New Project"
		3. Name the project w/ Mission Name
		4. ensure "Public" and "Inherit members" checkboxes are checked
		5. Under Modules ensure that "Isuse Tracking" and "Time Tracking" are checked
		6. Click the "Create" button
		7. Go to the "Members" Tab
		8. click "New Members"
		9. Select the "856CPT" Group
		10. Select the "856CPT" Users
		11. Click "Add"
		12. Click the Issue Tracking Tab
		13. Select the "856CPT" checkbox under Tracker
		14. Click "Save"
		
