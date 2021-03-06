# Database
For my third enhancement, demonstrating my skills of working with databases, I am building off my previous enhancement language conversion of [Lab 1-3 from my Data Structures and Algorithms course](https://github.com/GregMacDev/CS-499-Software-Engineering/blob/main/Lab%201-3.txt){:target="_blank"}
created in May of 2020 and [converted from C++ to Java](https://github.com/GregMacDev/CS-499-Software-Engineering/blob/main/src/enhancement/App.java){:target="_blank"} in May of 2021. The enhancements I have performed for this project includes full implementation of a database to store the data used within the program. The initial purpose of the program was to demonstrate the functionality of a struct data type in C++. The conversion of the program from C++ to Java changed the data structure container from a struct to a Java class. The implementation of a database into this base program allows for storing multiple Java class objects to be used within the program.

I chose to continue working with my Lab 1-3 artifact as I felt the conversion from C++ to Java created a great base to continue expanding upon the functionality and complexity of the program, allowing me to demonstrate my understanding of developing and integrating a database to an existing program. The database implementation showcases my ability solve the problem of creating a central location for program data as opposed to storing the data in a container within the running program. I am using the Java Database Connectivity, or JDBC, library to communicate with the MySQL database used to store the program’s data. By implementing a database into the initial program, the functionality is expanded upon and improved by allowing the user to store and manipulate multiple class objects from within the program. The decision for this enhancement to integrate a database into the program allows multiple users to access the same dataset from separate instances of his program. The inclusion of a database also allows for future expansion of stored data for this program. Another aspect of creating the database functionality, which was developed in a separate database class file, I am illustrating my understanding of the value of modularity within the program. The database class file I have created can be integrated, with minor modifications, into other programs requiring database interactions.

The proposal for this enhancement from module one outlined my intentions to develop the implementation of the database functionality to add, delete, update, sort, and search the data stored in a MySQL database. The expectations of the proposal as they were presented have been met in my enhancement project. Furthermore, this enhancement was developed with a security mindset, anticipating adversarial exploit attempts, where I implemented mitigation techniques by validating user input, throughout. In future revisions, I am hoping to tighten up security around the SQL statements to produce a project I am more comfortable with, that closer aligns with my own standards.

I chose to implement a database into a program that previously did not include any database functionality to learn more about databases. Up to this point, my familiarity with databases came from issuing commands to databases that were already created and ready to accept connections. My project presented me with the opportunity to learn through documentation and tutorials the steps of installing a MySQL local server and connecting to it and issuing commands through the command line. From there, I learned about using the Java Database Connectivity, or JDBC, library to communicate with my newly created MySQL local server. This process consisted of reading documentation, following tutorials, and creating a test program to practice sending command and printing and formatting returned results. The biggest challenge I faced during this process was when I proceeded to integrate what I had learned in my test program into my main program. In my test program, all the functionality was contained in one file, whereas in my main program, I was developing a separate class file for the database commands. This slight difference created an issue connecting to the database, but once I was able to work out a solution to connect to the database, the remaining functionality to interact with the database came together rather quickly.


### Database Code Review and Demonstration
<iframe src="https://youtube.com/embed/q_cs_R-vRqM" 
    width="560" 
    height="315"
    frameborder="0" 
    allowfullscreen>
</iframe>

### Repository
[Enhancement Three](https://github.com/GregMacDev/CS-499-Database){:target="_blank"}

## ePortfolio Links
- [Main Page](https://GregMacDev.github.io/index.html)
- [Enhancement Plan and Code Review](https://gregmacdev.github.io/enhancement%20plan%20code%20review.html)
- [Enhancement One](https://gregmacdev.github.io/enhancementOne.html)
- [Enhancement Two](https://gregmacdev.github.io/enhancementTwo.html)
