ad student: 
The class Student represents a student.  Notice that neither count nor sNumber are passed to the constructor. These two fields also have no set method (mutator). 

ad count: Notice that count is underlined. This indicated that count is a static field. Count keeps a running count of the Student objects that have been created.  It is used to create a unique sNumber for each student  

ad constructors: The generated field sNumber needs to be initialized in both constructors. Create a unique 7 digit student number for each student based on the static field count. (e.g. 1234567 + count++) The parameterized constructor uses the values passed to initialize the fields. 

ad StudentApp:
StudentApp includes the main method .  Use private methods to structure code.  

ad main:
Create an ArrayList of students  that is initialized with 3 different students. Use a do-while loop and a switch statement to display a menu with choices and to respond to the user selections. Here is how the menu should look like: 1. Add a student     2. Find a student    3. Delete a student    4. Display all students 5. Display number of students in list 6. Exit   
The user should not be allowed to enter a student number because it is auto-generated. If a user tries to find or delete a student based on a student number that doesn’t exist, an appropriate message should be displayed. (see output) If a student is actually found or deleted corresponding student data should be displayed as part of the response



# Student-info-app
simple java project about student info at a college 
