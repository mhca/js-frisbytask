# js-frisbytask
Frisby tasks

# High level test cases:

* Smoke tests

**General:
Verify that a valid user can be log in successfully
Verify that a valid user can be log off successfully
Verify that "my work" tab is selected by default after login the app

**Backlogs:
Verify that all product items are displayed inside Backlogs

**Administration:
Verify that "My settings" section is displayed successfully
Verify that "users" section is displayed successfully when clicking Administration>Users
Verify that "Teams" section is displayed successfully when clicking Administration>Teams
Verify that "Access rights" section is displayed successfully when clicking Administration>Access rights
Verify that "Account settings" section is displayed successfully when clicking Administration>Account settings
Verify that "Database export" section is displayed successfully when clicking Administration>Database export

*Sanity tests
Verify that enabled users "are displayed in "Users" section
Verify that disabled users "are displayed in "Users" section


*CRUD tests

**Create:
Verify that a new product is created sucessfully
Verify that a new project is created sucessfully inside a product
Verify that a new iteration is created sucessfully inside a project
Verify that a new story is created sucessfully
Verify that a new board is created sucessfully
Verify that a new team is created sucessfully
Verify that a new board is created sucessfully

**Update:
Verify that the user password can be changed sucessfully
Verify the basic user information can be edited
Verify the basic user settings can be edited

**Delete:
Verify that a user can be deleted successfully

**Negative tests
Verify that a new user is not created without required data

*Boundary tests
Verify a product sohuld be created with a large name

*Security tests
