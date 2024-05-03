## **PRJC-0006:** Project Creation Testing - Valid Project Description  

> **Summary:** Verify that the project description is displayed properly  <br>

**Preconditions:** Must have an account created

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Start the Application    | Verify that the login page is shown  | 
 |  2 | Login to your existing account    | Verify that you have an existing account created   | 
 |  3 | Examine the Home page     | Verify that you logged in and were redirected to the home page  |  
 |  4 | Click the Icon with the `File with the "+" ` button | Verify that you see the the icon on the My Projects section |
 |  5 | Get presented with the add project modal    | Verify that the add project modal is shown  | 
 | 6 | Edit the textfields with your own data | Verify that you can make changes to the textfields |
 | 7 | Edit the `Project Description` | Verify that you can check if the project description is accepted|
 
**Post-conditions:**  

 - Add Project Modal Is Shown
 - Text Fields are editable
 - Error is shown when Project Description exceeds a 100 characters
