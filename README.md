Project Overview
This project contains user stories and acceptance criteria for testing user account management functionalities on the Akakce.com website, which are tested using Selenium in IntelliJ IDEA. Each user story defines the interactions users will have with the website and the acceptance criteria for verifying the correctness of those interactions.

Table of Contents
Overview
User Stories
US_101 - Create User Account
US_102 - Account Validation Check
US_103 - Log Out
US_104 - Log In
US_105 - Order List Check
US_106 - Message Inbox Check
US_107 - Delete Account
Test Environment and Requirements
Negative Scenarios
Overview
This project is designed to test user account management features on the Akakce.com site. The user stories define various website functionalities and verify that they work correctly. Acceptance criteria and preconditions support these user stories by specifying the conditions under which each function should be tested.

User Stories
US_101 - Create User Account
As a user, I should be able to create an account on Akakce.com so that I can have a personalized shopping experience.

Description: The user can create an account by providing personal information and then personalize their profile.

Acceptance Criteria:

The user must enter details like first name, last name, email, password, gender, and birthdate to create the account.
Upon providing correct information, the user should be redirected to the account validation page.
Preconditions:

The browser (Chrome, Safari, or Firefox) must be installed and started.
The test environment must have internet access.
The password must be at least 8 characters long and contain both uppercase and lowercase letters as well as numbers.
US_102 - Account Validation Check
As a user, I should be able to see my name in the profile section at the top right corner once logged in, ensuring a secure shopping experience.

Description: After logging in successfully, the user's name should be displayed in the profile section at the top right.

Acceptance Criteria:

After logging in with valid credentials, the user’s name should appear in the top-right corner of the page.
The displayed name must match the name provided during account creation.
Preconditions:

The user must have successfully created an account.
US_103 - Log Out
As a user, I should be able to log out from my account on Akakce.com to ensure a secure experience.

Description: The user should be able to log out after signing in for better security.

Acceptance Criteria:

The user must be able to log out from their account.
After logging out, the user should be redirected to the login page.
Preconditions:

The user must be logged into the website.
US_104 - Log In
As a user, I should be able to log in to Akakce.com so that I don't have to enter my personal preferences repeatedly.

Description: After providing the correct login information, the user can access the site and start their shopping experience.

Acceptance Criteria:

If the user provides correct credentials, the login should be successful, and the user should be able to access their account.
Preconditions:

The user’s account (email address and password) must be successfully created and validated.
US_105 - Order List Check
As a user, I should be able to view my order history after logging in, so I can ensure that I am not making any untracked purchases.

Description: After logging in, the user can view their order history.

Acceptance Criteria:

After logging in, the user should be redirected to the order list page.
If the order list is empty, an appropriate message should be displayed.
Preconditions:

The user’s account (email address and password) must be successfully created and validated.
The user must be logged in to check the order list.
US_106 - Message Inbox Check
As a user, I should be able to check my message inbox after logging in to ensure I don't miss out on any special campaigns or notifications.

Description: After logging in, the user will be redirected to the message inbox and can view notifications about campaigns.

Acceptance Criteria:

After logging in, the user should be directed to the message inbox.
If the message inbox is empty, an appropriate message should be displayed.
Preconditions:

The user’s account (email address and password) must be successfully created and validated.
The user must be logged in to check the message inbox.
US_107 - Delete Account
As a user, I should be able to delete my account to ensure my personal data is protected.

Description: The user can delete their account to protect their personal data.

Acceptance Criteria:

After logging in, the user should be able to delete their account from the system.
When the correct password is entered during the account deletion process, the account should be successfully deleted.
Preconditions:

The user’s account (email address and password) must be successfully created and validated.
The user must be logged into the account to delete it.
Test Environment and Requirements
Test Environment: https://www.akakce.com

Browser Requirements:

Chrome, Safari, or Firefox
Additionally, a user account must be created and tested with valid data.

Negative Scenarios
Negative scenarios test the system's response to unexpected user behavior. These scenarios are important for ensuring a more robust and reliable user experience.

Example Negative Scenarios:

When the user attempts to log in with an empty email and password, an error message should be shown.
When invalid payment information is entered, an appropriate error message should be displayed.
This README document provides a comprehensive guide for testing user account management features on Akakce.com. Each user story is thoroughly defined, with acceptance criteria and preconditions for testing.
