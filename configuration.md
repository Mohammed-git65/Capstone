# Configuration

## Overview  
This section describes our technical setup and configuration of the IT Support Solution built by Group 2 using Microsoft Copilot Studio.


## Environment Setup  

<img width="1361" height="634" alt="image" src="https://github.com/user-attachments/assets/7de1a028-c433-4c61-9549-13a6c1ee7dc3" />


<img width="1358" height="630" alt="image" src="https://github.com/user-attachments/assets/60d6b4ae-3865-471a-8a09-123c50ad03c5" />




- Platform used: Microsoft Copilot Studio  
- Agent name: Group 2 IT Solution  
 

---

## Topic Configuration  


- Topic created: Submit a request
  
<img width="894" height="567" alt="image" src="https://github.com/user-attachments/assets/ac654e7a-2a6f-4831-a3bd-2db91d4bf89e" />


<img width="1358" height="632" alt="image" src="https://github.com/user-attachments/assets/1cf6c53f-a7c1-475c-8a57-129ba0550622" />



<img width="1358" height="633" alt="image" src="https://github.com/user-attachments/assets/850ef39a-b471-4556-92e6-568748cc5685" />


<img width="1355" height="640" alt="image" src="https://github.com/user-attachments/assets/2ba7fc38-d41b-466e-b9fd-c1772e6b0a8e" />



The topic "Submit a request" was created to handle IT support requests.  

Trigger phrases configured include:  
- Submit a request  
- I need IT support  
- Report an issue  


These phrases start the conversation flow.

<img width="894" height="567" alt="image" src="https://github.com/user-attachments/assets/ac654e7a-2a6f-4831-a3bd-2db91d4bf89e" />

---

## Question Nodes Setup  

### 1. Name Input  

<img width="1358" height="632" alt="image" src="https://github.com/user-attachments/assets/1cf6c53f-a7c1-475c-8a57-129ba0550622" />

- Question: What is your name?  
- Response type  
- Variable: `userName`  

---

### 2. Department Input  



- Question: Which department are you in?  
- Response type
- Variable: `department`  

---

### 3. Issue Type Input  

<img width="1358" height="633" alt="image" src="https://github.com/user-attachments/assets/850ef39a-b471-4556-92e6-568748cc5685" />

- Question: What type of issue are you experiencing?  
- Response type: Multiple choice  
- Options:
  - Hardware  
  - Software  
  - Network  
  - Access/Account  
- Variable: `issueType`  

---

## Message Configuration (Summary Output)  

<img width="1351" height="634" alt="image" src="https://github.com/user-attachments/assets/40687919-858c-4633-983c-6e86315103e4" />

Our agent uses stored variables to generate a structured summary:

Example:

Here is the summary of your request:  
- Name: {userName}  
- Department: {department}  
- Issue Type: {issueType}  

---

## Testing Configuration  

<img width="1360" height="625" alt="image" src="https://github.com/user-attachments/assets/b106b438-85b2-41c4-8725-030c1b57b932" />


<img width="1362" height="632" alt="image" src="https://github.com/user-attachments/assets/84027a30-9125-4af9-9ec0-b4102ee68f2b" />


<img width="1361" height="634" alt="image" src="https://github.com/user-attachments/assets/67f6d3c7-8f43-4508-b458-dd49112fead8" />

The solution was tested using the Test Canvas in Copilot Studio.  

Steps:
1. Trigger the topic using "Submit a request"  
2. Provide inputs  
3. Verify summary output  

---

## Conclusion  
The configuration ensures that the agent collects user input correctly, stores it in variables, and presents a structured summary. The setup provides a reliable and consistent IT request submission process.
