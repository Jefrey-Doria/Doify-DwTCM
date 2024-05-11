## **TAS-0003:** Task Creation Testing - Delete  

> **Summary:** Verify that Deleting a task feature is working successfully  <br>

**Preconditions:** 
- Must have an account created 
- have created a Project
- have created a task

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Start the Application    | Verify that the login page is shown  | 
 |  2 | Login to your existing account    | Verify that you have an existing account created   | 
 |  3 | Examine the Home page     | Verify that you logged in and were redirected to the home page  |  
 |  4 | Click the Project on the left hand side| Verify that you see the contents of the project after clicking |
 |  5 | Navigate to the `task` you want to delete    | Verify that a task is present if not create one.  | 
  | 6 | Click the `edit` button to be able to edit the task | Verify that you can click the edit button |
   | 7 | Click the `delete` button | Verify that you have deleted the task and the task does not exist anymore |

**Post-conditions:**  
   - The task gets deleted

