# scheduling
Message Handling: In this project we will be creating a whatsapp based chatbot where we will take the message from the user and create a scheduler to send the message to the person.


````
if("message"=="scheduling"):
 send to whatsapp service
else:
  reject it outright
````

2. Message Extraction: If the message is for scheduling, the chatbot will extract:
- Sender Name
- Receiver Name
- Message Content
- Sender Contact Number

## Technical Requirements :
1. Database :
  - Sender Name
  - Sender contact number 
  - Receiver Name
  - Receiver Contact Number
  - Message
  - Time left to send the message
  - Time to send the message at  

## User APIs:
- @Controller :
  - /api/v1/message
 
- @Service :
  - Synchronous LLM function to connect. Using any open source ai tool which will 
  - Storing in the database
    
## Challenges:
1. Whatsapp connection to the server: 
2. Mapping of the number to the persons name in the contact book and handling of multiple people of the same name.

v1.0.0:
1. Connecting whatsapp bot and making hello world
2. Connecting whatsapp bot to backend service
3. Sending messages from frontend to backend 

  
