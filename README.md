# Extended-Day-Services_Child-Time-Tracking

- Security / Roles
    - Manger:
		  - Create Employee Account
		  - Generate Invoices
		  - Create Student Accounts
      - View Audit Logs
	- Employee:
		  - Clock Students In/Out

- Who can edit student hours?

- Clock In/Out Student Using Unique QR Code

- Generate Invoices:
	- Frequency - Weekly/Monthly/Ad-Hoc?
	- Format - PDF/Doc/Email?
	- Track Invocie Payment Status?
    - In/Out of scope?
		- Who marks an invoice paid?
	- How is the billable rate defined?
	- Do taxes need to be included in invoces?
	- How are hours billed?
    - What increments?
      - Minute/Quarter Hour
        - How is rounding done?

- Audits - What needs to be logged?
  - Student Info being adjusted?
	- Manual Hour Adjustments?
	- User Login/Logouts
	- Emplyee who clocked student in/out?

- Bulk Import Students Data
  - Import CSV



- Assumptions:
  - Bulk Import CSV - Data will be consistent and format will be provided
  - Frontend - Python Flask
  - Backend - MySQL Database
  - Access - on premise only
  - Open Souce All Code via GitHub
  - Support via GitHub Issues
  - Security is local to the app
    - No LDAP / Active Directory
