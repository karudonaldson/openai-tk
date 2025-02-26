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
3. Daily maintenance tasks in cron
