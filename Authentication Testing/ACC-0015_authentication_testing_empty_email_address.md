## **ACC-0015:** Authentication Testing - Empty Email Address

> **Summary:** Verify that the Email Address is not empty. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter valid first name, last name, birthday, gender, and contact number | Verify that the other registration fields are populated correctly. |
| 2 | Leave the email address field empty | Verify that the system detects the empty email address field and displays an appropriate error message. |
| 3 | Enter a valid password | Verify that the password field is populated correctly. |
| 4 | Click the "Create Account" button | Verify that the system does not allow the user to proceed with the registration process if the email address field is left empty. |
| 5 | Observe the error message | Verify that the system displays an error message indicating that the email address cannot be empty. |

**Post-conditions:**

- The system should not allow the user to complete the registration process with an empty email address field.
- An appropriate error message should be displayed to the user when the email address field is left empty.
- The user should not be able to proceed with the registration process until a valid email address is provided.
