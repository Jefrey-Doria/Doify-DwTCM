## **ACC-0010:** Authentication Testing - Empty First Name

> **Summary:** Verify that the First Name is not empty. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Leave the first name field empty | Verify that the system detects the empty first name field and displays an appropriate error message. |
| 2 | Enter a valid last name, email, and password | Verify that the other registration fields are populated correctly. |
| 3 | Click the "Create Account" button | Verify that the system does not allow the user to proceed with the registration process if the first name field is left empty. |
| 4 | Observe the error message | Verify that the system displays an error message indicating that the first name cannot be empty. |

**Post-conditions:**

- The system should not allow the user to complete the registration process with an empty first name field.
- An appropriate error message should be displayed to the user when the first name field is left empty.
- The user should not be able to proceed with the registration process until a valid first name is provided.
