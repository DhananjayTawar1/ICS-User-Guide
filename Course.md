# USER GUIDE FOR COURSE MANAGEMENT SYSTEM
****
## Table Of  Contents

####I. Overview
####II. Data Model
####III. Role
####IV. Use Cases

###I. Overview
Course Management System is intended to Automate the Course activities. It will help both the Course Administrator and Partitcipant The Course Administrator can able to create the course, update and delete it. There is Master Course function which will help in creating the course(e.g:Mastrer Course->DYS,then course like->DYS 2016), it will manage the record of the participant in the course.

 
###II.	Data Model
In Course System there are three section as follows:
</br>1. MasterCourse Model
</br>2. Individual/Participant Model
</br>4. Payment Model
</br>3. Event Model
 

	
</br>**1. Master Course Model**

####i.*Master Course*
Here only Admin can create a master course which is a unique name, treated as base course for creaating other courses. All master course will be shown in the MasterCourse list including Name, Type, Category and MasterCourseRequisites,RequisitesBooks where the course administrator can create, edit and delete a master course.
</br>**a.** ***Name:***
</br>This is the title of a mastercourse based on which batch course/general
course will be created,  the batchcourse can be different but need to be related of that mastercourse, it will not accept special symbols/charecters like %,# etc.

***b. Type:***
</br>The type of the master course it can be of the different type for e.g.online, offline.

***c. Category:*** </br>A specifically defined division of the master course for e.g. for Brahmachari, Grihasta etc.

**d.** ***PrereqBooks:***</br>
</br>This field describes the Books that are required for that particular course.

**e.** ***PreqMasterCourses :***</br> Master Courses need to be completed to apply this master course.
To create a master course goto master Course page(by clicking mastercourse button on the top bar of course page near home button).Then on the bottom of the table  click '+' and fill up the required information like: MasterCourseName,Category etc and click save(near '+' button). After creating a master course go for creating a course at the course page as as given in the Course model.

####</br>ii.	Course Model :
Here only Admin can create one or more batch course/general course related to a master course. All batch course will be shownCourse list is the description of the pursuing course including Name, Description, Type, Category and MasterCourse where the course administrator can create, edit and delete the course.Later this course can be assigned to the registered participants.Every course is further divided into events.One course may have more than one events according to the duration of the course.For event details check event model.
<P> **a.** ***Name :***
</br>This is the title of the pursuing course, new title for the course can be added and the existing course title can be edited, it will not accept special symbols/charecters.

***b. Description:***
</br>It is a brief summary of the topics covered in a particular course,which describes about the subject matter, approach, breadth, and applicability of the course.

***c. Type:***
</br>This is the list of the course including the name of the name of the course,   the type of the course varies from time, place and circumstance, for e.g.online,offline, self study etc.

***d. Category:***
</br>A specifically defined division of the course Category, it means the for who the course is? it may be general course, for Grihasta, Brahmachari, Prabhuji, Mataji, Children etc.

**2. Participation Model:**
</br>Displays all the participants for a particular course(when select a course from the course list).	 


***a. LegalName:***
	 </br>This is the real name of the person as per the identity proof.

****b. Initiated Name:***
	 </br>This is the name of the devotee which he got from spiritual master at the time of initition

***c. Reference:***
</br>	 To give some reference.

***d. Phone:***
</br>	 Mobile number of the devotee.

***e. Email:***
</br>	 Email address of the person.

***f. Date of Birth***
</br>	 Date of Birth in the DD/MM/YYYY formate.

***g. Date Of Reg***
</br>	 Date of the registration, to enter the date select click on the Date of Reg textbox this is  in the DD/MM/YYYY formate, so add accordingly.

***h. Course Material Status***
</br>	 Status of the course material. For e.g. the course materil is issued or not.

***i. Payment Status***	 
</br>Statement of the payment whether received or not.


***j. Comments***
</br>	 Remark expression an opinion or reaction.

***k. Remarks***
</br>	observation.
</br>***l.	 Status***
Active or not.
 Payment and export operation can be done here. This model consist of several attributes, explained below:

 If individual has not registered yet, then add that individual by clicking add('+') button(bottom of the individual course list) and giving the individual details in the dailog. Admin can also delete and change individual course details except changing ICS ID  

####3.Event Model:
Event List is the schedule of the Course, it includes Title, Venue, StartDate, End Date, Contact Person, Attended,Absent.

***a.Title :***
</br>It is name for the event of the course, The administrator must give the name for the course.

***b.Venue :***
</br>Venue is place where the course takes place, for e.g. temple, VOICE, Home etc.

***c.Start Date :***
</br>Start Date is the date which indicates the starting date of the course

***d.End Date :***
</br>It displays the Date which indicates the date for End of the Course.


###III. Roles:
Course administrator can add, update or delete the course, he can also able create, update or delete the Master Course and the course. Course Administratror can able to do payment(s), event operation

###IV. Use Cases
For user must check for the particualr course check whether masterCourse is present or not.
 
####A.	For Course
***a.	Add Course:***
	</br>	
	To add new Course choose  the "+" from the first table, enter the name, description it will add the , enter the details and select the MasterCourse that you have created
	
***b.	Edit:***
</br>
 Select edit click on the pencil button to edit. You must select a row that you want to edit.If you don’t select row and clicks edit button, then it will say “Please select a row. Select row that you want to edit and edit the attributes of the Course that you want click on Submit button, click on cancel to cancel course editing. There is forward and backward button available if you want to move from one row to another for editing.

***c. Delete:***
	</br>
		To delete particular Course, select the Course from row that you want to delete and click on delete button.

***d.Reload***		
</br>
It refreshes the current table and after selecting Reload, it will update the chages that are made in the table.


 ***e.Mark Absent:***
	</br>It displays dialog "Are you sure" press "Ok" to proceed and "Cancel" to cancel, we have to select the Individual and event, otherwise it will display dialog "Please select Individual and event."

***f. ByIcsID:***
</br>If admin wants to assign many participants for particular course at a time then select a course and then click on ByIcsid button(present at the bottom of Individual Course List), on the dialog box put the ICS ID of the  registered Inidividuals seperated by comma, then click on the submit.
####B.For Master Course:
Following are the opeartions that can be performed on the MasterCourse.
</br>
***a.	Add Course***	</br>	
To add new MasterCourse click on the "+", it will add the MasterCourse
</br>

***b.	Edit:***
	</br>
	 To select MasterCourse edit click on the pencil button to edit. You must select a row that you want to edit.If you don’t select row and clicks edit button, then it will say “Please select a row. Select row that you want to edit and edit the attributes of the MasterCourse that you want click on Submit button, click on cancel to cancel course editing. There is forward and backward button available if you want to move from one row to another for editing.
	
***<P>c. Delete:***
</br>
To delete particular MasterCourse, select the MasterCourse from row that you want to delete and click on delete button.
***<P>	d.	Reload Grid***
</br>
	It refreshes the current grid.
***<P>e. Bulk Upload:***
</BR>Upload bulk is used to upload the MasterCourse catalogue, it must be in csv file.
For uploading MasterCourse data, click Browse->Select File->Open(it must have .csv extension)->Click on Upload MasterCourse It will update the current MasterCourse data.

	