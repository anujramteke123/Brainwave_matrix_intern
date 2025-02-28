# Brainwave_matrix_intern
 I have completed my given task by brainwave matrix solutions.
 Task Name : To Design and Implement a relational database on library management system..

 In this Library Management System Database I create total 8 tables which contains different attributes in it and different values.

 𝗔𝗨𝗧𝗛𝗢𝗥 𝗧𝗔𝗕𝗟𝗘 :

 Author table consist of 2 attribute 
  1] Author_Id : this is a primary key in this table and datatype is int.

  2] Author_Name :This consist of name of Author and datatype is varchar.
  
 𝗕𝗢𝗢𝗞 𝗧𝗔𝗕𝗟𝗘 :

  1] Book_id : This consist of the id of book and datatype is int.

  2] Isbn : This is a primary key of these table and isbn is stands for international standard book number and datatype is varchar.

  3] Book_Name : This consist of name of the book and datatype is varchar.

  4] Publicationyr : This consist of year of publication and datatype should be the int.

  5] Totalcopies : This consist of the total no. of the copies of that particular book in library and datatype is int.

  6] Availablecopies : This consist of the available copies of that paticular book in the library and datatype is int.

  7] Publisher_id : This is the foreign key referencing publisher in this table and this attribute tell about the id of publisher and datatype is int.

  8] Genre_Id : This is also the foreign key referencing genre in this table and this attribute tell about the id of the genre and datatype is int.
  
 𝗕𝗢𝗢𝗞_𝗔𝗨𝗧𝗛𝗢𝗥𝗦 𝗧𝗔𝗕𝗟𝗘:

  1] Book_id : This consist of the id of book and this is a primary key in this table and the datatype is int.

  2] Author_id : This consist of the id of the author and datatype is int.
 
 𝗚𝗘𝗡𝗥𝗘 𝗧𝗔𝗕𝗟𝗘:

  1] Genre_id : This attribute is a primary key in these table and this attribute shows the id of the genre. 
  
  2] Genre_Name : This attribute shows the name of the genre. 

  LOANS TABLE:

  1] Loans_id : This attribute is a primary in the loans table and the attribute loans_id shows the unique id for the loan.

  2] Loans_date : This attribute consist of the date of loans and the datatype of these attribute is varchar.The datatype of the attribute Loans_date should also be the datetime.

  3] Returned_date : This attribute consist of the date when the book is returned to the library and the datatype is should be varchar or datetime.

  4] Book_id : This attribute consist of the id of the book and these attribute is the foreign key referencing book and the datatype is int.

  5] Member_id : This attribute consist of the id of the member and these attribute is the foreign key referencing member and the datatype is int.

  MEMBER TABLE:

  1] Member_id : This attribute is the primary key in these table which consist of the id of the member and the datatype of these attribute is int.

  2] Member_name : This attribute consist of the name of the member and the datatype of these attribute is varchar.

  3] Address : This attribute consist of the address of the member and the datatype of these attribute is varchar.

  4] Mobile_no : This attribute consist of the mobile number of the member and the datatype of these attribute is varchar.

  5] Joindate : This attribute consist of the date when the member join the library and the datatype should be varchar or date or datetime.

  6] Enddate : This attribute consist of the date when the member end their membership with library and the datatype should be varchar or date or datetime.

 PUBLISHER TABLE:
 
 1] Publisher_id : This attribute is the primary key in these table and the datatype of these table is int . This attributes shows the unique id for the publisher.

 2] Publisher_Name : This attribute shows the name of the publisher and the datatype of these attribute is varchar.
 
 RESERVATIONS TABLE:

 1] Reservation_id : This attribute is the primary key in these table and the datatype of these table is int. This attributes shows the unique id for the reservations.

 2] Isbn : This attribute is the foreign key referencing book in these table and the datatype of these table is varchar. This attributes shows the isbn of the reserved book.

 3] Member_id : This attribute is the foreign key referencing member in these table and the datatype of these table is int. This attributes shows the id of the member who made the 
                reservations.

 4] Reservation_date : This attribute shows the date when the reservation is made and the datatype of the table is varchar or date or datetime.

 5] Reservation_status : This attribute shows the status of the reservation and tell about the reservation is pending,successful or cancelled . The datatype of the attribute is varchar 
                         or enum.

 
 
  
