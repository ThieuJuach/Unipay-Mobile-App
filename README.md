CHAPTER 1
Project Title:             UNIPAY MOBILE APPLICATION

Problem Statement
In the current digital era, financial management and transactions remain a crucial part of daily life. However, many students and individuals struggle with managing their finances efficiently due to the lack of integrated systems that offer seamless transaction services. Existing platforms often focus on specific functionalities, such as payment or fund transfer, but fail to provide an all-in-one solution that can cater to the comprehensive financial needs of users, especially students.
In Kenya, students face challenges in managing their school fees, meal payments, and other expenses due to the fragmented nature of existing financial systems. This lack of integration not only causes inconvenience but also increases the risk of errors and financial mismanagement. There is a significant need for a mobile application that can streamline these processes, ensuring secure, efficient, and real-time financial management.
Project Objectives

A. Main Objective
To develop a mobile application that integrates various financial services, enabling users ie USIU-Africa students to manage their transactions efficiently and securely.
B. Specific Objectives
1.	To Integrate Mpesa for seamless deposit and transfer of funds.
2.	To Enhance user experience by providing a user-friendly interface for managing transactions.
3.	To Develop a robust authentication system ensuring secure access to financial data.
4.	To Streamline the process of viewing and managing receipts for better financial tracking.
   
Justification
The significance of this project lies in its potential to simplify financial management for users, particularly students. By providing an integrated platform, the application will reduce the time and effort required to manage finances, minimize errors, and enhance the overall user experience. This solution addresses a critical need in the market, offering a comprehensive tool for efficient financial management.


CHAPTER 2
Literature Review
Several financial management systems and mobile applications exist globally, offering various functionalities such as payment processing, fund transfers, and expense tracking. In Kenya, platforms like M-Pesa dominate the mobile money market, providing essential financial services. However, these systems often operate independently, lacking integration for comprehensive financial management.
Comparative analysis of existing systems reveals that while there are numerous solutions for specific financial tasks, few provide an all-in-one approach. This project aims to fill this gap by integrating multiple financial services into a single application, enhancing usability and convenience for users.
Unique features of Unipay include its focus on the student demographic, integration with Mpesa for seamless transactions, and a user-centric design that simplifies financial management tasks.


CHAPTER 3
3.0 Methodology
The development of Unipay followed a structured approach, ensuring thorough planning, design, and implementation. The methodology involved:
•	Requirement Analysis: Identifying user needs and defining system requirements.
•	System Design: Creating detailed design documents such as architectural diagrams.
•	Development: Building the application using modern development frameworks such as Android Studio and integrating Firebase for backend services.
•	Testing: Conducting rigorous testing to ensure functionality, performance, and security.

3.1 Preliminary Investigation
The preliminary investigation involved researching existing financial management systems, identifying gaps, and gathering requirements from potential users. Surveys and interviews with students provided insights into the features needed for an effective financial management app.

3.2 Design Phase
The design phase included creating detailed system architecture, user interface designs, and database schemas. Tools like Adobe XD were used for UI/UX design, and Entity-Relationship Diagrams (ERDs) were developed to model the database structure.


CHAPTER 4: Implementation
4.0 System Analysis & Design
The system analysis focused on defining the functional and non-functional requirements of the application. The design phase involved creating detailed architectural models, including data flow diagrams and entity-relationship diagrams.

4.1 Data Flow Diagram (DFD)
The DFD outlines the flow of data within the system, depicting how data moves between different components and processes. It provides a clear overview of the interactions between the user, the application, and the Firebase backend.
 

4.2 Entity Relationship (ER) Diagram
The ER diagram models the database structure, showing the relationships between different entities such as users, transactions, and receipts. It ensures a well-organized and efficient database design, crucial for the application's performance and reliability.
 

4.3 TABLES CREATED IN THE FIREBASE REALTIME DATABASE:
Firebase Realtime Database is a cloud-hosted NoSQL database that allows data to be stored and synchronized in real-time. It is particularly well-suited for applications that require a consistent and low-latency solution for syncing data across multiple clients. In the Unipay mobile application, Firebase Realtime Database plays a central role in managing user data, transactions, and receipts.
The Firebase Realtime Database for Unipay is organized into several key nodes, each serving a specific purpose:
1.	Users: Stores information about each user.
2.	Transactions: Records all financial transactions initiated by users.
3.	Receipts: Contains details of receipts generated from transactions.



 

 

 

 


4.4 USER INTERFACE IMPLEMENTATION:
Below attached are the system implementation screenshots and explanations. 


Landing page
This will be the landing page of the mobile application. It gives an option to login if you have an account. We have managed to create a login Ui that requires a students email issued by the school i.e the email must look like this: student@usiu.ac.ke and one must key in their password if they already have an existing account. If one doesn’t have an account they are required to sign up for an account.
 

If the user already has an account, they can simply enter the details that they had registered with. If the credentials are correct, the user is authenticated and is allowed to enter and get access to the system. The credentials are captured and are compared to the details stored in the database. If the user does not have an account, they will have an option to sign up. The details are captured through a form and are posted to the database.
This Ui comes immediately after a successful login it displays the users current balance and they are given options to retrieve money  from their Mpesa or  google wallet into the app . It also gives the user the option for transferring money from one student account to another student registered account. This will then prompt the app to look for the recipient of the money on the database because they must be a student in USIU-Africa. 

 

The applications main initiative was so that students could pay for services on campus with ease. This next part offers the option to buy or make payment from within school selected businesses i.e Paul’s café, Sironi or even when a student wishes to pay for their graduation fee.

 
 
 

