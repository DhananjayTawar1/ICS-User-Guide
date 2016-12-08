# USER GUIDE FOR COURSE MANAGEMENT SYSTEM
****




## Table Of  Contents

####I. Overview
####II. Data Model
####III. Role
####IV. Use Cases

####I. Overview
Course Management System is intended to Automate the Course activities.

 
####II.	Data Model
In Course System there are three models as follows:
</br>1. Course Model
</br>2. Individual Model
</br>3. Event Model
 

#####A.	For Course	
#####1.	Course Model :
Here one can create a batch for a particular course. All batch course will be shownCourse list is the description of the pursuing course including Name, Description, Type, Category and MasterCourse where the course administrator can create, edit and delete the course.
<P>1.Name:
</br>ThIt is the title of the pursuing course, new title for the course can be added and   the existing course title can be edited, it can't contain the special symbols.
</br>2.Description:
</br>It is a brief summary of the topics covered in a particular course,which describes about the subject matter, approach, breadth, and applicability of the course.
</br>3. Type:
The type of the course including the name of the pursuing/pursued course for e.g..
</br>4. Category:
</br>A specifically defined division of the course.

**2. Participation Model:**
</br>Displays the participant for the selected course. Every Individual have ICS ID Select one course and add, If we want to add Individual for Course using ByICSID, we can add, then participant will be added.

**3.Event Model:**
</br>Event List is the schedule of the Course, it includes Title, Venue, StartDate, End Date, Contact Person, Attended,Absent.

**B.	For Master Course**
</br>1.Name:
</br>It is the title of the master course, new title for the course can be added and the existing course title can be edited.
</br>2. Type:
</br>The type of the course including the name of the pursuing/pursued Master course.
</br>4. Category:
</br>A specifically defined division of the Master course.

**III. Roles:**
</br>Course administrator can add, update or delete the course, he can also able create, update or delete the Master Course.
####IV. Use Cases
For user must check for the particualr course check whether masterCourse is present or not.
 
**A.	For Course**
</BR>a.	Add Course:
	</br>	
	To add new Course choose  the "+" from the first table, enter the name, description it will add the , enter the details and select the MasterCourse that you have created
	
b.	Edit:
</br>
 Select edit click on the pencil button to edit. You must select a row that you want to edit.If you don’t select row and clicks edit button, then it will say “Please select a row. Select row that you want to edit and edit the attributes of the Course that you want click on Submit button, click on cancel to cancel course editing. There is forward and backward button available if you want to move from one row to another for editing.

c. Delete:
	</br>
		To delete particular Course, select the Course from row that you want to delete and click on delete button.

**d.Reload**		
</br>
It refreshes the current grid.


 **e.Mark Absent:**
	</br>It displays dialog "Are you sure" press "Ok" to proceed and "Cancel" to cancel, we have to select the Individual and event, otherwise it will display dialog "Please select Individual and event."

**f. ByIcsID:**
</br> Bulk upload
	
**B.For Master Course:**


Following are the opeartions that can be performed on the MasterCourse.

1.	Add Course
	</br>	
To add new MasterCourse click on the "+", it will add the MasterCourse
	
<P>2.	Edit:
	</br>
	 The select MasterCourse edit click on the pencil button to edit. You must select a row that you want to edit.If you don’t select row and clicks edit button, then it will say “Please select a row. Select row that you want to edit and edit the attributes of the MasterCourse that you want click on Submit button, click on cancel to cancel course editing. There is forward and backward button available if you want to move from one row to another for editing.
	
<P>3. Delete:
</br>
To delete particular MasterCourse, select the MasterCourse from row that you want to delete and click on delete button.
<P>	4.	Reload Grid
</br>
	It refreshes the current grid.
<P>5. Bulk Upload:
</BR>Upload bulk is used to upload the MasterCourse catalogue, it must be in csv file.
For uploading MasterCourse data, click Browse->Select File->Open(it must have .csv extension)->Click on Upload MasterCourse It will update the current MasterCourse data.

	