# USER GUIDE FOR COURSE MANAGEMENT SYSTEM
****




## Table Of  Contents

####I. Overview
####II. Data Model
####III. Role
####IV. Use Cases

####I. Overview
Course Management System is intended to Automate the Course activities. It will help both the Course Administrator and Partitcipant The Course Administrator can able to create the course, update and delete it. There is Master Course function which will help in creating the course(e.g:Mastrer Course->DYS,then course like->DYS 2016), it will manage the record of the participant in the course.

 
####II.	Data Model
In Course System there are three section as follows:
</br>1. Course Model
</br>2. Individual/Participant Model
</br>3. Event Model
 

**A.	For Course**	
**1. Master Course Model**
**For Administrator**
</br>Here only Admin can create a master course which is a unique name, treated as base course for creaating other courses. All master course will be shown in the MasterCourse list including Name, Type, Category and MasterCourseRequisites,RequisitesBooks where the course administrator can create, edit and delete a master course.
<P>1.Name:
</br>This is the title of a mastercourse based on which batch course/general
course will be created,  the batchcourse can be different but need to be related of that mastercourse, it will not accept special symbols/charecters like %,# etc.
</br>2. Type:
The type of the master course for e.g. Monthly,Weekly,Daily
</br>3. Category: The type of the master course for e.g. online,offline
</br>A specifically defined division of the course Category is the collecion of.
</br>4. PrereqBooks: Books required for the course.
</br>5. PreqMasterCourses **:** Master Courses need to be completed to apply this master course.
To create a master course goto master Course page(by clicking mastercourse button on the top bar of course page near home button).Then on the bottom of the table  click '+'
and fill up the required information like: MasterCourseName,Category etc and click save(near '+' button). After creating a master course go for creating a course at the course page as as given in the Course model....

</br>**1.	Course Model :**
</br>Here only Admin can create one or more batch course/general course related to a master course. All batch course will be shownCourse list is the description of the pursuing course including Name, Description, Type, Category and MasterCourse where the course administrator can create, edit and delete the course.Later this course can be assigned to the registered participants.Every course is further divided into events.One course may have more than one events according to the duration of the course.For event details check event model.
<P>1.Name:
</br>This is the title of the pursuing course, new title for the course can be added and the existing course title can be edited, it will not accept special symbols/cherecters.
</br>2.Description:
</br>It is a brief summary of the topics covered in a particular course,which describes about the subject matter, approach, breadth, and applicability of the course.
</br>3. Type:
The type of the course including the name of the pursuing/pursued course for e.g.
</br>4. Category:
</br>A specifically defined division of the course Category is the collecion of .
**For User**
**2. Participation Model:**
</br>Displays all the participants for a particular course(when select a course from the course list). Administrator can add both registered and unregistered individuals by using by ICS ID button and add('+')  respectively. Payment and export operation can be done here. This model consist of several attributes, explained below:


If admin wants to assign many participants for particular course at a time then select a course and then click on ByIcsid button(present at the bottom of Individual Course List), on the dialog box put the ICS ID of the  registered Inidividuals seperated by comma, then click on the submit. If individual has not registered yet, then add that individual by clicking add('+') button(bottom of the individual course list) and giving the individual details in the dailog. Admin can also delete and change individual course details except changing ICS ID  

**3.Event Model:**
</br>Event List is the schedule of the Course, it includes Title, Venue, StartDate, End Date, Contact Person, Attended,Absent.

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
</br>Following are the opeartions that can be performed on the MasterCourse.

1.	Add Course
	</br>	
To add new MasterCourse click on the "+", it will add the MasterCourse
</br>
2.	Edit:
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

	