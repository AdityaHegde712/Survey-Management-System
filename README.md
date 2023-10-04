# Survey Management Application
### Functional Features:
#### Daily Entry Module:
- Users can add, update pay status, or delete daily survey work entries.
- Fields include Date, Party name, location/address, Feed location as survey number, type of work, bill, and payment status (paid or unpaid).
- Adding entry will have a single button
- Updating pay status will toggle the status between paid and unpaid for the entry number
- Deleting entry will delete the entered entry number from the table. 

#### Team Management Module:
- Users can create and delete teams.
- A head of each team can be specified during creation
- Individual employees can be added to teams.
- For team deletion, only the team leader needs to be specified.
- If a selected member is already in a different team, a warning message will be displayed, and depending on the user’s choice, the member will be removed from the previous team and added to the new team, or the operation will be aborted.

#### Work Type Module:
- Users can add or delete work types. Name needs to be entered.
- If the name does not exist, a warning message will be displayed.

#### Employee Control Module:
- Users can add or remove employees.
- Name and phone number required for both operations.

#### Data Viewing Module:
- The most powerful module in this application.
- Users can view entries and costs in various ways, including:
  - Viewing all data
  - Viewing data by date
  - Viewing data by party name
- Users can also choose to view all existing workers, teams, and work types.

#### User Authentication Module:
- User login and authentication system.
- Access is restricted to three predefined users as per the agreed upon number. Subject to change.
- Any updates would require change in database schema, and need developer’s attention.
- (Depending on requirement): Additional feature to add/remove admin users by one superuser may be added.


### Non-Functional Features:
#### Security:
- Data should be securely stored and protected against unauthorized access.
- User authentication and authorization should be robust.

#### User-Friendly GUI:
- The graphical user interface (GUI) should be intuitive and easy to use.
- Proper layout and design for efficient data entry and retrieval.

#### Performance:
- The application should perform efficiently, even with a large volume of data.
- Database queries should be optimized.

#### Compatibility:
- Ensure compatibility with common web browsers and devices.


### Usage Directions:
Instructions for usage will be provided after the application's design and features are finalized.

**Note: This is a work in progress.**
