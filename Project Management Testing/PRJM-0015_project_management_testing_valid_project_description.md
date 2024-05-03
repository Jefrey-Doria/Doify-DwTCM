## **PRJM-0015:** Project Management Testing - Valid Project Description  

> **Summary:** Verify that Project Description is displayed properly.  <br>

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
 | 7 | Remove the Project Description | Verify that the textfield is editable|
 | 8 | Add in a Project Description | Verify if the project description date is valid and doesn't exceed the 100 character limit |
 | 9 | Click the `save` button | Verify that it saves the changes|
 
**Post-conditions:**  

 - New Project Description is set
