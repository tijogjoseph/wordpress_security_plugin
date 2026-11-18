# wordpress_security_plugin
Security pugin details

# Version 0.3.7
Features Implemented 
 - Login Protection - Failed login attempts with Username/IP, temporary lockout etc.
 - 2FA - Implemented, SMS not implemented
 - Captcha - Implemented for core flows
 - Password strength - Implemented for core flows
 - Inactivity logout - Done
 - Firewall rules - Partially done
 - Backups - Backup creation is done, still tests need to be performed
 - backup reliability - Implemented
 - Site checks and DB scan - Partially implemented
 - Admin dashboard - Done

PRO features
- Google search console integration
- Advanced technical SEO
- Automation of manual tasks

# Version 0.3.8
- PRO feature introduced - Scan site files
- It provides a report but it does not delete or quarantine files

# Version 0.3.9
- Changes with dashboard tabs UI as routed views

# Version 0.4.0
- Run scans on a schedule. It provides report only, no deletion or quarantine of files

# Version 0.4.1
- Scans run in resumable batches of 500 PHP files.
- Progress is retained if a cron request times out or fails.
- Overlapping scans are prevented.
- The dashboard shows current progress.
- Added Run file monitoring now.
- Added Reset file baseline.

# Version 0.4.2
- Successful-login email notifications, enabled by default.
- Notifications include login time, trusted server IP, account, and browser category.
- Active session details on the WordPress profile page.
- “Log out other sessions” and “Log out all sessions” controls.

# Version 0.4.3
- Uses the existing profile form for 2FA and session actions.
- Shows setup progress and success notices.
- Produces a pending secret and authenticator-code confirmation step.
- Avoids nested HTML forms.

# Version 0.4.4
- In 0.4.4, 2FA and session actions now submit through WordPress’s standard button, so setup and cancel shouldn’t trigger that misleading warning.
