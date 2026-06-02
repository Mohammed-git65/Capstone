# Configuration

## Overview  
This section describes our technical setup and configuration of the IT Support Solution built by Group 2 using Microsoft Copilot Studio.


## Environment Setup  

<img width="1358" height="630" alt="image" src="https://github.com/user-attachments/assets/60d6b4ae-3865-471a-8a09-123c50ad03c5" />


- Platform used: Microsoft Copilot Studio  
- Agent name: IT Support Agent  
- Topic created: Submit a request  

---

## Topic Configuration  
**[Screenshot here: topic flow diagram showing all nodes]**

The topic "Submit a request" was created to handle IT support requests.  

Trigger phrases configured include:  
- Submit a request  
- I need IT support  
- Report an issue  

These phrases start the conversation flow.

---

## Question Nodes Setup  

### 1. Name Input  
**[Screenshot here: “What is your name?” node showing Text + variable userName]**

- Question: What is your name?  
- Response type: Text  
- Variable: `userName`  

---

### 2. Department Input  
**[Screenshot here: department question node showing Text + variable department]**

- Question: Which department are you in?  
- Response type: Text  
- Variable: `department`  

---

### 3. Issue Type Input  
**[Screenshot here: issue type node showing multiple choice options]**

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
**[Screenshot here: summary message with variables inserted]**

The agent uses stored variables to generate a structured summary:

Example:

Here is the summary of your request:  
- Name: {userName}  
- Department: {department}  
- Issue Type: {issueType}  

---

## Variable Usage  
**[Screenshot here: variable picker showing inserted variables]**

Variables are used to store user inputs and reuse them later in the conversation.

Configured variables:
- userName  
- department  
- issueType  

---

## Testing Configuration  
**[Screenshot here: test canvas panel]**

The solution was tested using the Test Canvas in Copilot Studio.  

Steps:
1. Trigger the topic using "Submit a request"  
2. Provide inputs  
3. Verify summary output  

---

## Deployment  
**[Optional Screenshot here: publish button]**

- The agent was published using the "Publish" option in Copilot Studio  
- This makes the latest version available for use  

---

## Conclusion  
The configuration ensures that the agent collects user input correctly, stores it in variables, and presents a structured summary. The setup provides a reliable and consistent IT request submission process.
``






<img width="1361" height="634" alt="image" src="https://github.com/user-attachments/assets/e8cb8d72-df4a-4891-8565-6bb5663bc347" />


<img width="1358" height="637" alt="image" src="https://github.com/user-attachments/assets/d044a324-6bdd-4642-b743-714ba302af30" />
