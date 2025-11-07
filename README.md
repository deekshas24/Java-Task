# Java-Task
Student Exam Score Logger
This project simulates students submitting exam scores at the same time using multithreading. Each thread writes a student's name, roll number, and marks into a CSV file, and the writing process is kept thread-safe using synchronized.

Features:
1.Multiple threads writing to the same file
2.Thread-safe file handling
3.Stores data in results.csv
4.JUnit tests for file writing and thread completion
