## **PRJC-0005:** Project Creation Testing - Valid Issue Date  

> **Summary:** Verify that the date is valid  <br>

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
 | 7 | Edit the `Issue Date` | Verify that it gives an error when creating a project with an invalid `Issue Date`|
 
**Post-conditions:**  

 - Add Project Modal Is Shown
 - Text Fields are editable
 - Error is shown when Issue Date is invalid
