# Word Length Calculator Project

This project is a simple Java application built with Maven that calculates the length of an entered word.

## Prerequisites

Before you begin, ensure you have the following tools installed:

- **JDK 8 or later:** [Download JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
- **Maven:** [Download Maven](https://maven.apache.org/download.cgi)

You can use your favorite code editor for this project. Microsoft VS Code is recommended but not mandatory.

## Project Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Shubhamlearn/Projectcal.git
The project has the following directory structure:

src/: Contains the source code of the project.

main/: Main source code.

java/: Java source files.

com/example/: Package structure.

App.java: Main application class.

test/: Test source code.

java/: Java test files.

com/example/: Package structure for tests.

AppTest.java: Test class for the application.

target/: Maven builds the project here. The generated JAR file will be located here.


Build the Project:

mvn package

Run the Application:

java -cp target/word-length-calculator-1.0-SNAPSHOT.jar com.example.App


Enter a Word:
Follow the prompt to enter a word, and the program will output the length of the word.
