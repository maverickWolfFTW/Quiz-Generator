# Quiz-Generator
The purpose of the application is to simplify the knowledge test activity in the academic environment. The target group include those who study programming languages, employers who need people with a certain level of knowledge of language programs and who want to choose candidates with a certain outcome, recruitment of companies, etc.
The application involves completing a form by the user specifying the number
of questions the test will contain, the level of questions, the category of the question
(programming language), the language skills (programmer's skill in a language, Exam-
ple, JavaFX, Swing), the type of questions (Grid, Text, Boolean). All these questions
are stored in a basic relational relationship to which the algorithm based on java.util.Random applies. Generated multiple-response questions will be contained in a PDF file.

Technologies used for this application are:
 - I used Java as programming language in order to use Hibernate for data persistence with annotations.
 - As DB initially I used Derby DB but it was quite limited so I choose to go with MySql.
 - For GUI I used JavaFX for multiple reasons. Because I was eager to learn something new instead of Java Swing that I already knew and also because JavaFX have multiple functionalities and the libraries contains functions "cleaner" than function from Java Swing.
 - To form the test into a file I used IText PDF because this API is the leader of F/OSS and libraries are advanced than other ones. Initially I went with PDFBox but I've had to implement more functions to get what IText PDF already have. Because I had to deliver this project at particular time I switched to IText PDF.
