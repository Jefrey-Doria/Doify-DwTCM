## **TAS-0012:** Task Creation Testing - Empty Task Description  

> **Summary:** Verify that Task Description is not empty.  <br>

**Preconditions:** Must have an account created and have created a Project

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Start the Application    | Verify that the login page is shown  | 
 |  2 | Login to your existing account    | Verify that you have an existing account created   | 
 |  3 | Examine the Home page     | Verify that you logged in and were redirected to the home page  |  
 |  4 | Click the Project on the left hand side| Verify that you see the contents of the project after clicking |
 |  5 | Click the "Create Task" button    | Verify that a modal shows with the requirements to create an app.  | 
 | 6 | Edit the textfields with your own data Except `task description` | Verify that you can make changes to the textfields |
  | 7 | Click the `create` button to create the task | Verify that the task is shown on the dashboard |

**Post-conditions:**  
   - Task is not created and an icon near task description is presented to indicate it is empty
