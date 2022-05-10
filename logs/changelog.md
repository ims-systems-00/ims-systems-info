# V2.5.3 (-)

# V2.5.2 ( 11 May 2022 )
## Added
### CRM
- CRM licence management and access policy introduced

## Changed
### Dashboard
- linking to all the module from dashboard is implemented
- Code base restructured in both front end and back end
- Title truncation added in task manager analytics

## Removed
### Dev-lib
- Unnecessary licence management code cleared
- Backend infrastructure updated

## Fixed
### Miscellaneous
- Custom policy tool allocation problem

# V2.5.1 ( 16 April 2022 )
# Task manager updates 
- Multiple user assign feature has been added.
- Cross business unit task assignment feature has been added.
- Team priority feature has been added.

# V2.4.6 ( 5 April 2022 )
### Notification system
- Pagination Not working properly and read only notifications not working properly has been fixed

# V2.4.5 ( 4 April 2022 )
### Compliance
- ISO14001 introduced is available now

### Audit
- Risk scoring system in audit form has been added.

### Password invalidation
- Invalid attempts are set to number 5.
- Account lock for too many bad attempts is set to 1 hour.
- Verification email spamming protected

# V2.4.4 ( 24 March 2022 )
### Dashboard
- CRM analytics introduced
- Live customer analytics with values are available for most valued customer, Lowest value customer and average contract value
### CRM 
- Customer specific analytics introduced
- Customer logo Introduced in invoice form
- Invoice bug reports has been fixed.
- Interaction section introduced in customers.
- Invoice table validation introduced
- My customer filter available to see which customer a user is managing.
- My customer analytics introduced.
- Analytics for valuable customer, contract starting and ending this month added
- Live customer analytics with values are available for most valued customer, Lowest value customer and average contract value for customer managing by end user

# V2.4.3 ( 10 March 2022 )
### Developer updates
- Profile picture secure URL introduced
- CSV support for mobile app has been introduced
### Supplier management
- Contract value added in the supplier form
- Contract value analytics introduced in the dashboard

### Organisation profile
- From the dropdown of profile section organisation overview is available.
- Super user can amend organisation info, all other user will have a read view

# V2.4.2 ( 21 February 2022 )
### Table
- Search bars have been added.
  >**Searches are working for basic fields like reference title description name email etc.** 
### Bug reporting
- You can now directly raise a ticket to iMS Systems team from inside the system.
### Login
- Organisation selection is introduced in login form
### System entry point
- After v2.4.2 users have to go to domain `https://portals.imssystems.tech` to access ims systems
### Dashboard
- Todays date is showed on the top of the dashboard
### Compliance
- Clauses which are not amendable are also viewable. Users have read view for all the clauses
### Authentication
- Flow has been modified. Forgot password needs organisation name.
# V2.4.1 ( 14 February 2022 )
## Added
### Toolkit
- BS 9997 compliance toolkit is available in system
- Summary of each compliance tool is introduced to the system
### CRM
- CRM System has been introduced.
#### Features
- Customers Listing
- Customer Incident management.
- Send Invoices
## Profile
- New Profile picture upload has been moved to avatar section.
## Changed
### Supplier management 
- Managing supplier incidents is upgraded, comments and filters has been added.
### Document management 
- Modified date are inline with the version info in detail page.
### License management
- License allocation in business unit is not available anymore.
- Request includes only number of business units, number of users and the toolkits.
- No grant license feature is available in client end from the request table.
  >**All the licenses are managed from iMS Systems end.** 
- `Manage licenses` section for super admin only has toolkit license management.
- Anyone having a super admin or hos access can create user anytime as long as licenses are available in the organisation.
- A license is utilized when a user is created.
  >**Not when a new role is added in a function.** 
- A license is freed when a user is deleted or removed from the system.
  >**Not when the role is deleted from a function.** 
- Organisational overview table has been changed and relevant information are rearranged.
- Business units table indicates how many roles are being utilized in each function. But doesn't change the roles. These roles do not have any relationship with with licenses. These are just static information.
### Table
- Column resizing feature available. Tables can be expanded in horizontal direction.
### Admin theme
- Default theme has been set to red and mode is white.
### Date format
- 24 Hour date format across the system introduced
### Dashboard
- Greetings introduced in dashboard in place of integrated management system.
- Analytics changed finance and users duplication in business unit has been fixed.
  >**First business unit is prioritized and considered as the primary business unit.** 
## Fixed
### Buttons
- Updated buttons doesn't remain disabled when the data is being processed.
### Task manager
- Assigned date issue fixed.
# V2.3.3 (27 January 2022)
## Added
### Document management 
- Shared with notifications has been integrated 
### System defaults
- Issue date and scheduled date has been added in report interval
- Push notification is expandable to get the full view
## Fixed
### Document management 
- Version detail showing reverse order.
- Share with form not populating all the users
### Task manager
- Requested task needs to accept again
### Our iMS
- Business unit user table pagination need to click twice
### Date picker
- Invisible years and months of date select
### Calendar 
- Agenda title left aligned
### Dashboard
- Scrolling lags at the dashboard

# V2.3.2 ( 19 January 2022)
## Added
### Risk management  
- Risk management mitigated event notification added for users of the particular unit and super admin.
- Incident management resolved event notification added for super admin.
### Management Review
- Added scheduled time
### Compliance Toolkit
- Last updated by and date in toolkit table and detail page.
### Compliance Table
- Color code implemented in compliance table
## Changed
### Compliance Toolkit
- Select control and implement control feature implemented in ISO 20000, ISO 27001, ISO 9001, ISO 45001 
- Non compliant color have been changed to amber
## Fixed 
### CQC
- CQC KLOE table doesn't update real time
### Incident Management
- Incident form update button doesn't change with check mark status
### Risk Management
- Risk form update button doesn't change with check mark status
### Complaints
- Complaints form update button doesn't change with check mark status
### Significant Events
- Significant Events form update button doesn't change with check mark status
### Safeguardings
- Safeguardings form update button doesn't change with check mark status
### Whistleblowing
- Whistleblowing form update button doesn't change with check mark status
### Task Manager
- Notification doesn't redirect to the detail page
- Accept task not handled properly
# V2.3.1 ( 18 January 2022)
## Added
- Comment section in risk management section
- KPI delete button alert added.
### Tables
- New filter feature introduced across the system.
- New pagination mechanism introduced across the system.
## Changed
- compliance default tab is shifted to overview
### Compliance service
- ['Breaking'] New Data structure update in all the tools.
- ['Breaking] Evidence APIs and data structure updated.
## Removed
- removed the prefixes of all the attachments in detail page in all the modules
### Compliance service
- ['Breaking] Current Comments API has been removed for all the iso modules and new comments api is recomended to be used from now on.
- Tab views in all the modules is replaced with filter feature.
## Fixed 
- Task manager assign user feature not working.
- Task manager complete doesn't auto refresh the page
- Incident management attachment does not update.
- Default filter should be opened data in all modules.
- Email should be having user name in additional message.
- Attachment mutation problem in risk management, ci, task manager, incident management.
- Kpi objective amendment not working.
- Compliance percentage not updating properly in ISO 27002 and DSPT.
# V2.2.1 ( 31 December 2021)
## Changed
### Comment sections
- Comments thread design finalized. Text colors updated.
- Comments database migrated to activity database. So we can implement timeline feature in future.
## Added
### Activity api
- Activity api is avaible, able to handle activities quite in a performant way. Will act as a centralized service for all the moudles.
## Removed
### Comments API
- Comments api has been removed for all the modules.
# V2.1.5 ( 27 December 2021)
## Changed
### Comment sections
- Comments thread design initialized. Text colors updated.
## Added
### Development library 
- new scss designs created. `card-timeline` class available, new button mixin class available `btn-text`.
- use `card-timeline` only of there is a activity thread sections in the system and `btn-text` helps to render only text-based buttons.
# V2.1.4 ( 17 December 2021)
## Changed
### Comment sections
- Latest comments are at the top.
### Force reload 
- Table doen't refresh on update accross the system. (issue fixed)
# V2.1.3 ( 14 December 2021)
## Added
### Incident managment
- Assign the incident to an owner feature added. Owner can only be assigned once and can never be amended.(Pop up notification available)
- Comment section created.
### Email service 
- Service changed from Microsoft smpt to sendgrid api.
### System Infrusture
- Database collection renaming and synchronization in all the three environment.
- Deployment pipeline infrusture shifted to github actions from aws in the backend.
## Changed
###  Calendar
- Faulty query for event attendees as been fixed.
- Update of system event realted information automatically updates in calendar.
### Task manager
- Fixed Task reassign feature and working properly.