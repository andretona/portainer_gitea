#mirror repositories

if you have the following error (You cannot import from disallowed hosts, please ask the admin to check ALLOWED_DOMAINS/ALLOW_LOCALNETWORKS/BLOCKED_DOMAINS settings) when trying to setup a mirror follow the instruction

- open the app.ini file located in "gitea-data-folder"/gitea/conf/app.ini
- at the end add a section called [migrations]
- in the new section add: ALLOWED_DOMAINS = mydomain.example.invalid
