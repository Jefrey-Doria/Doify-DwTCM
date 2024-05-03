## **ACC-0013:** Authentication Testing - Empty Gender

> **Summary:** Verify that the Gender is not empty. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter valid first name, last name, and birthday | Verify that the other registration fields are populated correctly. |
| 2 | Leave the gender field empty | Verify that the system detects the empty gender field and displays an appropriate error message. |
| 3 | Enter a valid email and password | Verify that the email and password fields are populated correctly. |
| 4 | Click the "Create Account" button | Verify that the system does not allow the user to proceed with the registration process if the gender field is left empty. |
| 5 | Observe the error message | Verify that the system displays an error message indicating that the gender cannot be empty. |

**Post-conditions:**

- The system should not allow the user to complete the registration process with an empty gender field.
- An appropriate error message should be displayed to the user when the gender field is left empty.
- The user should not be able to proceed with the registration process until a valid gender is provided.
