## **ACC-0005:** Authentication Testing - Invalid Username

> **Summary:** Verify that if Username is invalid, it shows the username is invalid.

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter an invalid username | Verify that the system detects the invalid username and displays an appropriate error message. |
| 2 | Enter a valid password | Verify that the password field is populated correctly. |
| 3 | Click the "Login" button | Verify that the login button is clickable and responds to the user's action. |
| 4 | Observe the error message | Verify that the system displays an error message indicating that the username is invalid. |

**Post-conditions:**

- The system should not allow the user to log in with an invalid username.
- An appropriate error message should be displayed to the user when an invalid username is entered.
- The user should not be able to proceed with the login process if the username is invalid.
