## **ACC-0017:** Authentication Testing - Verify Username

> **Summary:** Verify that the Username is unique. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter a unique username | Verify that the system accepts the unique username and allows the user to proceed with the registration process. |
| 2 | Enter the same username again | Verify that the system detects the duplicate username and displays an appropriate error message. |
| 3 | Enter a different, unique username | Verify that the system accepts the new unique username and allows the user to proceed with the registration process. |

**Post-conditions:**

- The system should not allow the user to register with a username that is already in use.
- An appropriate error message should be displayed to the user when a duplicate username is entered.
- The user should be able to successfully register with a unique username.
