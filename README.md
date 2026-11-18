# PROG-POE-PART-3
Lisakhanya Iviwe Ngcongo
ST10537069

Overview of ChatAppLogin:

ChatAppLogin is a Java-based application designed to manage user authentication, login workflows, chat functionality, and message storage. It uses Apache Maven as its build automation tool and includes automated unit tests to verify system reliability.

Project Layout and Structure:

The project lives inside a root folder named ChatappLogin. 
Within this folder, everything is organized into the following areas:
pom.xml: The primary configuration file for Maven that defines project dependencies, build settings, and plugins. messages.json: A JSON data file used to store chat message records. Contains the automated test files used to check the code.Target Directory: An automatically generated folder created when you compile the project, containing compiled class files and testing reports.   

Core Components and What They Do

ChatApp.java: This file manages the main chat interface, user interactions, and active messaging features while the application runs.

ChatappLogin.java: This file handles the security logic, including user registration, credential verification, and sign-in management.

Message.java: This is the data model file that defines the structure, format, and properties of individual chat messages.

StoredMessages.java: This component handles message persistence, meaning it reads, writes, and saves chat history, working closely with the messages.json file.
