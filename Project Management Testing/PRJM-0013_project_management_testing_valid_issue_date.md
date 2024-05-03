## **PRJM-0013:** Project Management Testing - Valid Issue Date  

> **Summary:** Verify that Issue Date is valid  <br>

**Preconditions:** Must have an account created and have created an existing project

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Start the Application    | Verify that the login page is shown  | 
 |  2 | Login to your existing account    | Verify that you have an existing account created   | 
 |  3 | Examine the Home page     | Verify that you logged in and were redirected to the home page  |  
 |  4 | Click the Icon with the `3 dots` button beside the project you would like to edit| Verify that you see the the icon on the My Projects section |
 |  5 | Get presented with the project modal  | Verify that the  project modal is shown  | 
 | 6 | Edit the textfields with your own data | Verify that you can make changes to the textfields |
 | 7 | Remove the Issue Date | Verify that the textfield is editable|
 | 8 | Add in a new Issue Date | Verify if the issue date is valid |
 | 9 | Click the `save` button | Verify that it gives an error when editing a project without a adding an Client Name|
 
**Post-conditions:**  

 - Error is shown when Issue date is invalid
