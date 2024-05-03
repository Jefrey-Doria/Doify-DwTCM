## **ACC-0003:** Authentication Testing - Existing Account  

> **Summary:** Verify that the system checks if the account already exists.  <br>

**Preconditions:** User has a registered account

Scenario 1 

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Navigate to the sign-up page | Verify that the sign-up page is displayed with the necessary input fields. |
| 2 | Enter a new unique username | Verify that the username field is populated correctly. |
| 3 | Enter an email address that is already registered in the system | Verify that the system detects the existing email address and displays an appropriate error message, indicating that the email is already in use. |
| 4 | Enter a valid password | Verify that the password field is populated correctly. |
| 5 | Click the "Create Account" button | Verify that the system does not allow the user to create an account with the existing email address and displays the error message. |

**Post-conditions:**

- The system should successfully prevent the creation of an account with an existing email address.
- Appropriate error messages should be displayed to the user when attempting to create an account with an existing email address.
- The user should not be able to create an account with an existing email address.
