**Online Exam System**
This project is a simple Online Exam System developed in Java using Swing for the graphical user interface (GUI). The system allows users to log in, take an online test, save their progress, and view their score at the end.

**Features**
1) User Login: Users are required to log in with a username and password.
2) Online Test: After logging in, users are presented with a series of multiple-choice questions.
3) Timer: A countdown timer tracks the time left for the test (10 minutes in this example).
4) Save and Next: Users can save their answers and proceed to the next question.
5) Save for Later: Users can mark a question for later review.
6) Result: At the end of the test, the system displays the user's score.
7) Questions: A set of predefined Java-related questions is included in the exam.

**Technologies Used**
1) Java Swing: For the GUI components like buttons, labels, radio buttons, etc.
2) AWT: For handling layout and event-driven programming.
3) Timer: To implement the countdown timer for the exam.
4) JOptionPane: For showing dialog boxes.

**Structure
Classes**
1) login: Manages the login process for users. It prompts for a username and password.
2) OnlineTestBegin: Contains the logic for the online test. It handles displaying questions, checking answers, and controlling the exam flow.
3) OnlineExam: The main class that starts the application.

**Key Methods**
1) actionPerformed(ActionEvent e): Handles user interactions like clicking buttons to save and proceed with the test or review answers.
2) set(): Displays questions and multiple-choice answers on the screen.
3) check(): Checks whether the user-selected answer is correct.

**Running the Project**
1) Clone or download the project files.
2) Open the project in your preferred IDE (e.g., Eclipse, IntelliJ IDEA, or Visual Studio Code).
3) Compile and run the OnlineExam.java file.
4) The login form will appear. Enter a username and password to start the exam.
5) Answer each question within the time limit and click Save and Next or Save for Later to proceed.
6) View the final score when all questions are answered or time runs out.
7) 
**Sample Login**
Username: Enter any name.
Password: Enter any non-empty value.

**Example Questions**
Who is known as the father of Java programming language?
Number of primitive data types in Java?
Where is the System class defined?
Which of the following is not an OOPS concept in Java?

**Screenshots**
Login Screen
Exam Interface
Result Screen

