# universitymodel
project oveerview 
The university attendance management system is a simple java based concole application that helps universities or colleges manage student attendance. the system allows user to 
1)Add new students 
2)Mark attendance(present/absent)
3)view attendance reports
4)store data in memory using java collections 
the project is beginnner friendly and demonstartes OOP concepts like classes,objects, Arraylist and HashMaps.

Project Structure
src/
|--Student.java
|-- AttendanceRecord.java
|-- Main.java


Technologies Used
1)Java (JDK 8 or later)
2)OOP concept
3)Collection Framework(Arraylist,Hashmap)

Features
1)Add Student
 Stores student name,ID, And department

2)Mark Attendance 
Allow Marking Present/Absent for  any date

3)View Attendance 
Displays attendance records of a specific student 

4)Simple Coonsole Menu
Easy to run basic input/output

How to run the project

1)place file inside a directory like
|-AttendanceProject/src/

2)open terminal/CMD and navigate to src
|-cd Attendance/src

3)Compile the java file
|-javac *.java

4)Run the program
|-java main



Classes explanation 
1.Student.java 
stores:
.Student Name
.Student ID
.Department

2.AttendanceRecord.ajav
stores:
.Student object
.Dates + present/absent information(using hashmap)

3.Main.java
Contains:
.Menu System
.Logic to mark attendance
.View attendance report


Sample Output
== UNIVERSITY ATTENDANCE SYSTEM ==
1.Add Student
2.Mark Attendance
3.View Attendance Report 
4.Exit

Enter Student Nmae: Rahul
Enter Student ID:101
Enter Department: CSE
Student Added Successfully!
