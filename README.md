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
    This application will provide for users to view about famous people's biography in Myanmar such as business leaders,models,actors,actresses,directors and vocalists.By using this application,you can know these people biography in details.
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
     This application can be used with mobile phones,tablets or PCs.The project provides about an application that gives famous people's information in Myanmar.This application is simple and easy to use.
     The project"Who is Who in Myanmar" intends to know about the biographies of famous actors,actresses,business leaders,vocalists,directors and models.Our project is helpful to save your time by viewing famous people's biography easily and quickly.
     1.2 Background of the app
      1.2.1 HTML,CSS,JavaScript
      Hypertext Markup Language is the standard markup language for creating web pages and web applications.With Cascading Style Sheets and Javascript, it forms a triad of cornerstone technologies for the World Wide Web.So we use html,javascript,css for this project.
      To make this application,we use materializecss, material design lite.
     1.2.2 What is Python?
     Python is a scripting language like PHP, Perl,Ruby and so much more.It can be used for web programming(Zope,Google App Engine,and much more).But it also can be used for desktop applications and can also be translated into binary code like java.
     It can be used to build server-side web applications. While a webframework is not required to build web applications,it's rare that developers would not use existing open source libraries to speed up their progress in getting their application working.
     Python is not used in web browser.In this project,we use Python programming language due to this above good facts.
     1.2.3 What is Flask?
    Flask is a lightweight web framework written in Python.Flask provides you with tools,libraries and technologies that allow you to build a web application.In the case of Flask,its dependencies are:Werkzeug a WSGI utility Library,Jinja2 which is its template engine.
    Flask is commonly used with MongoDB which allows it more control over database and history. Applications that use the Flask framework include Pinterest, Linkedln and the community web page for Flask itself. 
    Flask is now one of the most widely used Python web frameworks for start-ups, and is becoming commonly accepted as the perfect tool for quick and simple solutions in most businesses.In this project,we use Flask to build a web framework in Python.
    1.2.4 What is SQL Alchemy?
      SQL Alchemy is a library that facilitates the communitation between Python Programs and databases.
      Most of the time, the library is used as an Object Relational Mapper(ORM)tool that translates that Python classes to tables on relational database and automatically converts function calls to SQL statements.
      SQLAlchemy considers the database to be a relational algebra engine, not just a collection of tables.Rows can be selected from not only tables but also joins and other select statements:any of these units can be composed into a larger structure.
      SQLAlchemy's expression language builds on this concept from its core.
    
    
                                   
