lab-4
=====
#Software engineering
##lab 4: modelling software requirements
### A. Get familiar with software requirements specification (SRS) documentation

**1. Find existing requirements documentation** e.g. by querying

   * requirements specification
   * requirements specification example pdf
   * srs pdf
    or here
   * (Maybe too big for today; but could be interesting to check for your project: http://www.i-locate.eu/public-deliverables/)

AVOID DUPLICATE. Check if the SRS you found has not been already taken: https://docs.google.com/document/d/1e2hjG9Fs-gl-k7V5mrX6Fz_oTahO69wWQVh2VYzFB0Q/edit And add yourself there. First come, first served.
   
   (http://site.iugaza.edu.ps/oradwan/files/SRS.pdf)
   
**2. Report the following things related to the document you found:**

**(Introduction)*

   * What is the project?
   
   The aim of the documentation is to illustrate how a product which is Web Library Management System is functioning so that the web developer will have an insight to design the real project.

   
   * Overall description of the product (=what is it? can you understand it?)
   
   The product is a web based application, its basic functionality is to update and modify user’s account information, show and reserve available books and notify the user the remaining renewal time of their borrowed book. The product is designed to be used by an existing or new user as well as by the librarians.

   * Target audience (of the document)?
   
   The web site developer, testers, librarians and managers and coordinators.
   
   * The situation? Motivation?
   
   The product is designed basically enhance the functionality of the manual library system.

   * Structure
   
   The structure differ from the group project ; the project template included the system Archtechre, Risk analysys,budget… however the document I review doesn’t include all those contents.

**(Use cases)**
Library members

- The member should be provided with the updated information about the books catalog.
- The user should have to have access to the books catalog.
- The user has to be able to update the details in his/her account.
- The user have the ability to explore books by different categories such as title, authors etc. 
- The user can renew the bowered book online.
- The user can request for the book of his choose to the book shelf even if its unavailable for the moment.

Librarian (administrator)

- The librarian can add, delete a book form the shelf and update the catalog.
- Can accept or reject a new user according to the library policy or payment methods.
- Can accept the renewal or extension period for a borrowed book.
- Can access the information of the user who has borrowed a book.
- Can notify the user if the deadline has come to an end.
- Can arrange the books by categories.
- Make and remove reservations.


  * What the system (will) do?
  
  The system interface will allow the library members to see the information on their account, borrow, reserve and renew book.  While the librarian can set books by order, notify users for renewal….etc.

  * Use case diagram?
  The document doesnt have a use case diagram, i draw one.

http://users.metropolia.fi/~lilyg/UseCaseDiagram1.jpg
http://users.metropolia.fi/~lilyg/UseCase%20Diagram1.jpg

  * Actors?
  
  Librarians and the administrators
  
  * How cases are described, how much details?
  
Case diagrams are described in a concise way however the use cases for a registered user and a random library user are written in the same use case category under library members. I hope extra use case for random user should be added. E.g.  Sign up (register) field should be provided for a random user.


**(General structure of the system)**

   * What chart techniques are used? Why?

**(Functional & non-functional requirements)**

   * Listed?
   
   ** Functional requirements**

  Admin

- should be able to insert, modify and delete books.

- Can accept or reject a new user according to the library policy or payment methods.

- Increase the period for borrowing a book for specific type or group of users.

- Can get the information (status report) of any member who has borrowed a book.

- Add and edit book categories and arrange books by categories

- Add and edit authors and publishersinformation

- Can send lateness warnings to people who have exceeded deadline date.

- Can record books returned by users


  Normal User 
  
- Register:  when new user enters WLMS for the first time then he has to register 

- extending borrowing deadline:member can extend the borrowing time to some limit decided by Admin

- Reset password: Description when a member forgets his password he can claim it back via e-mail.

- Edit personal information: Description if some user changes for example his mobile number, he can modify it.

- Reset password: when a member forgets his password he can claim it back via e-mail.
    
   **Non Functional requirements**

- Error handling: WLMS product shall handle expected and non-expected errors in ways that prevent loss in information and long downtime period.

 - Performance Requirements: The system shall accommodate high number of books and users without any fault. Responses to view information shall take no longer than 5 seconds to appear on the screen.
 
- Safety Requirements:  System use shall not cause any harm to human users.

- Security Requirements: the database functionality of the product is secured with password.

- System will have different types of users and every user has access constraints.


   * Measurable/traceability? (is it possible to check from the upcoming end product if a feature / requirement is implemented or not?)
   
Yes it can be checked in the requirement specification.


**(How does (will) it look?)**

  * UI examples / views?
  
  * Are the pictures mockups or screenshots from existing system?
  
The mockups are made for the first time for the specific project not from the existing system; the product version is a new one.its is not screenshot.

  * Transitions between views
  
  I think the user interfaces are done layer by layer without skipping the UI from each step in the case of UI for the user but in the case of administrator the UI are not done in detail. 

  
**(Process model? [might not exist, some times in a separate document called ‘project plan’])**

   Not included

  * Allocation of resources / budget?
  
  Not included

  * Risk Analysis?
  
 Not included

**(Your point of view)**

  * Is it a good/bad document? Why?
  * Consider also the quality of diagrams / illustrations
  * Do you think there would be enough information for you to build that system?
    Etc.

 I think it is fair document however I wouldn’t say it is possible to develop real full system out of the documentation. Because the system architecture is not done (not Mentioned at any level), risk analysis is not mentioned. The user interface for the administrator case is not discussed clearly (step by step).but with respect to the UI diagrams it is quite nice one.



  *  Do you get an idea how and what to write?
  
  Yes

  *  At the content level, is there parts that you would simplify or go into more details?
  
  Perhaps with the functional and nonfunctional requirement.

  *  Do you think that you are able to list functional requirements? Non-functional requirements (and make them measurable)?
  
Yes

  * What is the importance of the illustrations/diagrams/mock-ups?
  
By using pictures (mockups) we can minimize the length and complexity of our documentation. System users like having pictures, diagrams, for quick reference.

  *  How much "technical" vocabulary should be?
  
 Not much, the Documentation will be written so that anyone with only basic computer skills can read it and learn how to properly use the system. If there is any I will place it in an appendix.


  *  Etc.
