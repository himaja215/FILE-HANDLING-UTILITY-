# FILE-HANDLING-UTILITY-

*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : KONDAKAYALA REDDY HIMAJA 

*INTERN ID* : CT04DF358

*DURATION* : 4-WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION* :

The Java program titled FileUtility is a simple console-based file handling utility that allows users to perform basic operations on text files, including creating and writing to a file, reading from a file, and appending new content to an existing file. It is structured around a menu-driven interface within the main() method, which uses a while(true) loop to continuously prompt the user with four options: create/write a file, read a file, modify (append to) a file, or exit the program. The user input is read using a Scanner object, and based on the selected option, the corresponding method (writeFile(), readFile(), or appendToFile()) is executed.

The writeFile() method allows the user to create a new file or overwrite an existing one. It prompts the user to enter a filename (with a .txt extension) and the content to write. It then uses a FileWriter object to write the content to the specified file. If the operation is successful, a confirmation message is displayed; otherwise, an IOException is caught and an error message is shown. The readFile() method is responsible for reading the contents of a file specified by the user. It uses a File object and a Scanner to open and read the file line by line, printing each line to the console. If the file is not found, a FileNotFoundException is caught, and the user is informed accordingly.

The appendToFile() method facilitates modifying a file by appending additional content to it. It first checks if the specified file exists using the File.exists() method. If it does not exist, the user is notified and the method exits early. If the file exists, it prompts the user to enter new text to be added. A FileWriter in append mode (true flag) is combined with a BufferedWriter to write the new content to the file, starting from a new line for clarity. Exception handling is incorporated to deal with any IOException that may occur during the writing process.

Overall, the program follows a modular structure, where each function performs a specific task, making it easy to maintain and extend. It uses standard Java file I/O classes such as FileWriter, BufferedWriter, File, and Scanner. The code also includes basic input validation and exception handling to ensure smoother user experience and prevent runtime crashes due to common file-related errors. While the functionality is basic, it effectively demonstrates core concepts of Java file handling and user interaction through console-based input. Minor improvements could be made, such as better user prompts, input validation, and enhanced exception messages, but for a beginner or educational context, the program serves as a solid example of how to manipulate files in Java using standard libraries.

*OUTPUT* :

![Image](https://github.com/user-attachments/assets/5610d153-7a3e-4a03-bbbb-a9ef08a21001)

![Image](https://github.com/user-attachments/assets/ed8b944e-e638-4f58-8f46-f2549c79857c)
