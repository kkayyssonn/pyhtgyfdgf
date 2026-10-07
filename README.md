Project Overview
I made a system that calculates and display student names, grades and their average grades. Its purpose is to display
each as simple as possible for all the students

Setup Instructions
1. The program will prompt the user to choose a number of choice between 1 and 7. Obviously since the program does
   not have any input, the user will have to choose option 1 to add student(s).
2. After selecting choice 1, the student must now enter each student's name, and grades for each subject. 
3. The user now has the options of updating, removing, viewing and searching student data.
4. The show summary (option 6.) is to display each student's grades and their average grade

Features List
- Add student: function that adds new students together with their grades
- Update student: function that modifies or changes the grades of an existing student
- Remove student: removes a chosen student's data
- View subject grades: displays a list of all student's grades for a specific subject
- Search student: finds a specific student by name and displays their grades and average
- Summary table: prints a table showing all the student's grades and the averages for each subject

Class Architecture
I have not used any classes, instead I used functions 

Example Input/Output


Assumptions and Limitations
Case sensitivity: student names are case-sensitive. E.g. Phemo and phemo are treated as 2 different people
Grade range: grades are limited to only numeric values that are in between 0 and 100
Data storage: when the program is stopped or is exited, all student data is lost

Testing Summary
<img width="1920" height="1080" alt="Screenshot (237)" src="https://github.com/user-attachments/assets/fa587db8-c446-467f-913e-36d56afe30aa" />



Known Issues
I had issues with asking for grades for each subject and i solved this by adding a while true loop 
