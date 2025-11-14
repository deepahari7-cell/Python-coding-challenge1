# Python-coding-challenge1

Introduction to Programming Languages and Python   
 Project Title: Student Profile Creator  
Scenario:  
 You are helping to build a basic student information system for a local school. The school wants to store some basic details about each student and let them update their interests. 
Tasks:  
Create variables to store the student’s name, age, and their favourite subjects they are enrolled in.  
Display the student’s information in a user-friendly format.  
Display the updated list of subjects.  

INPUT:     
name="Suresh"     
name1="Mani"     
name2="Aanandh"     
name3="Balu"     
age=17     
age1=18    
age2=16    
age3=19    
subject="Maths"    
subject1="Science"     
subject2="English"    
subject3="ComputerScience"    
print("-----------------------------------------------------------")   
print("                  STUDENT'S INFORMATION                ")    




# Python-coding--challenge2
Student Data Management using Tuples and Lists 🧩 Overview

This project demonstrates how to store and manage student information and marks using Python data structures such as tuples, lists, and nested lists (2D and 3D). It shows how immutable personal data (tuples) can be combined with mutable mark lists for structured data handling.

🪜 Steps Performed Step 1: Create Tuples for Each Student

Each student’s personal information (ID, Name, Age, Department) is stored in an immutable tuple.

Example:

student_1 = (1001, "mani", 16, "IT")

Two batches are created:

Batch 1 (IT Department) → Students 1–4

Batch 2 (Maths Department) → Students 5–8

Step 2: Create 1D Lists for Marks

Marks of each student are stored in separate 1D lists.

Example:

marks1 = [88, 99, 100, 87]

Step 3: Combine Marks into a 2D List

Each batch’s marks are combined into a 2D list for better organization.

batch1_IT = [marks1, marks2, marks3, marks4] batch2_maths = [marks5, marks6, marks7, marks8]

Step 4: Combine All Batches into a 3D List

Both 2D lists (batches) are grouped into a 3D list:

All_batches = [batch1_IT, batch2_maths]

Step 5: Display Formatted Data

The program prints each student's personal details along with their marks in a formatted table-like view for clarity.

Example Output:

---------------Student Information and Marks-------------------- First batch Student's details:
St_ID Name Age Dept Marks
(1001, 'mani', 16, 'IT') [88, 99, 100, 87] (1002, 'mona', 18, 'IT') [82, 19, 87, 95] (1003, 'nani', 17, 'IT') [80, 99, 100, 77] (1004, 'kala', 18, 'IT') [85, 99, 85, 89]
Second batch Student's details:
(2001, 'Dee', 16, 'Maths') [84, 99, 96, 87] (2002, 'Dev', 18, 'Maths') [81, 19, 87, 95] (2003, 'Divi', 17, 'Maths') [85, 100, 100, 88] (2004, 'Diya', 18, 'Maths') [86, 99, 88, 89] ...............................................................
print("-----------------------------------------------------------")   
print("  Student'S Name  /  Age  /  Favourite Subjects            ")   
print("                                                           ")   
print(" 1.  ",name,"       ",age,"     ",subject)      
print(" 2.  ",name1,"         ",age1,"     ",subject1)   
print(" 3.  ",name2,"      ",age2,"     ",subject2)   
print(" 4.  ",name3,"         ",age3,"     ",subject3)   
print("                                                           ")  
print("-----------------------------------------------------------")   

print("  Updated List of Subjects:")   
print("-----------------------------")   
print("1.Maths")   
print("2.Science")   

# Python-coding--challenge3

#Create a 2D list where each row holds a contact’s name, phone number, and email address.
emp_details=[
    ["Archana", "9876543210", "alice@example.com"],
    ["Balu", "9123456789", "bob@example.com"],
    ["Charles", "9998887777", "charlie@example.com"],
    ["Dee", "9112233445", "david@example.com"],
    ["Eve", "9001122334", "eve@example.com"]
]
#Allow the user to add a new contact.
emp_details.extend([["Dev", "9058745622", "dev25@gmail.com"]])
emp_details

# Python-coding--challenge4

#Create a dictionary with student names as keys and their grades as values.

students= {
    "Arun": 92,
    "Brabhu": 85,
    "Chinna": 78,
    "Deva": 88,
    "Ethicraj": 95
}
students
#Allow the user to add or update grades for at least 3 students
students.update({"Chinna": 98})
print(students)

#Create a set of hobbies and allow the user to input at least 3 hobbies.

hobbies_set={"learning,knitting,cooking,writting,Gardening"}
print(hobbies_set)
#Convert the set of hobbies into a frozenset and display it.
frozen_hobbies_set=frozenset(hobbies_set)















print("3.English")   
print("4.ComputerScience")   
# Python-coding--challenge2
