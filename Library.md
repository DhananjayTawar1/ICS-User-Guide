# USER GUIDE FOR LIBRARY MANAGEMENT SYSTEM #
****

## Table of Contents##
##I. 	Overview
##II.	Data Model
##III.	Roles
##IV. Use Cases
</br>
</br>
## `I. Overview`
Library management System is designed, so that it will help both library and user.Library System is intended to Automate the library activities such as adding new books, giving books to the borrowers, maintaining the details of all the details of the book. It will help in managing the track of the book issued, available copies with auto reminder feature for sendind the mail/sms to the borrower. There is  details of the book also helps the librarians by providing information such as total copies available each book, list of books that belong to a particular category 

##`2.	Data Model`
There are two models in the Library management system.
</br>1. Book List
</br>2. Book Issue List
###1. Book List
It display the list of books, there is filter for various attributes of the book, the user can search the book by name, author, publisher, language. It also displays the location of the book, total copies and available copies
Following are the attributes of the Book List table
<p>***a. Name :*** 
		</br>
		This is the name of the book, the administrator can search particular book by entering the name of the book.
		***<p>b. Author :***
		</br> This is the name of the author of the book, the user can serach the book of the particular author by entering the name of the author in the author textbox. 
		***<p>c. Publisher :***
		</br>This is the name of the publisher of the book, here the name of the publisher of the book is given the book of the particular publihser can be 
		***<p>d. Language :***
		 </br>This field indicates the language of the book, the books will be available in the various languages for e.g. English, Hindi, Marathi etc.
		***<p>e. Location :***
		</br>It shows where the book is located.
		***<p>f. Total Copies :***	
		</br>It display the total number of copies are present for book issue, the total number of copies will increase when the books are added.
		***<p>g. Available Copies:***
		</br>It displays the total number of available copies, after issuing of the book the available copies will be decreased as per the books are issued and after book is returned it will be added to availabe copies list.
##`III. Roles`
***a. Library Administrator :***
</br>The library administrator can add books, update book details, delete book. He helps the user to issue the book. He also able to upload the book data in bulk.

***b.User :***
</br>
The user can only able to search book and request the book for issue, he can able to see whether the book is available or not(Yes or No)
##`IV. Use Cases` 
###A. For Library Administrator			
***a. Add Book :***
</br>To book add book go to 'Book List'->Click on the '+' button, then fill the details of the book(Name, Author, Publisher, Language, Location, Total Copies, Available Copies), and then click on the submit button to add book and it will display the book in the 'Book List' after submitting it. To cancel the addition of book then click on Cancel button.
***<p>b. Edit Book :***
</br>
	To edit the book details select the edit book that you want to edit, then click on the pencil button to edit, Then Edit Record dialog will appear, To edit the book it is necessary to select the book. If you don’t select row and clicks edit button, then it will say “Please select a row. After selecting the edit button, edit the attributes of the book that you want to edit.To cancel book editing select the cancel button. In the 'Edit Record the forward backword button available to navigate up and down.
***<p>c. Delete Book :***
</br>
	To delete particular book, select the book from row that you want to delete and click on delete button.
***<p>d. Issue Book :***
</br>Select the book you want to issue and click on the issue button to issue book, user can only issue only those books which are available in catalogue. To issue book enter Individual name, it will automatically fetch the contact and email, if the contact and email is already present otherwise it need to enter manually. Click on Modify contact checkbox if you want to change the contact number. Enter comments if you want, click auto reminder, if you want to give automatic reminder, the automatic reminder feature will enable to send automatic sms to book borrower for due date. Click submit to submit book issue.  When you issue book it will automatically generate due date. The borrower  will not able to select the books which are not available. The Due Date for the book is generated when the book is issued Click Cancel to cancel it.

***e. Book Return :***
</br>
***f. Book Renew :***
</BR>After the book is renewed the book will be available in the available list.The Due date of the borrower will extend when the book is renewed
may be renewed but once the renewal limit is reached, the item must be returned before it can be checked out again

***g. Bulk Upload:***
</br>Bulk Upload is used to uploading the book data in bulk.
<br>
<br>

###B. For User
***1. Search Book :***
</BR>You can the search the book by name, author, publisher, location. 

***3. Request book for issue :***
</br>After you found the interested book, you can issue the book by asking librarian for issue of the book. You have to return the book within the 14 days from the date of issue. You can renew the book if want it further, before Due Date.

***4. Request for book return :***
</br>The User should return the book before Due Date.