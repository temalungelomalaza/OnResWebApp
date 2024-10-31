# OnResWebApp
This system is a protoype of an online portal for the management of on-campus accommodation for full-time students. 
The system stores registered students' accommodation data including their assigned rooms, related debit and credit records and complaints about the assigned room, in order to achieve seamless and easier management on students living on-campus and tracking all accommodation services.

## STURCTURE OF SYSTEM
The system has 2 sub structures: frontend & backend
## Frontend
OnRes will include the following web pages and functionalities
1. Home Page/Landing Page

   - has login / register popups
   - provides brief description of the system as well as some images of the university dorms
   
3. User Profile
   - displays inofrmation of student ; full name, student ID, Year of study, gender and credit balances
     
4. Report dysfuntions
   - this page will allow students to lodge complaints about their rooms; broken or faulty utilities
  
     ## BACKEND
     The backend of this system runs on Flask, which is an open source API, plus MySQL, which is a relational database management system.
     Flask allows the querying of the databse using Python, suitably connecting requests and responses between the user interface and database.
