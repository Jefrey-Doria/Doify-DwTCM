## **TAS-0006:** Task Creation Testing - Valid Amount  

> **Summary:** Verify that the amount is valid  <br>

**Preconditions:** Must have an account created and have created a Project

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Start the Application    | Verify that the login page is shown  | 
 |  2 | Login to your existing account    | Verify that you have an existing account created   | 
 |  3 | Examine the Home page     | Verify that you logged in and were redirected to the home page  |  
 |  4 | Click the Project on the left hand side| Verify that you see the contents of the project after clicking |
 |  5 | Click the "Create Task" button    | Verify that a modal shows with the requirements to create a task | 
 | 6 | Edit the textfields with your own data | Verify that you can make changes to the textfields |
  | 7 | Add in data into  the Amount section of the modal | Verify that you can make changes to the textfields |
  | 8 | Click the `create` button to create the task | Verify that the `amount` value would be accepted |

**Post-conditions:**  
   - A task is created with a valid amount
OR
- A task is rejected after inputting an invalid amount
