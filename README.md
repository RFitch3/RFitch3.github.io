# RFitch3

## Self Assesment

- ### Discuss how completing your coursework throughout the program and developing the ePortfolio has helped you showcase your strengths, shape your professional goals and values, and prepare to enter or become more employable in the computer science field.

&emsp;Throughout this course, and throughout my time at SNHU, I believe that I’ve displayed several skills that are essential to success in the field of Computer Science.

&emsp;The first skill I’ve shown is an ability to quickly learn and adapt to new information. You can see this throughout the project where I challenged myself by incorporating things into the project that I had little to no knowledge about before incorporating them. Although I had some experience working with state machines, I had never built one from scratch. Similarly, I’ve had experience working with databases, but had never worked with SQLite, or databases in C++ in general. For both of these, I needed to research the topics, so I could find the most fitting solution to my system’s needs. This not only helps demonstrate my ability to learn, but my overall knowledge and skill in software engineering and database design.

&emsp;I’ve also demonstrated my ability to learn throughout my time at SNHU in several other ways. One way this can be seen is through looking at my completed artifact compared to the original. I made the original in one of my earliest courses at SNHU and applied what I’ve learned throughout my other courses to enhance the project. For example, in CS-300 I learned about data structures and algorithms, which included how to research and choose the data structure or algorithm that best fits the system requirements. I demonstrated this in my project by researching sorting algorithms that would best work in the system that I was working on, then after choosing to use quicksort, researching and choosing a partition algorithm that helped me reduce the average time complexity, by making the worst-case scenarios less likely.

&emsp;The next skill that I have exhibited throughout my time at SNHU is my critical thinking skill. Critical thinking is crucial for problem solving, making it a key skill to have in software design and development. Throughout my time at SNHU, I’ve used my critical thinking skills to help me through each course, designing projects, and fixing any issues that arose along the way.

&emsp;I’ve learned how to analyze and design systems to get the most out of the system while avoiding its weaknesses. This can help me in a team setting where I may need to write documents or communicate my ideas to a team. It also allows me to better understand the opinions of other team members and stakeholders, which allows collaboration to find the best solutions possible.

&emsp;Finally, a key skill that I learned throughout my time at SNHU is how to think with a mindset for security. I’ve learned ways attackers try to gain access to a system, how to prevent or limit these attacks, and how to design and build the system with security being a focus from the ground up.  This is shown throughout my work by using industry best standards and practices, as well as ensuring the system is safe by using things such as input validation and parameterized queries.

- ### Summarize and introduce how your artifacts fit together and inform the portfolio as a whole.

&emsp;For my project, I chose to focus on a single artifact, building a fuller and more complete system throughout the course. The original artifact simply allowed the user to put in investment information, and see a year-end report, which output a report with and without a monthly deposit. I chose this because I saw a lot of room for improvement in it, as it was pretty bear bones, and was created in one of my earliest courses at SNHU.

&emsp;I started work on this project by adding a login screen, which simply saved user data to a .txt file, and parsed through the file to check if a user entered valid login data. I then realized that I would need to add a way for the user to navigate, settling on the solution of using a state machine to manage the states and navigation throughout the system. After some research I decided to add a Singleton StateMachine class, which held an enum of states, and several methods to handle the state machine functionality. I used this class originally to navigate through the login screen, main screen, and to cleanly exit the program. I then cleaned up the code, to make it simpler and easier to read and maintain, before submitting the first enhancement.

&emsp;My work on the second enhancement started by adding a bitwise XOR encryption algorithm, to protect the user’s login information. Although this wasn’t the most secure way to handle the data, I felt like it was a good choice to show my skill in working with algorithms for the project. Likewise, I decided to create my own sorting algorithm instead of using the built-in sorting functions, to show my skill in this area as well. After research I settled on a quicksort algorithm, using random partitioning to help avoid the worst case time complexity. This function has a best and average case of O(n*log n), and the worst case of O(n^2), so avoiding the worst case is vital to the speed of this algorithm. I also researched using other data structures to hold the data, but the only data structure that truly made sense was the C++ standard library vector. I also needed to learn how to use C++ templates, so I could sort the vector using any of the Investment variables. This allowed me to write a single quicksort function, instead of repeating the code for each variable I wanted to sort by.

&emsp;For my final enhancement I decided to add a database with two tables to store user login data and allow the user to save investments. I researched different databases that could be used, and settled on SQLite, as it was lightweight and serverless. Although I had previously worked with MySQL before, I had experience with SQL, I hadn’t worked with SQLite, so I had to quickly learn about how it worked before I could add it to my system. After learning about SQLite, I added it to my project, adding a table and database functions for both users and investments. Adding the ability for users to save investments also meant that I needed to adjust the state machine. I ended up adding three more states, to allow the user to navigate throughout the system in a smooth way.

&emsp;Finally, I cleaned up my code, finishing anything I wasn’t able to get done before, such as improving my input validation and adding a delete function to the investments database class. Overall, I think this project shows a wide array of my skills, and demonstrates what I’ve leaned throughout my time at SNHU. 

## Artifacts
<a href="https://github.com/RFitch3/RFitch3.github.io/blob/main/OriginalAirGeadBanking.zip">Original Air Gead Banking</a>

<a href="https://github.com/RFitch3/RFitch3.github.io/blob/main/AirGead.zip">Updated Air Gead Banking</a>

## Code Review
[MilestoneOne Code Review](https://youtu.be/hg0wpmSkva0)

## Author
- Robert Fitch III

## Repository
[Github Repository](https://github.com/RFitch3/RFitch3.github.io)
