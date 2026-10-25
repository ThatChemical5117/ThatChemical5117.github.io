# E-Portfolio


## Self Assessment

Working through the Computer Science program at SNHU has help with developing skill in many aspects of Software engineering and development. One case of this is my course about agile development, where I learned about how to work in a agile envrionment. This type of development cycle is often used in professional and collaborative settings to make work faster and to quickly iterate through software design.
This course also helped with creating effective communication both in a team setting, and with corporate share holders. In many courses I needed to apply software engineering principles to effectively complete the assignments. A great example of this that is in this portfolio is CS-210 investment calculator application. There I had designed it with flexibility in mind and that allows for a better collaborative environment and for easier future changes.
In the CS-300 course I had worked with many different data structures and how algorithms could be used with them to make efficient and effective applications. This course allowed me to better learn about 


### Enhancement 1 - Software Design and Engineering

[CS-320 Appointment book before](https://github.com/ThatChemical5117/CS320-Journal-before)

[CS-320 Appointment book after](https://github.com/ThatChemical5117/CS320-Journal)

This artifact is the start of an Appointment/Contact/Task book. The course it came from was about testing and automation. The project was mainly created to display the ability to provide proper testing for a code base and was created in the summer of 2025.
I included this artifact in this ePortfolio due to it's potential as a fully implemented application. The current code in the artifact could be reused through the use of Design patterns, inheritance, and polymorphism.
Something that I learned while enhancing this artifact was about porting Java code to C++. I had never used the chrono library before so learning about it and using it to represent dates was very interesting. Something else that I learned was how to use gtest as a standalone library rather than including it in a Cmake file.
Typically gtest is included in a project through CMake, though I was using Makefiles for this project. I was able to find a solution to use gtest and provide good testing coverage for my project. Another challenge was adding additional features to the project without constantly going back and updating the previously written code. This required planning ahead and smart use of software design to achieve.

For the course outcomes of this enhancement, I meet both Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science and Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
I did this by creating a code base that is easy to extend and use, making it easy for new additions to be implemented. For the other course outcome I used software techniques and C++ features to meet the feature requirements of the software.

### Enhancement 2 - Algorithms and Data structures

[CS-210 Project 2 Investment Calculator Before](https://github.com/ThatChemical5117/Project2_before)

[CS-210 Project 2 Investment Calculator After](https://github.com/ThatChemical5117/Project2_before)

This artifact is an Investment calculator for a introduction into programming principles with C++. The calculator is text based and runs in a terminal. The user can input a principle amount, monthly contributions, interest, and term length to calculate the expected interest of an investment both with and without a monthly deposit. 
I wanted to include this artifact because of it's design. The application is written with encapsulation mind. This made changing the underlying algorithm very easy and non-intrusive. Though the artifact did have improvements already made to it, I did believe that there were better solutions. 
Through enhancing this artifact I came to better appreciate how important encapsulation is. With the artifact written well, I was able to come back to it after a long time and quickly re-familiarize myself with the code, then quickly make the changes required to enhance it. 

The course outcome I achieved with this artifact was: Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices. The new algorithm that I chose to replace the old one is simpler but does not have 100% parity with the old algorithm. That being it is off by a few cents to a few dollars depending on the amounts. 
I do believe that this is an decent trade off since this calculator only predicts an expected amount and doesn't need to be 100% accurate. The amount of loops required is reduced making the algorithm more efficient. 

### Enhancement 3 - Databases

[CS-300 Course Planner before](https://github.com/ThatChemical5117/CS-300-Project2_before)

[CS-300 Course Planner after](https://github.com/ThatChemical5117/CS-300-Project2)

This artifact is a course planner application that was written for my Data structures and algorithms class. The planner reads a CSV file and can then makes sure that each course's prerequisites is a line in the csv. 
I included this artifact because of how it can lend it's self for the use of a database. The artifact already uses a local file on disk for storage. In the enhancemnt I added a RestAPI to stand between the database and application. The application should be able to manipulate the database to add or remove through this API. This also allows for other application like a website to also view and connect to the database making new uses of the database easier. 
Much of the time I spent creating this artifact was finding and learning about creating a REST API in C++ and connecting to MongoDB through the C++ driver. I also had to find Json libraries in order to use json to send and receive messages from the web server. I was also able to learn more about the quirks about the C++ language and the libraries that I was using. 

The course outcome I achieved with this artifact was: Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources. When I was creating the REST API I made sure that the database key used to gain access to the database was not included in the version control software. I also use a special file loader to get the key dynamically instead of hard coding the key in the software. 
Additionally I also added a middlewear that runs before going to any of the routes that filters out invalid request bodies. This includes bodies that cannot be converted into json, preventing bad inputs from outside sources. While there is more that I could add these show how I preemptively cover obvious security issues before they become a problem. I also started to add the required routes to add new user and to login. 

### Code Review
