# whoinmyanmar
Repo for project
## A Project Report on
### Python Flask Application(Who is Who in Myanmar)
              FOR
         GEO MANDALAR Co.,Ltd
    UNDER THE GUIDANCE OF
         Director
         U RAVI CHHABRA
         Supervisor
         Daw Khaing Myat Nwe
        Contents
                                
           Abstract                  
           Acknowledgement          
           Declaration              
           List of figures          
           List of Tables             
           CHAPTER 1 INTRODUCTION
          1.1 Introduction            
          1.2 Background of the app   
            1.2.1 HTML, CSS, Javascript      
            1.2.2 What is Python?
            1.2.3 What is Flask?
            1.2.4 What is SQL Alchemy?   
          1.3 Objective of the project         
          CHAPTER 2 METHODOLOGY
          2.1 Software Selection               
                Software Requirement
                Hardware Requirement
          2.2 Project Schedule                 
           CHAPTER 3 PROJECT DEVELOPMENT
           3.1 Design
           3.1.1 Class Diagram                  
           3.1.2 Use Case Diagram               
           3.1.3 Sequence Diagram               
           3.1.4 App Design
           3.2 Database Implementation          
          CHAPTER 4 EVALUATION AND CONCLUSION
           4.1 Conclusion                       
           4.2 Advantages of the project        
           4.3 Disadvantages of the project     
           4.4 Limitations                      
                                     Abstract
    This application will provide for users to view about famous people's biography in Myanmar such as business leaders,models,actors,actresses,directors and vocalists.By using this
    application,you can know these people biography in details.
    This application intends to give famous people's information for users.Then it can also be viewed to know this information easily and quickly.
    In our project,we use materializecss,material design lite,Python programming language.We also use Flask-SQL Alchemy, DB Browser for SQL lite for database.

                                  Acknowledgement
    We would like to express a great apprecitation to U Kyaw Swar Soe,Rector,University of Computer Studies(Mandalay) and who gives valuable advice at seminars for his permission to develop this project.
    Moreover,we would like to thank Dr.San San Tint,pro-rector and our supervisor,Daw Khaing Myat Nwe,Faculty of Computer Systems and Technologies,University of Computer Studies(Mandalay) for giving their constructive suggestions during the plan for development of this project.We would like to express our deep appreciation to the director, U RAVI CHHABRA(CEO of Geo Mandalar Co.,Ltd)for his guidance about software development workflow and for giving his trust to us such a responsibility project during internship programme.
    We also thank our parents and all of our friends for providing encouragement and giving us a great support during internship programme.
                                      Declaration
    We declare that this project report or part of it was not a copy of a document done by any organization,any other institute or university or a previous project group at University of Computer Studies(Mandalay) and was not copied from the Internet or other sources.
                       List of Figures
     Figures
     Figure(2.1) Project Schedule
     Figure(3.1) Class Diagram
     Figure(3.2) Usecase Diagram
     Figure(3.3) Sequence Diagram
     Figure(3.4) Drop categories when click menu icon
     Figure(3.5) Celebrity Page
     Figure(3.6) Clicking "READ MORE" link
     Figure(3.7) Selecting director tab
     Figure(3.8) Director Page
     Figure(3.9) Clicking "READ MORE" link
     Figure(3.10) Selecting business leader tab
     Figure(3.11) Business Leader Page
     Figure(3.12) Selecting vocalist tab
     Figure(3.13) Vocalist Page
     Figure(3.14) Model Page
     Figure(3.15) Clicking "READ MORE" link
                                    List of Tables
      Table
      Table(3.1) Celebrity Table
      Table(3.2) Director Table
      Table(3.3) Business Leader Table
      Table(3.4) Vocalist Table
      Table(3.5) Model Table
      Table(3.6) People Table
     CHAPTER 1 INTRODUCTION
        1.1 Introduction
        This application can be used with mobile phones,tablets or PCs.The project provides about an application that gives famous people's information in Myanmar.This application is simple
	and
     easy to use.The project"Who is Who in Myanmar" intends to know about the biographies of famous actors,actresses,business leaders,vocalists,directors and models.Our project is helpful to 
     save your time by viewing famous people's biography easily and quickly.
      1.2 Background of the app
         1.2.1 HTML,CSS,JavaScript
         Hypertext Markup Language is the standard markup language for creating web pages and web applications.With Cascading Style Sheets and Javascript, it forms a triad of cornerstone
      technologies for the World Wide Web.So we use html,javascript,css for this project.To make this application,we use materializecss, material design lite.
     1.2.2 What is Python?
         Python is a scripting language like PHP, Perl,Ruby and so much more.It can be used for web programming(Zope,Google App Engine,and much more).But it also can be used for desktop 
     applications and can also be translated into binary code like java.
     It can be used to build server-side web applications. While a webframework is not required to build web applications,it's rare that developers would not use existing open source
     libraries to speed up their progress in getting their application working.
     Python is not used in web browser.In this project,we use Python programming language due to this above good facts.
     1.2.3 What is Flask?
        Flask is a lightweight web framework written in Python.Flask provides you with tools,libraries and technologies that allow you to build a web application.In the case of Flask,its
    dependencies are:Werkzeug a WSGI utility Library,Jinja2 which is its template engine.
    Flask is commonly used with MongoDB which allows it more control over database and history. Applications that use the Flask framework include Pinterest, Linkedln and the community 
    web page for Flask itself. 
    Flask is now one of the most widely used Python web frameworks for start-ups, and is becoming commonly accepted as the perfect tool for quick and simple solutions in most businesses.
    In this project,we use Flask to build a web framework in Python.
    1.2.4 What is SQL Alchemy?
      SQL Alchemy is a library that facilitates the communitation between Python Programs and databases.
      Most of the time, the library is used as an Object Relational Mapper(ORM)tool that translates that Python classes to tables on relational database and automatically converts function calls to SQL statements.
      SQLAlchemy considers the database to be a relational algebra engine, not just a collection of tables.Rows can be selected from not only tables but also joins and other select statements:any of these units can be composed into a larger structure.
      SQLAlchemy's expression language builds on this concept from its core.
    
    
1.3	Objective of the project
       This project provides about famous people’s information in Myanmar.
	To give satisfaction to the users.
	To view about a biography of person who you want to know and to see this person’s photo.
	To save your time for using  this application.
	To give details about the biography of this person in Myanmar.
	To provide the information of popular people in Myanmar.
	

CHAPTER 2  METHODOLOGY
         2.1 Software Selection
          Chosen Programming Language
  I would like to choose Python as a programming language in my project because there are a lot of benefits.
	
Software Requirements

	Python 3.6.5
	Materialize CSS
	Material Design Lite
	DB Browser For SQL Lite
	Flask-SQLAlchemy 
	
                    Hardware Requirements
	Android Phones or  Tablets
	Internet Access
	PC with window OS
	
  





2.2 Project Schedule
       
For this project, UI-UX design, we worked together. Collecting data, for database implementation we worked together. Developers wrote the coding for this project.
 All of project preparation, we worked together.

              
	wk
1	wk
2	wk
3	wk
4	wk
5	wk
6	wk
7	wk
8	wk
9	wk
10	wk
11	wk
12
Traning and study duration												
Data Collection
												
Design,
Coding												
Test&
Documentation												

Figure 2.1 Project Schedule



CHAPTER 3 PROJECT DEVELOPMENT
                     3.1  Design
3.1.1  Class Diagram

           
 

Figure 3.1 Class Diagram for Application




 








3.1.2  Usecase Diagram

 Figure 3.2 Usecase Diagram for Application 
3.1.3  Sequence Diagram

 
Figure 3.3 Sequence Diagram for Application











3.1.4 App Design
When we click menu icon, we can see this categories such as celebrity(actors,actresses), director, business leaders, vocalists, models.

Figure 3.4 Drop categories when click menu icon 
Then we click celebrity tab to view about actors and actresses information.The following figures show this people photos and READ MORE link.

 
Figure 3.5 Celebrity Page
 
Figure 3.6 Celebrity Page


 
Figure 3.7 Celebrity Page
 
Figure 3.8 Celebrity Page


When we click “READ MORE” link of Wutt Hmone Shwe Yi,Wutt Hmone Shwe Yi biography in detail will show.
 

 

Figure 3.9 Clicking “READ MORE” link






Then we click director tab to view about directors information.The following figures show this people photos and READ MORE link.
 
Figure 3.10 Selecting Director tab
 
Figure 3.11 Director Page
 
Figure 3.12 Director Page
 
Figure 3.13 Director Page  
When we click “READ MORE” link of Wyne,Wyne biography in detail will show.
 
 
	Figure 3.14 Clicking “READ MORE” link






Then we click business leader tab to view business leaders information.The following figures show this people photos and READ MORE link.
Fi gure 3.15 Selecting Business Leader tab

 
Figure 3.16 Business Leader Page 

 
Figure 3.17 Business Leader Page
 

Figure 3.18 Business Leader Page 
 
Figure 3.19 Business Leader Page
Then we click vocalist tab to view about vocalists information. The following figures show the people photos and READ MORE link
 .Figure 3.20 Selecting Vocalist tab
 
Figure 3.21 Vocalist Page

 
Figure 3.22 Vocalist Page
 
 
Figure 3.23 Vocalist Page

 

Figure 3.24 Vocalist Page


Then we click model tab to view about model information.The following figures show this people photos and READ MORE link.
 
Figure 3.25 Model Page
 

Figure 3.26  Model Page 
 
Figure 3.27 Model Page













When we click “READ MORE” link of Nang Khin Zay Yar, Nang Khin Zay Yar biography in detail will show.
  
Figure 3.28 Clicking READ MORE link
 
3.2  Database Implementation
Database Tables
Table (3.1) Celebrity Table
Column	Constraint	Data Type	Length
Id	Primary Key	integer	
Name		varchar	30
Link		varchar	10
Occupation		varchar	30
Image		text	
Bio		text	

Table (3.2) Director Table
Column	Constraint	Data Type	
Id	Primary Key	integer	
Name		varchar	30
Link		varchar	10
Occupation		varchar	30
Image		text	
Bio		text	


Table (3.3) Business Leader Table
Column	Constraint	Data Type	Length
Id	Primary Key	Integer	
Name		varchar	30
Link		varchar	10
Occupation		varchar	30
Image		text	
Bio		text	

Table (3.4) Vocalist Table
Column	Constraint	Data Type	Length
Id	Primary Key	Integer	
Name		varchar	30
Link		varchar	10
Occupation		varchar	30
Image		text	
Bio		text	

Tabel(3.5) Model Table
Column	Constraint	Data Type	Length
Id	Primary Key	Integer	
Name		varchar	30
Link		varchar	10
Occupation		varchar	30
Image		text	
Bio		text	


Tabel (3.6)  People Table
Column	Constraint	Data Type	Length
Id	Primary Key	Integer	
Name		varchar	30
Link		varchar	10
Occupation		Varchar	30
Image		text	
Bio		text	
 


                  CHAPTER 4
EVALUATION AND CONCLUSION
4.1 Conclusion	
       This application is simple and can be used easily for users. 
       This would aslo reduce the time for user. It is easy to view about the biographies of directors, business leader, actors,actresses, vocalists who you want to know.
        The name “Who is Who in Myanmar” python flask application is convenient for users and it is one of the useful application in mobile phones, tablets or PCs.

 4.2 Advantage of the Project
         This application gives the following advantages:
	It can view to know about the biographies of famous people easily and quickly.
	It can save time for users.
	It is simple and convenient to use.


4.3  Disvantages of the Project
   If you have no internet connection, you cannot view about people information.
This application can only view about famous peole in Myanmar.



Limitations
This application is not a complete application. Users cannot be searched about  famous people’s biography because our application doesn’t contain search box .It is the weakness of our application. Therefore, users can only view about famous people biography in details by clicking read more link.

             
          
References
1.	www.wikipedia.com
2.	Learn Python the hard way Book
3.	Learning-Flask Framework Book             
                                 
