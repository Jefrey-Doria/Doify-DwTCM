## **ACC-0006:** Authentication Testing - Invalid Password

> **Summary:** Verify that if Password is invalid, it shows the Password is invalid.

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter a valid username | Verify that the username field is populated correctly. |
| 2 | Enter an invalid password | Verify that the system detects the invalid password and displays an appropriate error message. |
| 3 | Click the "Login" button | Verify that the login button is clickable and responds to the user's action. |
| 4 | Observe the error message | Verify that the system displays an error message indicating that the password is invalid. |

**Post-conditions:**

- The system should not allow the user to log in with an invalid password.
- An appropriate error message should be displayed to the user when an invalid password is entered.
- The user should not be able to proceed with the login process if the password is invalid.
