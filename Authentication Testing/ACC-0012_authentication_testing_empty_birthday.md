## **ACC-0012:** Authentication Testing - Empty Birthday

> **Summary:** Verify that the Birthday is not empty. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter valid first name and last name | Verify that the first name and last name fields are populated correctly. |
| 2 | Leave the birthday field empty | Verify that the system detects the empty birthday field and displays an appropriate error message. |
| 3 | Enter a valid email and password | Verify that the email and password fields are populated correctly. |
| 4 | Click the "Create Account" button | Verify that the system does not allow the user to proceed with the registration process if the birthday field is left empty. |
| 5 | Observe the error message | Verify that the system displays an error message indicating that the birthday cannot be empty. |

**Post-conditions:**

- The system should not allow the user to complete the registration process with an empty birthday field.
- An appropriate error message should be displayed to the user when the birthday field is left empty.
- The user should not be able to proceed with the registration process until a valid birthday is provided.
