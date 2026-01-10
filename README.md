<img width="1384" height="3684" alt="image" src="https://github.com/user-attachments/assets/c622b62e-52d3-4c0d-af7d-12526afd4554" />[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/sF7T-ior)

UNIVERSITY OF MALAYSIA TERENGGANU 

 

CSF3023 – PEMIKIRAN SISTEM DAN LOGIK 

 

GROUP ASSIGNMENT SEM 1 25/26 

 

Group 1: 

NUR ALEEYA AQMAR BINTI MOHD RADZIF S78538 

MUHAMMAD AMIR HAZIQ BIN MOHD NOOR S78521 

MUHAMMAD AFIQ HANIF BIN SUHAIMI S62993 

NUR DINIE YASMIN BINTI ZULKARNAIN S78541 

 


Software Engineering 

 
1.Introduction to The System 

   Conventionally, the management of leaves in organizations has been done through manual means like paper-based, spreadsheet, emails, or oral requests. Most of these methods cause various issues such as lost records, sluggish authorization, absence of transparency, and inability to monitor the leave balance of employees. With the increase in the size of the organization, the manual management of leave becomes both inefficient and can easily be affected by human error. 

   In response to these issues, Online Leave Management System was created as an electronic tool that could be used to automate and plan the leave application process. It is a system that gives a centralized system where employees are able to request leave online, check on the status of leave as well as check the balance of their leave. Meanwhile, administrators or supervisors will be able to check the applications, approve them and keep proper records of leaves in an orderly fashion. 

   Use of an Online Leave Management System enhances efficiency through minimization of paperwork, minimization of time spent in the processing of the work and implementation of uniformity in the use of organizational leave policies. It will also improve the level of transparency and accountability because all information regarding leave will be organized and easily retrieved as and when necessary. This has led to a more dependable and streamlined leave management process by both the employees and management. (Online Leave Management System Easy to Use and Free for 2023, n.d.) 

   The Online Leave Management System is analysed using the principles of system thinking and logical problem-solving with this assignment. The system is analysed with the help of determining its essential elements and operations, and by depicting the logic of the system in form of flowcharts and pseudocode. By applying this analysis, the assignment has revealed how the real administration systems may be disassembled into simple, rational steps to facilitate the system design and documentation. 


2. Functional Requirements 

Functional requirements describe the specific functions that a system must perform to support its intended operations and to fulfil user needs. They define what the system should do, including user interactions, data processing activities, and system responses. In system development, functional requirements are crucial as they form the basis for designing system features, workflows, and database structures. 

For the Online Leave Management System, functional requirements ensure that the system is able to manage leave applications efficiently, accurately, and systematically. These requirements focus on enabling employees to submit leave applications online, allowing administrators to process and manage leave requests, and ensuring that leave information is recorded and accessible when needed. By clearly defining the functional requirements, the system can improve administrative efficiency, reduce paperwork, and minimize errors in leave management. 

There are 5 main functional requirements identified for this system, which define the core functions required to support the operations of the Online Leave Management System. 


a) User Authentication 

   User Authentication function will be the one that will be in charge of ensuring the authenticity of users before they are allowed to access the Online Leave Management System. This role will make sure that the system features are only accessed by authorized users, i.e. the employees and administrators, as per their roles. The user is authenticated with the help of a valid username and password. Once user tries to log in, the system matches the user with the records stored in the system. In case the credentials are true, the system permits the user to get the system dashboard. In case of invalid credentials, an error and denial is shown by the system. Moreover, the system enables one to log off safely to avoid unauthorized access once the system has been used. This role is necessary to ensure the security of the systems, the security of sensitive leave information, and that only authorized users access the system. (Worksy, 2024) 

Flowchart: <img width="1384" height="3684" alt="image" src="https://github.com/user-attachments/assets/3487677f-65fd-44b2-8162-22c02f8055ea" />

Pseudocode: 

START 

DISPLAY login screen 

INPUT username, password 

IF username and password are valid THEN 

    DISPLAY "Login successful" 

    GRANT access to system 

ELSE 

    DISPLAY "Invalid username or password" 

    RETURN to login screen 

ENDIF 

IF user selects logout THEN 

    LOGOUT user 

    DISPLAY "Logout successful" 

ENDIF 

END 
