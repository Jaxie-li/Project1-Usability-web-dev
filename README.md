# Project 1 - Usability Enhanced E2EE Support System website
Design and implement a comprehensive E2EE (End-to-End Encryption) web application using Python, html, css and Django. The system serves as a robust platform for University students to securely communicate, share academic experiences, and access a centralized knowledge repository. Features of the application include user authentication, secure messaging, a discussion board, and a resource repository akin to platforms like Canvas. 

## Brief function introduce:
**User Authentication**: Facilitated seamless user registration and login while ensuring the secure storage and transmission of passwords.  

**Messaging System**: Developed a secure messaging tool that allows users to view their friend list and send encrypted messages, maintaining user privacy and data integrity.  

**Discussion Forum**: Incorporated an interactive discussion board allowing users to engage in academic discussions, seek clarifications, and upload files to support their points.  

**Resource & Repository**: Created a central hub where students can upload, discover, and manage academic resources, course sheets, and other pertinent learning materials.

## Reports and the video
Please visit the link below, the specific report and demo video. 
https://drive.google.com/drive/folders/1LwGH1Czkwg7UoXwzEdXIezmR-DxDgJb-?usp=sharing


## Requirements
The requirements are stored in  
```{./requirements.txt}```  

Run the following command to install:  
```{pip install -r requirements.txt}```

## How this work
Migrate the database please use:```{python3 manage.py migrate}```
Run the server with the Django: ```{python3 manage.py runserver}```  

```{python3 manage.py runserver_plus --cert cert.pem --key key.pem}```
(run the command when you want to have the web security, but you don't have the certificate)

## Superuser function
Some power for admin:
- add/delete user
- create a realtionship with friend A and B
- mute user in the discussion forum, chat, resource and repository
- But you cannot see all of the messages and password as plaintext. 

If you want, please create the spueruser use this command  

```{python3 manage.py createsuperuser}```

PS: Thank you for your respect and understanding, please respect my intellectual property rights when reviweing this. Do not copy, distribute or use it for purpose other thanassessment. 

