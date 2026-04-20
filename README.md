
🏥 Project Title

Hospital Resource Management System using CRUD Operations with Dynamic Memory Allocation in C




👥 Team Members

Student 1:P.Uday Kumar


Student 2:Hari charan




📍 Problem Statement

Managing hospital records manually is inefficient, time-consuming, and prone to errors. Hospitals need a system that can dynamically store, update, retrieve, and delete patient information without memory limitations.
This project provides a solution using a linked list-based system that efficiently handles patient data through CRUD operations in a menu-driven program.






🧱 Data Structure Used

Singly Linked List

Each node represents a patient record containing:

Patient ID
Name
Age
Disease
Pointer to next node

Why Linked List?

Dynamic size (no fixed limit like arrays)
Efficient insertion and deletion
Memory allocated at runtime





⚙️ Algorithm Explanation
1. Add Patient (Create)
Step 1: Allocate memory using malloc()
Step 2: Read patient details
Step 3: Create a new node
Step 4: Insert node at the end of the list
Step 5: Update links


2. Display Patients (Read)
Step 1: Start from head
Step 2: Traverse until NULL
Step 3: Print each node’s data



3. Search Patient
Step 1: Input Patient ID
Step 2: Traverse list
Step 3: If ID matches → display record
Step 4: Else → show “not found”


4. Update Patient
Step 1: Input Patient ID
Step 2: Traverse list
Step 3: If found → update details
Step 4: Else → show “not found”



5. Delete Patient
Step 1: Input Patient ID
Step 2: Traverse with previous pointer
Step 3: Adjust links to remove node
Step 4: Free memory using free()

6. Exit
Step 1: Free all allocated memory
Step 2: Terminate program






💻 Compilation Instructions

Using GCC Compiler:
gcc hospital.c -o hospital
./hospital

Steps:
1.Save the code as hospital.c
2.Open terminal / command prompt
3.Compile using gcc
4.Run the executable file


<img width="639" height="347" alt="Screenshot 2026-04-20 120350" src="https://github.com/user-attachments/assets/7f2da774-36c8-4aee-a4f2-82f9134cb378" />
<img width="608" height="353" alt="Screenshot 2026-04-20 120401" src="https://github.com/user-attachments/assets/39309ffb-b2ed-4e43-9307-11c9e01654a3" />
<img width="638" height="289" alt="Screenshot 2026-04-20 120446" src="https://github.com/user-attachments/assets/9c5a376c-a9d7-4d0b-ae8f-b6b0c698e02c" />
<img width="638" height="369" alt="Screenshot 2026-04-20 120454" src="https://github.com/user-attachments/assets/d13b5b96-4617-4f3e-803b-b9a05be354f8" />
<img width="633" height="325" alt="Screenshot 2026-04-20 120503" src="https://github.com/user-attachments/assets/6ef8cb7d-1e31-4314-9fa6-39e53b889aeb" />
<img width="659" height="323" alt="Screenshot 2026-04-20 120512" src="https://github.com/user-attachments/assets/e5b97d08-a406-472e-9961-1eb8dd51ca30" />
<img width="631" height="249" alt="Screenshot 2026-04-20 120521" src="https://github.com/user-attachments/assets/2fcfc755-f288-4ac8-b27f-1369134a0519" />







📁 Files Used
hospital.c → Main source code





⭐ Features
Menu-driven interface
Dynamic memory allocation
Efficient data handling using linked list
CRUD operations:
1.Add patient
2.Delete patient
3.Update patient
4.Search patient
5.Display all patients
No fixed memory limit
Easy to use and understand





✅ Conclusion

The Hospital Resource Management System successfully demonstrates the use of linked lists and dynamic memory allocation in C. It efficiently performs CRUD operations and overcomes the limitations of static data structures. This project provides a strong foundation for real-world applications like hospital databases and management systems.
