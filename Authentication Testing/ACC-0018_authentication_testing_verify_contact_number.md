## **ACC-0018:** Authentication Testing - Verify Contact Number

> **Summary:** Verify that the Contact Number is unique. <br>

**Preconditions:** _None_

Scenario 1

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Enter a unique contact number | Verify that the system accepts the unique contact number and allows the user to proceed with the registration process. |
| 2 | Enter the same contact number again | Verify that the system detects the duplicate contact number and displays an appropriate error message. |
| 3 | Enter a different, unique contact number | Verify that the system accepts the new unique contact number and allows the user to proceed with the registration process. |

**Post-conditions:**

- The system should not allow the user to register with a contact number that is already in use.
- An appropriate error message should be displayed to the user when a duplicate contact number is entered.
- The user should be able to successfully register with a unique contact number.
