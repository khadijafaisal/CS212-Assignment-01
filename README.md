Library Management System
Description
The Library Management System is a Java application designed to manage books, users, and borrowing operations within a library. It provides functionalities such as adding new books, adding new users, checking out books to users, returning books, displaying books, and searching for books by title or author.

Setup and Running the Project Locally
Prerequisites
Java Development Kit (JDK) installed on your machine
Java IDE (such as IntelliJ IDEA, Eclipse, or NetBeans) or a text editor
Git installed on your machine (optional, if you want to clone the repository)
Steps
Clone the repository to your local machine using the following command:

git clone <repository-url>
Alternatively, download the repository as a ZIP file and extract it to your desired location.

Open the project in your Java IDE or text editor.

Compile and run the LibraryManagementSystem.java file.

Key Features and Functionalities
Adding Books and Users: Librarians can add new books to the library by providing book details such as ID, title, author, genre, and availability status. They can also add new users by specifying user ID, name, and contact information.

Checking Out Books: Users can borrow books by providing their user ID and the ID of the book they want to borrow. If the book is available, it will be checked out to the user.

Returning Books: Users can return borrowed books by providing their user ID and the ID of the book they want to return. The book will be marked as available in the library's inventory.

Displaying Books: The system allows librarians to display a list of all books in the library, including their details such as ID, title, author, genre, and availability status.

Searching for Books: Librarians can search for books by either the book title or the author's name. The system provides a convenient way to find books based on user input.

Error Handling: The system includes error handling mechanisms to prevent crashes and ensure data integrity. It handles scenarios such as invalid inputs, negative IDs, missing information, and contact information validation during user creation.

User-Friendly Interface: The user interface presents a simple menu-driven system, making it easy for librarians to perform various tasks efficiently.
