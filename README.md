# Student Management System

##  Description
This project is a simple Student Management System that allows the user to manage two types of students:  
- Undergraduate students (UG)  
- Graduate students (GR)  


The system provides the following functionalities:
- Add a new student  
- Update GPA for an existing student  
- Delete a student  
- Display all students  
- Generate a report (sorted by GPA + average GPA per department)  
- Save records to a CSV file  
- Auto-save feature during runtime  

---

##  How the Program Works
1. When the program starts, it attempts to load student data from a students.csv file (if it exists).  
2. A menu is displayed with available operations:  
   - 1 – Add Student  
   - 2 – Update GPA  
   - 3 – Delete Student  
   - 4 – Display All Students  
   - 5 – Generate Report  
   - 6 – Save Records  
   - 0 – Exit  
3. After any operation is performed, the user returns to the main menu.  
4. When choosing “Save Records,” all data will be written to students.csv.  
5. On exit, auto-save will ensure everything is stored properly.

---

##  Technologies Used
- Language: Java  
- Concepts: OOP (inheritance, abstraction), exceptions, CSV file handling, collections (List), command-line UI  
- Tools: Any Java runtime environment (JDK 8+), or OnlineGDB  

---

##  How to Run
1. Open the project in any Java environment or Online GDB.  
2. Run Main.java.  
3. Follow the menu instructions.  
4. Check the folder for the generated students.csv file after saving.

---

## Features
###   I have two types of students, and their scholarships vary based on their GPA:
- Undergraduate Students (UG):  
  - GPA ≥ 3.7 → Scholarship: 1000  
  - GPA ≥ 3.0 → Scholarship: 500  

- Graduate Students (GR):  
  - GPA ≥ 3.5 → Scholarship: 1500  
  - GPA ≥ 3.0 → Scholarship: 800  

### Additional Features
- Generate a report that includes:  
  - Students sorted in descending order of GPA  
  - Average GPA for each department  
- Automatic saving during runtime via AutoSaver  





---

##  Notes
- Enter GPA in decimal format such as 3.45.  
- If I try to edit or delete a student who doesn't exist, the system will display an error message.  
- The program will automatically create students.csv if it does not exist.  

---

## Usage Purpose
This project was created for academic purposes.
