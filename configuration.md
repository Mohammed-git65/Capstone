# Configuration

## Overview
This document describes the technical configuration and setup of the IT Support Solution built using Microsoft Copilot Studio.

The solution is designed to collect user inputs, store them in variables, and display a structured summary for IT support requests.

---

## Platform Setup

The solution was built using the following:

- **Platform:** Microsoft Copilot Studio  
- **Agent Name:** IT Support Solution  
- **Topic:** Submit a request  

The agent provides a guided conversational interface for submitting IT requests.

---

## Topic Configuration

A topic named **"Submit a request"** was created to manage the interaction flow.

### Trigger Phrases
The topic is triggered using the following phrases:

- Submit a request  
- I need IT support  
- Report an issue  

> These phrases initiate the conversation flow.

<img width="894" height="567" alt="image" src="https://github.com/user-attachments/assets/ac654e7a-2a6f-4831-a3bd-2db91d4bf89e" />

---

## Conversation Flow

The agent follows a structured flow:






### Flow Steps:
1. User triggers the topic  
2. Agent asks for name  
3. Agent asks for department  
4. Agent asks for issue type  
5. Agent displays a summary  





<img width="1358" height="633" alt="image" src="https://github.com/user-attachments/assets/850ef39a-b471-4556-92e6-568748cc5685" />


<img width="1355" height="640" alt="image" src="https://github.com/user-attachments/assets/2ba7fc38-d41b-466e-b9fd-c1772e6b0a8e" />

---

## Question Nodes Setup

### 1. Name Input
- **Question:** What is your name?  
- **Response Type:** Text  
- **Variable:** `userName`  

<img width="1358" height="632" alt="image" src="https://github.com/user-attachments/assets/1cf6c53f-a7c1-475c-8a57-129ba0550622" />

---

### 2. Department Input
- **Question:** Which department are you in?  
- **Response Type:** Text  
- **Variable:** `department`  

<img width="1358" height="633" alt="image" src="https://github.com/user-attachments/assets/850ef39a-b471-4556-92e6-568748cc5685" />

---

### 3. Issue Type Input
- **Question:** What type of issue are you experiencing?  
- **Response Type:** Multiple choice  

**Options:**
- Hardware  
- Software  
- Network  
- Access/Account  

- **Variable:** `issueType`  

<img width="1355" height="640" alt="image" src="https://github.com/user-attachments/assets/2ba7fc38-d41b-466e-b9fd-c1772e6b0a8e" />

---


## Summary Message Configuration

The summary message is configured using variables:


Here is the summary of your request:
Name: {userName}
Department: {department}
Issue Type: {issueType}

<img width="1351" height="634" alt="image" src="https://github.com/user-attachments/assets/40687919-858c-4633-983c-6e86315103e4" />

---

## Testing Configuration

The solution was tested using the **Test Canvas** in Copilot Studio.

### Test Steps:
1. Enter trigger phrase (e.g., "Submit a request")  
2. Provide inputs (name, department, issue type)  
3. Verify summary output  

<img width="1360" height="625" alt="image" src="https://github.com/user-attachments/assets/b106b438-85b2-41c4-8725-030c1b57b932" />


<img width="1362" height="632" alt="image" src="https://github.com/user-attachments/assets/84027a30-9125-4af9-9ec0-b4102ee68f2b" />


<img width="1361" height="634" alt="image" src="https://github.com/user-attachments/assets/67f6d3c7-8f43-4508-b458-dd49112fead8" />

---

## Conclusion

The configuration ensures:
- Structured data collection  
- Proper variable usage  
- Clear and consistent output  

This setup improves efficiency and ensures all IT support requests are complete and ready for processing.

