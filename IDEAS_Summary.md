1. DDEV Project Management Scripts
- Sweep project root checking for consistent project naming convention
- If anything rogue, move it to standardised new proect prompting for a new name
- Check GIT repos exist for each project registered
- Check GIT repos are up to date if not do a diff and spit out a new log for each project detected that has an out of date repo
- Check last snapshot timestamp and data, compare it against the latest database
- Is the project folder structure, outside of project proper, correct
-- Backup <-- Backup misc files.  Could be sitespecific config for settings.local.php, wp-config.php .env files, core configuration detail that type of backup.
-- code <--- Project Root
-- Source
-- code (frameworknames-version) are acceptable, check for the existence of GIT repos on each and report back also.s


2. Provisioning Customer Project
3. Hosting Daily Maintenance and Auto Healing Scripts
4. Open AI TK Conversation Tracker
5. Finance AI Pro Subscription
6. Customer Provisioning Scripts and Process Automation
7. Auto populate a Drupal Project Provionsing File 
- Capture in JSON/YAML format
- Capture via webformm
- Use to create customer in Xero API
- Once customer is created in Xero, Do a Xero API GET in Hubspot to pull customer to hubspot
- Same with Jira to prepulate new customer records in Hubspot

Original deal should existin hubspot before a customer exists

# Create a provisioning automation for onboarding a new customer in Azure AD
# Pull account info through Xero, Black Kite, 
# 