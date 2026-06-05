## Our Solution

We designed and implemented an IT Support Copilot solution using Microsoft Copilot Studio.  

The agent helps users submit IT support requests in a structured way by collecting essential information such as name, department, and issue type.  

It then displays a summary of the request to ensure all details are complete.




## How It Works

The solution uses a topic called "Submit a request" which is triggered when users type phrases like "Submit a request" or "I need IT support".

The agent performs the following steps:
1. Asks for the user's name  
2. Asks for the department  
3. Asks for the issue type  
4. Stores each response in variables  
5. Displays a structured summary



<img width="894" height="567" alt="image" src="https://github.com/user-attachments/assets/ac654e7a-2a6f-4831-a3bd-2db91d4bf89e" />


<img width="1358" height="632" alt="image" src="https://github.com/user-attachments/assets/1cf6c53f-a7c1-475c-8a57-129ba0550622" />



<img width="1358" height="633" alt="image" src="https://github.com/user-attachments/assets/850ef39a-b471-4556-92e6-568748cc5685" />


<img width="1355" height="640" alt="image" src="https://github.com/user-attachments/assets/2ba7fc38-d41b-466e-b9fd-c1772e6b0a8e" />




### Test Case: Normal Flow
Input:
- Name: Mohammed  
- Department: IT  
- Issue Type: Network  

Expected Result:
- Agent displays correct summary  

Actual Result:
Passed

<img width="1360" height="625" alt="image" src="https://github.com/user-attachments/assets/b106b438-85b2-41c4-8725-030c1b57b932" />


<img width="1362" height="632" alt="image" src="https://github.com/user-attachments/assets/84027a30-9125-4af9-9ec0-b4102ee68f2b" />


<img width="1361" height="634" alt="image" src="https://github.com/user-attachments/assets/67f6d3c7-8f43-4508-b458-dd49112fead8" />


<img width="1365" height="630" alt="image" src="https://github.com/user-attachments/assets/6b8b13c5-c86f-477b-ab49-396e2edf4d4f" />


<img width="1359" height="635" alt="image" src="https://github.com/user-attachments/assets/e3bbf8df-ebbf-4fc0-b01a-c4f9630145ec" />


<img width="1351" height="634" alt="image" src="https://github.com/user-attachments/assets/40687919-858c-4633-983c-6e86315103e4" />

<img width="1365" height="629" alt="image" src="https://github.com/user-attachments/assets/42b2cf54-94ef-4939-9398-0d89b9fb14ef" />



## Variables Used

The agent uses variables to store user input:

- userName: Stores the user's name  
- department: Stores the user's department  
- issueType: Stores the type of issue  

These variables are used to generate the summary message.


## Conclusion

The solution successfully ensures that IT requests are structured, complete, and easy for the IT team to process.  

It improves efficiency and user experience.
