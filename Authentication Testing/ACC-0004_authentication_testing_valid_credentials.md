## **ACC-0004:** Authentication Testing - Valid Credentials

> **Summary:** Verify that the credentials of the user is valid.

**Preconditions:** _User has a registered account_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter a valid username | Verify that the username field is populated correctly. |
| 2 | Enter a valid password | Verify that the password field is populated correctly. |
| 3 | Click the "Login" button | Verify that the login button is clickable and responds to the user's action. |
| 4 | Observe the page transition | Verify that the user is successfully logged in and redirected to the appropriate page (e.g., dashboard, home page). |

**Post-conditions:**
- The user should be able to log in successfully with valid credentials.
- The user should be redirected to the appropriate page after a successful login.
- The system should not allow the user to log in with invalid credentials.
