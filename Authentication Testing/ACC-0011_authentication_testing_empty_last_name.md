## **ACC-0011:** Authentication Testing - Empty Last Name

> **Summary:** Verify that the Last Name is not empty. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter a valid first name | Verify that the first name field is populated correctly. |
| 2 | Leave the last name field empty | Verify that the system detects the empty last name field and displays an appropriate error message. |
| 3 | Enter a valid email and password | Verify that the email and password fields are populated correctly. |
| 4 | Click the "Create Account" button | Verify that the system does not allow the user to proceed with the registration process if the last name field is left empty. |
| 5 | Observe the error message | Verify that the system displays an error message indicating that the last name cannot be empty. |

**Post-conditions:**

- The system should not allow the user to complete the registration process with an empty last name field.
- An appropriate error message should be displayed to the user when the last name field is left empty.
- The user should not be able to proceed with the registration process until a valid last name is provided.
