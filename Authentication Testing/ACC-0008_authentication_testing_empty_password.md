## **ACC-0008:** Authentication Testing - Empty Password

> **Summary:** Verify that the password is not empty. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter a valid username | Verify that the username field is populated correctly. |
| 2 | Leave the password field empty | Verify that the system detects the empty password field and displays an appropriate error message. |
| 3 | Click the "Login" button | Verify that the login button is clickable and responds to the user's action. |
| 4 | Observe the error message | Verify that the system displays an error message indicating that the password cannot be empty. |

**Post-conditions:**

- The system should not allow the user to log in with an empty password.
- An appropriate error message should be displayed to the user when the password field is left empty.
- The user should not be able to proceed with the login process if the password is empty.
