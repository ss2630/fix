# Agora
Web application 
AGORA
Overview
Agora, derived from the Greek word for a public gathering place or marketplace, aims to create a forum in which college students can buy, sell, or rent any school supplies or textbooks they may have or need. 
	The application will allow students to enter the website using their unique school ID, create an account, and then fulfill their need. The goal is to build this application and utilize Rutgers University as a testing ground / incubator, then expand to colleges and universities across the nation.


ER-diagram
 

Three main tables: 
•	Book table: 
o	Unique key: book_id
o	includes book info such as ISBN, sell price, rent price, picture
•	Customer table:   
o	Unique key: RUID
o	User basic info:   Name, address 
o	Stores store buyer & seller information 

•	Transaction table:  
o	Unique key: transaction_id
o	contains seller, buyer id, book id
•	Order Table:  search for orders can retrieve all the relevant information
o	unique key: Order_id 
o	Other attributes includes price, date, picture of item


 


