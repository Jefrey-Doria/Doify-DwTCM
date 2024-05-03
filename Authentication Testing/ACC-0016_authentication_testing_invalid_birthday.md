## **ACC-0016:** Authentication Testing - Invalid Birthday

> **Summary:** Verify that the Birthday is valid. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter a valid first name, last name, and other registration details | Verify that the other registration fields are populated correctly. |
| 2 | Enter an invalid birthday (e.g., a future date, an impossible date) | Verify that the system detects the invalid birthday and displays an appropriate error message. |
| 3 | Click the "Create Account" button | Verify that the system does not allow the user to proceed with the registration process if the birthday is invalid. |
| 4 | Observe the error message | Verify that the system displays an error message indicating that the birthday is invalid. |

**Post-conditions:**

- The system should not allow the user to complete the registration process with an invalid birthday.
- An appropriate error message should be displayed to the user when an invalid birthday is entered.
- The user should not be able to proceed with the registration process until a valid birthday is provided.
