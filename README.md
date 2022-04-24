# Project-4-Database
Microsoft Access is used for this project
 Project 4 will be finsihed on April 16th 2022
(UNDER CONSTRUCTION)

This college database contains student’s information and the classes at this college.
The goal is to create a school database and to create the queries, forms, reports, and a mailing address.

Creating data
Before I create the data. The first thing to do is to crate the columns. After the columns, then pick the data types that I want the data in the columns to displays.
I also do the same thing for creating Classes table

![](Students%20Column.png)

![](Students%20Data%20Types.png)


![](Students%20Data%20Values.png)

Classes

![](Classes%20Column.png)

![](Classes%20Data%20Types.png)

![](Classes%20Data%20Values.png)

Creation relationships
The goal is to create a relationship between the two tables. I want one student taking three classes. I am creating a one to many relationship between students and classes where one student is taking 3-5 classes. The studentID will also be in the classes table. With the craeting. For example one student is taking all business class while the other is taking engerring classes while other taking

![](Students%20and%20Classes%20Relationship.png)

Values
For students I created fictional names 
For class I created coming subjectd

Creating Queries
The first question I want to ask is how many students are taking Calculus III. In class name I will group by the total with the criteria of Like ‘Calculus III*’.  It will display those 4 students are taking Calculus III.

![](Query%20Number%20of%20Students%20in%20Calculus%20III%20Design%20View.png)

![](Query%20Number%20of%20Students%20in%20Calculus%20III%20Datasheet%20View.png)

Another question is how many students are taking summer school. In the design view I will the start date and will filter like from January 1st and July 31st. That is before August where majority of the students will take classes. The criteria used is >#1/1/2022# And <#7/31/2022# So there are 15 summer class and even thought studentDI shows uo mmnay times 4 students are taking summer classes

![](Query%20Students%20in%20Summer%20School%20Design%20View.png)

![](Query%20Students%20in%20Summer%20School%20Datasheet%20View.png)

Total Cost

![](Query%20Total%20Cost%20per%20Student%20Design%20View.png)

![](Query%20Total%20Cost%20per%20Student%20Datasheet%20View.png)

Total credits

![](Query%20Total%20Credits%20per%20Student%20Design%20View.png)

![](Query%20Total%20Credits%20per%20Student%20Datasheet%20View.png)

Creating Forms
A form is an object that allows you to enter edit or view your data. Three forms are created for this database.


The form will be created. To create frmStudents I used the create form option. It shows that Student 1’s information and the classes that are taking. As you change students, the classes they are taking changes change.

![](Student%20Form.png)

![](Student%20Form%202.png)

Classes’ Form
Another form created is frmClasses. To create frmClasses, I used to create form option. It shows Class 1’s information and the class name, section number, cost, and which student is taking this class.

![](Classes%20Form.png)

![](Classes%20Form%202.png)

Database Subform
Subform is created when fields from two or more related tables are used to create a form.
The form named tblClasses Subform1 is a subform. The subform contains all the class sections and the credit hours each class has. The main form named tblStudents1 contains one student and the classes they are taking and as the students change, the classes also change.

![](tblClasses%20Subform.png)

![](tblStudents%20Main%20Form.png)

Creating Reports
A report for Access as an object that summarizes the fields and records from a table or query in an easy-to-read format suitable for printing. Three reports will be created from this database.
First report is a collection of every class name and section and which class a student is taking.
![](Classes Report.png)
The second report is a collection every student’s information in the database.
![](Student Report.png)
The third report is Every student and every class they are taking.
Student Class Report.png

Creating Mailing Address
Creating a mailing for all the students in this database

![](Student's%20Mailing%20Labels.png)
Conclusion
