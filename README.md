# case-study-4th-week


case study 4:
==============
Layerd Architecture:
=====================

Refer the case study and create an application for that requirement by creating packages and 
classes as given below:

Books Service Application:
=========================
a)  com.ac.bean
 
    In this package, create “Book” class with different attributes such as bookid, 
bookTitle, bookPrice, grade.

b) com.ac.service

    This package will contain code for services offered in Books. 
	  create one bookService method with parameters.
	  implemnt the bussiness logic. based on the book price assign the Grade of the book. 
	  create the objets of dao,bean
	  wrap up all the four field values into bean 
c)com.ac.DAO
     
	 1.  create a DAO classs
   
    a)create method  addBook() passing bookbean paramter
         with in the method get the connection and insert the values by using praperd statement.
		 
    b) create a method: ArrayList getBookDetailsById(int bookId)
	       write exception id is there are not 
     	
  
    2. Create a database class to connect with database
	
	    a. create a method static Connection getConnection();
		     write get the connection details and return the connection.

d)com.ac.Ui
 
   
  1. Intialize the values bookid,price,title 
  2. by using scanner:
             End user 
       1. Enter BookId
	   2.Enter book title 
	   3. enter book price 
