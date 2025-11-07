🧾 Student Record Management System (C)


📘 Overview

This project is a Student Record Management System written in C language using a Singly Linked List.
It allows you to dynamically add, delete, search, and display student records.
The program demonstrates the concepts of structures, pointers, and dynamic memory allocation in C.

🧠 Features

Add new student records (ID, Name, Marks)

Delete existing records by ID

Search student details using ID

Display all student records

Menu-driven console interface

⚙️ Concepts Used

Structures (struct)

Pointers and dynamic memory (malloc, free)

Linked List traversal

String handling (strcpy)

🧩 Data Structure

Each student record is represented as a node in a singly linked list:

struct Student {
    int id;
    char name[50];
    float marks;
    struct Student* next;
};


🧮 Sample Output
--- Student Record Management (Linked List) ---
1. Insert Record
2. Delete Record
3. Search Record
4. Display All Records
5. Exit
Enter your choice: 1
Enter ID, Name, and Marks: 101 Luna 92.5
Record inserted successfully!

🎯 Learning Outcomes

Understanding linked list operations

Using dynamic memory allocation in C

Structuring programs using user-defined types

Implementing CRUD operations using data structures

✨ Author

Luna
🎓 B.Tech CSE (AI & ML) Student
💻 Passionate about coding, data structures, and building practical C programs.
