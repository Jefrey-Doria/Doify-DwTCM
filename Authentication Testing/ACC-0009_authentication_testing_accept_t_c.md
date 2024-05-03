## **ACC-0009:** Authentication Testing - Accept T&C

> **Summary:** Verify that the user accepts the Terms and Conditions.

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Navigate to the sign-up page | Verify that the sign-up page is displayed with the necessary input fields and a checkbox or button for accepting the Terms and Conditions. |
| 2 | Enter valid registration details | Verify that the user can enter a valid username, email, and password. |
| 3 | Locate the Terms and Conditions checkbox or button | Verify that the Terms and Conditions checkbox or button is present and accessible. |
| 4 | Check the Terms and Conditions checkbox or click the button | Verify that the user can successfully select or click the Terms and Conditions checkbox or button. |
| 5 | Click the "Create Account" button | Verify that the user can only proceed with the account creation process after accepting the Terms and Conditions. |

**Post-conditions:**

- The user should not be able to create an account without accepting the Terms and Conditions.
- The system should prevent the user from completing the registration process until the Terms and Conditions are accepted.
- The user's acceptance of the Terms and Conditions should be recorded or acknowledged by the system.
