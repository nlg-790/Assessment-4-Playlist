### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

PostgreSQL is an open source database that supports SQL and JSON and is used for many websites and apps. 

- What is the difference between SQL and PostgreSQL?

SQL is a relational database management system and postgreSQL is an object-relational database management system. PostgreSQL is open source, while SQL is dependent on Microsoft.  

- In `psql`, how do you connect to a database?

psql is a program in terminal used to control databases. 
In terminal: psql database_name 

- What is the difference between `HAVING` and `WHERE`?

HAVING is which results you keep. and WHERE is which rows you are going to use. 

- What is the difference between an `INNER` and `OUTER` join?

INNER matches only the rows in both tables

OUTER matches the rows from either the left or right table 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

The LEFT OUTER is all of the rows from the left table combined with the matching rows from the right. 

The RIGHT OUTER is all of the rows from the right table combined with the matching rows from the left. 

- What is an ORM? What do they do?

Object Relational Mapper. It translates between data in databases and object-oriented programming.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

AJAX allows HTTP requests directly from client side. 
Requests from server side allows HTTP requests from server or python.

AJAX requests are exclusive to its same origin. 
Server Side are not restricted to origin.

AJAX requests from browser has a higher risk of exposing more private data
Server Side Library is more secure since the info remains on the server. 



- What is CSRF? What is the purpose of the CSRF token?

Cross Site Request Forgery - Forms can be submitted to other sites.
CSRF Token is checked by server on form submission


- What is the purpose of `form.hidden_tag()`?

form.hidden_tag() generates a hidden field that protects form against CSRF attacks using a token. 