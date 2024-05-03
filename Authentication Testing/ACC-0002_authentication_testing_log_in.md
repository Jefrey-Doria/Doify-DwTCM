## **ACC-0002:** Authentication Testing - Log in  

> **Summary:** Verify That a user can log into their existing account.  <br>

**Preconditions:** User has a registered account 

Scenario 1: Successful Login  

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the Login page     | Verify that the login page is displayed and has the necessary input fields for username and password.   | 
 |  2 | Enter a valid username and password  | Verify that the username and password fields are populated correctly  |  
 |  3 | Click the `Login button`     | Verify that the login button is clickable and responds to the user's action.   |  
 |  4 | Observe the page transition     | Verify that the user is redirected to the user's dashboard or home page after successful login.   |  
 |  5 | Verify the user's profile information     | Ensure that the user's profile information (e.g., name, email, avatar) is displayed correctly on the dashboard or home page.   |  

Scenario 2: Unsuccessful Login

Scenario 2: Unsuccessful Login

| \# | Step | Expected Behavior |
|----|------|-------------------|
| 1 | Navigate to the login page | Verify that the login page is displayed and has the necessary input fields for username and password. |
| 2 | Enter an invalid username in the username field | Verify that the username field is populated correctly. |
| 3 | Enter an invalid password in the password field | Verify that the password field is populated correctly. |
| 4 | Click the `Login` button | Verify that the login button is clickable and responds to the user's action. |
| 5 | Observe the error message | Verify that an appropriate error message is displayed, indicating that the login credentials are invalid. |


**Post-conditions:**  

 - User should be redirected
 - User's profile information should be displayed correctly on the dashboard or home page.
 - The application should handle invalid login attempts and display appropriate error messages.



