## **ACC-0014:** Authentication Testing - Empty Contact Number

> **Summary:** Verify that the Contact Number is not empty. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter valid first name, last name, birthday, and gender | Verify that the other registration fields are populated correctly. |
| 2 | Leave the contact number field empty | Verify that the system detects the empty contact number field and displays an appropriate error message. |
| 3 | Enter a valid email and password | Verify that the email and password fields are populated correctly. |
| 4 | Click the "Create Account" button | Verify that the system does not allow the user to proceed with the registration process if the contact number field is left empty. |
| 5 | Observe the error message | Verify that the system displays an error message indicating that the contact number cannot be empty. |

**Post-conditions:**

- The system should not allow the user to complete the registration process with an empty contact number field.
- An appropriate error message should be displayed to the user when the contact number field is left empty.
- The user should not be able to proceed with the registration process until a valid contact number is provided.
