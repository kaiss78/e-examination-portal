Mission Statement
Our mission is to  create an examination system which can test students on different subjects, provide grades, statistics and an option to review the mistakes.







Overview:
This  document is meant for describing all the features and procedures that were followed while developing the system. The document specially mentions the details of the project how it was developed, the primary requirement, as well as various features and functionalities of the project and the procedures followed in achieving these objectives.
Description:
	ONLINE TESTING SYSTEM is a service to help students take up online tests and analyze their performance.
	Its aim is to take online test of students according to their required field.
	Student can choose tests in accordance with his or her convenience and preference.
	There might be a provision for feedback from  users to implement it in future.
	At ONLINE TEST PORTAL students can find out an elaborate list of online tests being conducted at various locations. The searches can be filtered on the basis of subject name or their related field.
	It is not just the online test that is done through our website, but students can also improve their logic and skills by using student’s corner in which there are quiz, games, puzzles, challenges etc.
	ONLINE TESTING SYSTEM has registration request system that notifies the students through message on cell phone and also through email.
	 ONLINE TESTING SYSTEM may also offer alerts of all leading national and state level test, upcoming technical exams on various technologies like .NET, JAVA etc.
	ONLINE TESTING SYSTEM is an online portal to help students take up tests and practice conveniently.
	Students can also analyze their performance by the portal and make required improvements for the future exams.


1.	Functionalities:
Some of the functionalities of the project are as follows:
	Participant can select their field and Major from given options.
	Participant can show their result of given exam.
	Participant can select the level of the practice exam.
	Multiple Choice questions can be conducted by this system.




2.	Technologies used:
A developer no matter, how skilled is dependent on the tools and technology at his disposal. There are numerous free tools to aid in .net development; from source control to debugging and from documentation to profiling.
4.1 Software used:

•	Front-End:ASP.NET (Framework 4.0)
•	Code Behind-C# 4.0
•	Back-End –MS SQL Server 2008
•	Microsoft Visual Studio 2010

4.1.1 ASP.NET (Framework-4.0):
•	ASP.NET is a free technology that allows anyone to create a modern web site.
•	ASP.NET is a powerful platform for developing software.
•	ASP.NET is a web application framework developed and marketed by Microsoft to allow programmers to build dynamic web-sites, web-application and web-services.
•	Using Asp.Net we can make a web application easily.Asp.net server control enable an HTML-like style of declarative programming that let developer build great pages in far less code. Moreover Asp.Net pages work in all browsers.
•	 Asp.Net supports so many languages that give a great flexibility to the programmer. Developer can visually design Asp.Net Forms using familiar drag-drop-double-click techniques and enjoy full-fledged code support.

•	Asp.Net features a large number of classes that encapsulate rich functionality like XML, data access, file upload, regular expressions, image generation, transactions, message queuing, SMTP mail and much more.
•	ASP.NET 4.0 supports Entity Framework ,MEF ,Parallel Computing ,WCF 4.0,WCF Data Services , Workflow 4.0,C# 4.0,Asp.NET 4.0,MVC 4.0
4.1.2 C# 4.0:
•	C# is a very powerful language that supports high level of Abstraction
•	C# is a pure Object-Oriented language
•	C# supports inheritance, polymorphism, garbage collection and many oops concepts

4.1.3 MS SQL Server 2008:
•	Microsoft SQL Server is a relational model database server produced by Microsoft
•	Its primary query languages are T-SQL and ANSI SQL
•	It included native support for managing XML data, in addition to relational data
•	It allows DML and DDL functionality
4.1.4 Microsoft Visual Studio 2010:
•	MS Visual Studio 2010 is one of the very powerful IDE
•	It supports many languages, integrated web-server, code completion, refectory tools, debugger etc
•	You only need to have a highly configured computer system
4.2 Hardware used

•	Operating system: Windows -7 Ultimate
•	Processor: Core i5 second generation
•	Internet connection
•	Mobile phone

3.	Development Process model:
From a software engineering point of view we followed the Rapid Application Development process for our project implementation. Rapid Application Development (RAD) is a software development methodology that uses minimal planning in favor of rapid prototyping. The planning of software developed using RAD is interleaved with writing the software itself. The lack of extensive pre-planning generally allows software to be written much faster, and makes it easier to change requirements. Figure 1 depicts the phases of RAD software development process model.


Figure 1: RAD software development process model

Just like with all other software development process model RAD process model starts with development of preliminary data models and business process models using structured techniques. In the next stage, requirements are verified using prototyping, eventually to refine the data and process models. These stages are repeated iteratively; further development results in a combined business requirements and technical design statement to be used for constructing new systems.
4.	E-Examination project phases:
Considering the RAD design process model we had to follow certain standard steps for the successful completion of our project mentioned below, the steps also outlines the milestones covered until there
I.	System Analysis:
•	Identify system needs
•	Identify end user’s needs
•	Identify software needs
•	Identify project constraints
Milestone: Needs and Benefits Defined, Analysis

II.	Determine inputs and outputs:
•	Determine input
•	Determine output
•	Analysis and designing diagrams
Milestone: Decide input, output and control, Feasibility assessed.
III.	Modularization:
•	Check interdependencies
•	Time allocation
•	Effort validation
•	Defining responsibilities
•	Identifying outcomes
•	Workload distribution among team members
Milestone: Complete scheduling of whole project, Validation Phase.
IV.	Designing:
•	Database design
•	Design of home page
•	Design of registration form
•	Design of users corner
•	Design of the admin page
•	Design of login page
•	Design of exam page
Milestone: complete design of whole project.

V.	Coding:
•	Document all design
•	Develop various forms
•	Linking various forms
•	Connecting forms to database
•	Creating stored procedure
•	Perform various operations on database
•	Put validation control
•	Make security to project
Milestone: Make coding of all forms, Validation Phase.
VI.	Implementation:
•	Implement designed forms
Milestone: Implementation Phase
VII.	Testing:
•	Check for hyper links
•	Check for validation control
•	Check for database operation
•	Security check
Milestone: Testing, Project Meeting
VIII.	Documentation:
•	Document the final report.
Milestone: final report documentation phase
5.	User characteristics:
The user characteristic defines the type of User who is interacting in the system and are involved in the system. E-examination Portal has basically three types of users who will be interacting with the system and play different activities in the system.

The users of E-examination Portal are:
•	Student
•	Visitors
•	Admin

7.1 Student:

	Students can give online test of different fields.
	Students have to login first to give the online test of any subject.
A Student doesn’t have following rights:
•	He can’t add/update/delete any data of the system.

7.2 Visitors:

	Visitor can just go through this site but he/she cannot take online test.

7.3 Admin:

	Both users that are student and visitors are controlled by the site administrator; site administrator is not visible to any of the users.
	Any updating needed in the lists of online tests, students and visitors is done by site administrator.
	List of test directly shown on ONLINE TEST PORTAL are to be registered first by the site administrator.
	Site administrator maintains the site; it verifies and validates all the documents.
	Site administrator will upload all the available tests and then takes into account the scheduling of the students over there.
	Site administrator will carry out exam analysis of the students and their success ratio
An Admin has the following rights:
•	He can add/update/delete any data of the system.





FUNCTION OF SYSTEM

> Used Cases and Sequence Diagram

Use Case:
Actor:
> A coherent set of roles that users of use cases play when interacting with the use `cases.



> Case:
A description of sequence of actions, including variants, that a system performs that yields an observable result of value of an actor.



UML stands for Unified Modeling Language. UML is a language for specifying, visualizing and documenting the system. This is the step while
developing any product after analysis. The goal from this is to produce a model of the entities involved in the project which later need to be built. The representation of the entities that are to be used in the product being developed need to be designed.

Use case diagrams model behavior within a system and helps the developers understand of what the user require. The stick man represents what’s called an actor.

Use case diagram can be useful for getting an overall view of the system and clarifying that can do and more importantly what they can’t do.

> Use case diagram consists of use cases and actors and shows the  Interaction between the use case and actors.

•	The purpose is to show the interactions between the use case and actor.
•	To represent the system requirements from user’s perspective.
•	An actor could be the end-user of the system or an external system.

A Use case is a description of set of sequence of actions.  Graphically it is rendered as an ellipse with solid line including only its name.  Use case diagram is a behavioral diagram that shows a set of use cases and actors and their relationship.  It is an association between the use cases and actors.  An actor represents a real-world object.


MAIN MODULES OF NEW SYSTEM

There are 3 main modules of our system:

Registration
Online Exam
User’s Corner

	Registration:
This takes into account the free registration of the user. Visitor register themselves and after that they will be known as Student in our website.
	Online Exam:
After Registration Student will be able to give Online Exam in our website. In Online Exam Questions are generated randomly and the specific time limit is given for each test.
	User’s Corner:
This Module can be used by both users’ visitor as well as Student. In this module both can play games and solve puzzle.