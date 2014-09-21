# An Overview of Application Development

Application development is a complex and varied craft. It has many parts, each of which interacts with the other parts to make something truly great. We will begin our discussion at a high level and work our way down.

## Back-End and Front-End
Web development can generally be broken down into two parts: development on the back-end and development on the front-end. We will discuss the differences here.

### Back-End
*Back-end* normally means accessing and storing data. We do this using three parts:
-    Server
-    Application
-    Database

A *server* can be seen as something that makes transactions. When you visit a website in your web browser, a request is sent to a server for that website. The server takes the information from this request, does some processing, and then returns a response, which is normally in the form of a web page. In short, the server takes requests and gives responses.

An *application* represents all of the logic within an application. It does things like making sure form input is valid, adding information to and loading information from the database, and lots of other things. Think of the application as the controller of what happens within an application.

A *database* holds some data. For simplicity, think of it as lots of giant Excel spreadsheets, each with rows and columns. We can store information like user information, posts, comments, and other things here.

Together, these parts combine to be the *back-end*. When people say they are *back-end programmers*, these are the types of things they are talking about.

Common programming languages used for the back-end are:
-	PHP
-	Ruby
-	Python

### Front-End
*Front-end* normally means anything that the user sees and interacts with. This can be classified in two parts:
-	Design
-	Development

*Design* focuses on making a site look beautiful and professional. This involves making graphics in photoshop, aligning photos nicely, and choosing the correct color scheme.

*Development* is most of the logic that the user sees. This involves things like creating forms, drop-down menus, and buttons. Information loaded from these front-end pieces.

Common programming languages used for the front-are are:
-	HTML
-	CSS
-	JavaScript

### Communicating between Front-End and Back-End
While the parts are useful on their own, you web application becomes really meaningful once we wire them together. We can think of this process as a chain that goes in both directions. Let's look at this path:

1.	A user enters her information in a form and presses "Submit"
2.	The front-end code passes this information to the back-end server, which takes the request.
3.	The back-end server passes the information to the application, which checks certain things, like whether the e-mail address is valid, whether the passwords match, or whether the username you chose already exists.
4.	If all the user is correct, the application will create a new record in the database, with our new user and all of her information. This way, we'll have access to the user's information later when she tries to login.
5.	If the user was successfully created, the server returns a response to indicate that the user was successfully saved. If the user was not successfully created, the server returns a response to indicate this.
6.	The front-end code then makes changes to the appearance of the page to reflect this. Perhaps, if the e-mail name is invalid, the front-end will turn that field red.

We can see, then, that the chain starts at the user's interaction with the front-end, goes all the way back to the server, database, and application layers, then comes back to the front-end.


We will learn more stuff as you go, but this is a good way to start to understand the big picture of application development.



