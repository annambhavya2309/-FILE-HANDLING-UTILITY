# -FILE-HANDLING-UTILITY

*COMPANY NAME* : CODTECH IT SOLUTIONS

*NAME* : ANNAM BHAVYA

*INTERN ID* : 

*DOMAIN* : JAVA PROGRAMMING

*DURATION* : 4 WEEKS

*JAVA FILE HANDLING UTILITY – Project Description*

The Java File Handling Utility is a simple, menu-driven console application designed to perform basic file operations such as writing, reading, appending, and replacing the content of a text file. Developed in Java using the java.io and java.util packages, this utility is an ideal starting point for beginners learning about file input/output (I/O) in Java.

The program operates on a text file named sample.txt. It provides users with a clear and interactive interface, allowing them to choose from five different operations: write to the file, read from the file, append to the file, replace file content, or exit the program. The use of standard Java classes such as FileWriter, BufferedWriter, FileReader, and BufferedReader makes this a practical demonstration of real-world file handling in Java.

 PURPOSE AND LEARNING OBJECTIVE:

The primary goal of this program is to introduce students and new Java developers to file manipulation techniques. In many real-world applications, it is necessary to store, retrieve, and update data that persists beyond the life of a program. Java’s I/O library supports these operations efficiently, and this utility provides a hands-on way to explore them.

By interacting with the program, users gain a working understanding of how to open files, write data to them, read data line-by-line, and safely manage file resources. Additionally, the utility showcases best practices in Java programming, including:

Use of constants (FILE_NAME) for maintainability

Try-with-resources for automatic resource management

Modular structure using well-defined methods

Input validation and exception handling

 Functional Overview

WRITE TO FILE:

This feature allows the user to write new content into the file. If the file already contains data, it is completely overwritten. The user can enter multiple lines until they type "exit" to finish input. Internally, it uses BufferedWriter with FileWriter in default (overwrite) mode.

READ FROM FILE:

This option reads the content of sample.txt and displays it line by line on the console. If the file does not exist, the program catches the FileNotFoundException and informs the user accordingly. This function uses BufferedReader and demonstrates safe and efficient reading of files.

APPEND TO FILE:

With this feature, users can add new content to the end of the existing file without altering its previous content. It also supports multi-line input, ending with the keyword "exit". This operation is ideal for maintaining logs or sequential updates in a file.

REPLACE FILE CONTENT:

This option replaces the file’s current content with new input from the user. Although functionally similar to the write operation, it is presented separately in the menu to clearly indicate its use as a replacement tool. It promotes code reuse by calling the writeToFile() method internally.

EXIT:

The exit option ends the application gracefully, ensuring that the Scanner and other resources are properly closed, preventing potential memory leaks.

CONCLUSION:

In summary, this Java File Handling Utility provides a solid foundation for anyone looking to understand the core concepts of file manipulation in Java. It balances simplicity and functionality, making it suitable for educational purposes, assignments, or personal projects. Developers can easily extend this project by adding advanced features like deleting specific lines, searching for keywords, or integrating a GUI.

OUTPUT:


