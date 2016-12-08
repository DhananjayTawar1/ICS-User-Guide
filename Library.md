# USER GUIDE FOR LIBRARY MANAGEMENT SYSTEM #
****

## Table of Contents##
###</br>I. 	Overview
###II.	Data Model
###III.	Roles
###IV. Use Cases
#### 1. Overview
Library management System is designed, so that it will help both library and user.Library System is intended to Automate the library activities such as adding new books, giving books to the borrowers, maintaining the details of all the details of the book. It will help in managing the track of the book issued, available copies with auto reminder feature for sendind the mail/sms to the borrower. The Database  This also helps the librarians by providing information such as total copies available each book, list of books that belong to a particular category 

###2.	Data Model:
There are two models in the Library management system.
</br>1. Book List
</br>2. Book Issue List

</br>**A. Book List**
</br> 	It display the list of books, there is filter for various attributes of the book, the user can search the book by name, author, publisher, language. It also displays the location of the book, total copies and available copies
Following are the attributes of the Book List table
<p>	a. Name: 
		</br>
		Enter the book name that will be displayed in the book list.
		<p>b. Author:
		</br> Specify the author to the book name
		<p>c. Publisher: 
		</br>Enter the name of the publisher for book.
		<p>d. Language:
		 </br>The book is available in various lannguage including English, Hindi, Marathi.
		<p>e. Location:
		</br>It shows where the book is located.
		<p>f. Total Copies:	
		</br>It display the total number of copies are present for book issue, the total number of copies will increase when the books are added.
		<p>g. Available Copies:
		</br>It displays the total number of available copies, after issuing of the book the available copies will be decreased as per the books are issued and after book is returned it will be added to availabe copies list.
###III. Roles:
a. Library Administrator
</br>The library administrator can able to perform the basic operation including add, update, delete. He helps the user to issue the book. He also able to upload the book data in bulk.

b.User
</br>
The user can only able to search book and request the book for issue, he is also responsible for the due date, if he failed to return the book before return date.
###IV. Use Cases 
**A. For Library Administrator**			
</br>a. Add Book
</br>You can the book by filling the attributes of the book(Name, Author, Publisher, Language, Location, Total Copies, Available Copies), and then click on the submit button to add book and it will display the book on the grid after submitting it. If you want to cancel the addition of book then click on Cancel button.
<p>b. Edit Book 
</br>
	To edit the selected book edit click on the pencil button to edit. You must select a row that you want to edit.If you don’t select row and clicks edit button, then it will say “Please select a row. Select row that you want to edit and edit the attributes of the book that you want click on Submit button, click on cancel to cancel book editing. There is forward and backward button available if you want to move from one row to another for editing.
<p>c. Delete Book
</br>
	To delete particular book, select the book from row that you want to delete and click on delete button.
<p>d. Issue Book
</br>Select the book you want to issue and click on the issue button to issue book, user can only issue only those books which are available in catalogue. To issue book enter Individual name, it will automatically fetch the contact and email. Click on Modify contact checkbox if you want to change the contact number. Enter comments if you want, click auto reminder, if you want to give automatic reminder, the automatic reminder feature will enable to send automatic sms to book borrower for due date. Click submit to submit book issue.  When you issue book it will automatically generate due date. You will not able to select the books which are not available. Click Cancel to cancel it.
</br>
</br>e. Book Return:
After the book is renewed the book will be available in the available list.
</br>f. Book Renew:
The Due date of the borrower will extend when the book is renewed
</br>g. Bulk Upload:
</br>Bulk Upload is used to uploading the book data in bulk.

**B. For User**
</br>1. Search Book:
</BR>You can the search the book by name, author, publisher, location. 
</br>3. Request book for issue:
</br>After you found the interested book, you can issue the book by asking librarian for issue of the book. You have to return the book within the 14 days from the date of issue. You can renew the book if want it further, before Due Date.
</br>4. Request for book return: 
</br>The User should return the book before Due Date.