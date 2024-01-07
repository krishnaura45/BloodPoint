# BloodPoint : DBMS based Blood Bank Management Portal

BloodPoint is an end to end Database focused portal for registration of blood donors and blood stocks, organizing information and controlling blood distribution 

### ABSTRACT
The goal of this mini project is to create a Blood Bank Management System (BBMS) that will
help with the management of blood donor records and make it simple to manage the
distribution of blood around the nation based on hospital needs. In other words, it is an
application-based system designed to collect, manage, retrieve, and analyse data related to the
administrative management of a blood bank.

Making market strategies for blood donation, influencing blood donors, and sensitising them
to blood donation become exceedingly challenging without quick and timely access to donor
records. This project intends to keep all the data relating to blood donors, the various blood
types accessible in various places, and assist them in managing more effectively. The objective
is to increase openness in this area, simplify the process of getting blood from a blood bank,
and improve the efficiency of the blood bank management system. The technology platform
utilised to construct this system consists of MySQL for SQL database (Back End), Java
Programming Environment (Ant) using Netbeans IDE, and JFrame for front end development.
Our mini project is totally dependent on admin who gathers information regarding blood
donors, blood groups and blood stocks, and updates it in the database through the system.

### INTRODUCTION
the purpose of successful completion of our course Data Base Management System (DBMS).
It maintains Online Library of blood donors and blood stocks in various places of our
country. Sometimes, Doctors have to face the difficulty in finding the blood group donors at
the right time. Our project has attempted to provide the answer by taking upon itself the task
of collecting blood nationwide for the cause and care of people in need. At any point of time
the people who are in need can reach the donors through our search facility. By mobilizing
people and organization who desire to make a difference in the lives of people in need.
Our proposed system has the following major modules :
1. Donor (add, update, view)
2. Search Blood (by location and blood group)
3. Blood Stock (increase, decrease, view)
4. Delete Donor 

Without quick and timely access to donor records, creating market strategies for blood
donation, influencing and sensitization of blood donors becomes very difficult. 

### RESEARCH GAP
There are a quite good number of software packages that exist for blood bank management
system. But when I visited most blood bank management system portals, I found that existing
system is limited only to those particular blood bank.
Problems Found In Existing Systems :
- At the present there is no software to keep any records in blood bank.
- It becomes difficult to provide any record immediately at times of emergency.
- Required more human efforts in maintaining the branch related information.
- Manually to keep the accounts is also tedious & risky job & to maintain those
accounts in ledgers for a long period is also very difficult.
- Difficult to manage and maintain the files.
- Chance of damage of files, if the data is stored in the files for long duration of time.
- Privacy is difficult.
- Time consuming in retrieving, storing and updating the data.
- It is difficult to keep track the record about the donor & receiver he has donated or
received the blood at the last time.
- Attendance is taken manually.
- It need upgradation. 

### PROPOSED METHODOLOGY
We have compiled the system's admin requirements and prepared the project's scope and
purpose before starting. The outcomes of this phase include the proposed system's features,
scope and limitations, objectives, costs and advantages, and user interface design.
After researching and identifying the issues with the current system, we created an entity
relation diagram (E-R diagram) for the suggested solution.
We transformed the E-R diagram into a relational database model based on the analytical
phase, a user interface was also designed during this phase. 

##### ER MODEL

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/d541bc00-1b58-4916-809a-52774a75041d)

##### RELATIONS
There are two relational schemas :-
1. donor (donorId, name, fatherName, motherName, DOB, mobileNo, gender, email,
bloodGroup, city, address)
- Functional Dependencies : {(donorId -> name, fatherName, motherName, DOB,
gender, mobileNo), (mobileNo -> email, bloodGroup, city, address), (email ->
donorId)}
- Candidate keys : {donorId, mobileNo, email}

2. stock (bloodGroup, units)
- Functional Dependencies : {(bloodGroup -> units)}
- Candidate keys : {bloodGroup}

Analysis : As the determinant of each functional dependency in both relational schemas are candidate keys, both the relations are in Boyce Codd Normal Form (BCNF)

### IMPLEMENTATION
Login Page

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/6ef02a73-4852-4e88-a37c-6804b010fd8d)

Home Page

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/a850d6be-6b47-41b8-959b-a018f0f32e78)

Menu Pages

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/bb421dc3-30ba-42fd-b8f2-0cb5ca3ed90e)

### RESULTS
#### Project Parts in Running State ---
Login Page Checkup

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/ee42b44d-fe79-4a05-92c0-2b41e4bb3e82)

Donor Details Updation

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/d01b9999-1af5-44ac-bd5d-dbb0f32b8d5d)

Other Pages

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/3df294d3-7c5d-4ba1-ab7b-b0c5f8db85c9)

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/da0b827c-69f6-4ded-99eb-f6cec5809d9a)

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/17a054bc-44cb-41b6-9695-0a396e782744)

![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/c6edfd79-5034-431a-88cb-74d4120cc250)

MySQL Command Line
![image](https://github.com/KD-Blitz/BloodPoint/assets/118080140/bfc72972-ff7b-471b-ab81-3dc46c371465)

### OUTCOMES
Due to the heavy emphasis on theory in our curriculum, it is crucial to make the most of each
chance to get practical experience that presents itself. One of these opportunities was the
"BLOOD BANK Management System" major project's foundational elements. We gained
the necessary practical expertise to support the previously taught theoretical principles,
which improved our abilities as computer engineers. 

### REFERENCES
1) https://www.javatpoint.com/java-jframe
2) https://bbmis.hp.nic.in/#:~:text=Blood%20Bank%20Management%20System%20(BB
3) https://www.studocu.com/in/document/delhi-technological-university/database-management-systems/dbms-blood-bank-management-system/26578691
4) https://www.w3schools.com/mysql/default.asp
5) https://www.oracle.com/in/tools/technologies/netbeans-ide.html

### Tech Stacks 
- Java
- Netbeans IDE
- MySQL
- JFrame

### Project Team
Krishna Dubey, Pankaj Kumar Giri (Collective Contribution)

