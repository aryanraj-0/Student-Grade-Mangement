# Student-Grade-Mangement
Student Grades Management System 
A simple, menu-driven Python program designed to help teachers or administrators manage student grades efficiently. This Command Line Interface (CLI) application allows users to Perform CRUD operations (Create, Read, Update, Delete) on student records.<br/>
<br>
Features
Add Student: Create a new record with a student's name and their grade.
Update Student: Modify the grade of an existing student.
Delete Student: Remove a student from the records permanently.
View All Students: Display a clean list of all students and their current grades.
Input Validation: Handles errors if a user enters text instead of numbers for grades or menu choices.
Case Handling: Automatically formats names (e.g., "john" becomes "John") to ensure consistency.<br/>
<br>
Prerequisites
Python 3.x installed on your system.
No external libraries are required (uses standard Python functionality).<br/>
<br>
Code Structure
student_grades = {}: A global dictionary used to store data in Key:Value pairs (Name:Grade).
add_student(name, grade): Adds a new entry to the dictionary.
update_student(name, grade): Checks if a key exists, then updates the value.
delete_student(name): Removes a key-value pair from the dictionary.
display_all_students(): Iterates through the dictionary to print all records.
main(): The entry point of the program containing the while True loop and menu logic.<br/>
<br>
Future Improvements
File Handling: Currently, data is lost when the program closes. A future update could save data to a .txt or .csv file.
Grade Calculation: Add a feature to automatically calculate the class average or assign letter grades (A, B, C).
Author: [Aryan Raj]
Registration number:25BAI10693

<img width="1920" height="1080" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/92927c8e-0182-4820-9a38-58d4f9ce6803" />
<img width="1920" height="1080" alt="Screenshot (132)" src="https://github.com/user-attachments/assets/926a61eb-4ec4-4a95-9ad0-d877d5b82cc7" />
<img width="1920" height="1080" alt="Screenshot (133)" src="https://github.com/user-attachments/assets/94d1834d-d3f4-4600-a044-99033279c526" />






