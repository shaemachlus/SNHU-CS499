# SNHU-CS499
Computer Science Capstone Project

Professional Self-Assessment: 

My favorite aspect of the CS degree at SNHU is the variety of topics I was exposed to: QA testing, database management, mobile app development, and full stack development, to name a few. Each course came with a final project to display on my GitHub account, allowing me to showcase my strengths to employers and recruiters. This gives me a better chance at a job in the field, specifically at an IT Helpdesk, which is my goal. 

During my time at SNHU, I had the chance to collaborate with others through discussion boards. We would help each other out on the general questions board by posting our own questions and responding to our peers' questions, helping debug each other's code and solving other technical problems. One of my favorite courses was CS-300 Data Structures and Algorithms. I may have put the most work into this course because data structure and algorithm questions are ubiquitous in interviews. 

I also enjoyed learning about the software development life cycle and the different types of workflows (agile, TDD, waterfall) that exist in the industry. There was plenty of engineering experience, too, in classes covering client-server development, mobile app development, and full-stack development, to name a few. Using SQL to handle data in databases was also a great learning experience because of the importance of big data and cloud storage in many industries. The course on software security was a great introduction to cybersecurity. Privacy on the internet is increasingly essential since everything happens online these days.

The artifacts fit together nicely. I used the same code for each enhancement and built upon the previous enhancements each week. The data structure projects linked above was the starting code. In enhancement one, I merged these projects together by creating another menu in the UI that allows the user to select which data structure they'd like to load the data into. All the cpp and header files are now a part of the same project. In enhancement two, I coded additional vector sorting algorithms to demonstrate competency in the data structures and algorithms course goal. I set up a timing system to compare the speeds of different sorting algorithms. In enhancement three, I outputted all data to a tidy csv file that can be plotted in a few clicks on Excel. The resulting bar graph is uploaded with this project.

Discuss how completing your coursework throughout the program and developing the ePortfolio has helped you showcase your strengths, shape your professional goals and values, and prepare to enter or become more employable in the computer science field.
Use specific examples from your program and include examples outside of the artifacts included in your ePortfolio.
Address the following topics: collaborating in a team environment, communicating with stakeholders, data structures and algorithms, software engineering and database, and security. This section should function as an overall introduction to your skills, not a discussion of the artifacts.
Summarize and introduce how your artifacts fit together and inform the portfolio as a whole.
This summary will help demonstrate the full range of your computer science talents and abilities.
This section should introduce your audience to the technical artifacts that follow the professional self-assessment.

[Code Review](https://drive.google.com/file/d/1iHL3Jb9dDs2tcFdP0pn-wRLrEeSmxqXW/view?usp=sharing)

Original Code, from CS-300, Data Structure & Algorithms: [Vector Sorting](https://drive.google.com/file/d/1FSt-hcQRqSK3kyrp_cjQOgGWW4w7qD49/view?usp=sharing), [Linked List](https://drive.google.com/file/d/1tfSDdhKwkrRjcVvUojB0Ne9h06AbKCUD/view?usp=sharing), [Hash Table](https://drive.google.com/file/d/1AGKFkg5T3YwD6JQZNO1deyPfCw0GFy0r/view?usp=sharing), [Binary Search Tree](https://drive.google.com/file/d/1AXUzupCy6LOb2PKGhsT-nxyRnzkrFBbn/view?usp=sharing)

[Enhancement 1: Software Engineering](https://drive.google.com/file/d/1A_mTsuSpbifjIMZnON8fSLgVbwdudgqj/view?usp=sharing)

- Briefly describe the artifact. What is it? When was it created?

The original artifact is a collection of files from CS 300 - Data Structures and Algorithms. Specifically, four different data structures--vector, linked list, hash table, and binary search tree--were explored to see their efficiency in performing basic operations on a large database of property bids. I took this class in the summer of 2024.

- Justify the inclusion of the artifact in your portfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?

I like this artifact because it demonstrates competency in solving a problem using different strategies. Data structures are ubiquitous in computer programming, so having mastery of them and knowing how they compare to each other is essential. I am improving this artifact by making it easier to compare the data structures. Instead of running different main functions in different files for each data structure, each data structure and its CRUD operations can be accessed from a single menu in the main function, allowing for side-by-side comparisons of the efficiencies of the data structures for each of the four CRUD operations and the vector sorting algorithms. 

- Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

This enhancement taught me the importance of modularizing code. Specifically, I found it helpful to make separate header files for code belonging to different data structures. I ended up with 10+ header files with their corresponding cpp files, including header files for classes, header files for functions for specific classes, and header files for general functions. Although this may have been overkill, I know where each function goes, and when I develop more functions for specific classes in Milestone Three, I know exactly where to put them. I kept running into the issue of multiple files including identical functions. By allowing myself to make many header files and associated cpp files as desired, I could achieve the organization necessary to make function inclusion intuitive. It’s better to over-organize than under-organize, especially when more additions will be made to a project.


[Enhancement 2: Data Structures and Algorithms](https://drive.google.com/file/d/10GAQoelHszot03fw6ey5LUNRLsv9CLE5/view?usp=sharing)

- Briefly describe the artifact. What is it? When was it created?
  
The artifact is a collection of files that use different data structures to hold property auction bids and perform operations on those data structures. Specifically, the data structures are the std::vector, and implementations of a linked list, a hash table, and a binary search tree. These artifacts were developed in CS 300: Data Structures and Algorithms.


- Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in algorithms and data structure? How was the artifact improved?

These files are the perfect artifacts to showcase competency with algorithms and data structures because that’s the class from which they were taken. Specifically, I called upon the CR and D operations for each of the data structures. Create, to populate the data structure with entries, Read, to display the entries, and Delete, to delete an entry. The clock ticks associated with each of these operations are counted and displayed. The artifact was improved by incorporating more sorting algorithms for the vector data structure. Specifically, I added the following algorithms: bubble sort, insertion sort, linear sort, binary sort, and jump sort. I included a variety of sorting algorithms because it’s interesting to compare the runtimes. 


- Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

I learned that vector sorting, using any method, takes much longer than simple CRUD operations, and there is much greater variety in the runtimes of sorting algorithms than between CRUD operations (for any of the four data structures). This has made me re-evaluate my plan for the database enhancement. Instead of recording each runtime for each function, I will only record the vector sorting algorithms. When the random fluctuations are averaged out, the vector sorting algorithms are the only ones with interesting (varied and non-zero) runtimes. One challenge was the decision of which aspect of the bids to sort (title, ID, fund amount, etc.). After deciding to sort the bids alphabetically instead of by bid ID, I needed to edit the algorithms to make the comparison element a string rather than an integer. This edit was straightforward, but it did require an important decision. I took a cue from the previously written sorting algorithms (selection sort and quick sort), which sort bids alphabetically.

[Enhancement 3: Databases](https://drive.google.com/file/d/1nUdGTgM4RWYAxQFtusAVcYXAzn0kczL2/view?usp=sharing)

- Briefly describe the artifact. What is it? When was it created?
  
I’m using the Vector.cpp artifact from CS-300, Data Structure and Algorithms. This file defines algorithms for a vector of property auction bids to be sorted along with the CRUD operations. In the previous enhancement, I added more sorting algorithms in Vector.cpp to compare their efficiency using runtime measurements.

- Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?

I selected this item because I was curious about how all of the algorithms compare to each other. I wanted to log data and see it in a graph, instead of just knowing the big O scaling each algorithm has mathematically. The input file of property auction bids was long enough that sorting was a nontrivial task. Last week I improved this artifact by adding 5 new sorting algorithms (bubble sort, insertion sort, linear sort, and jump sort), demonstrating knowledge in software development. I improved this artifact further by outputting data to a CSV that can be opened and quickly graphed in Excel.

- Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

At first, I was very ambitious--I wanted to log all the data to MongoDB with the two attributes of sorting algorithm type and runtime in clock ticks. However, it was very complicated to set up a connection to MongoDB in Visual Studio (unlike MongoDB’s seamless integration in Visual Studio Code). I explored alternate ways to output data. The simplest and most effective route I found was to upload the data to a .csv file and then import that value in Excel where a graph can be easily made. If I were to do this again, I’d make a copy of my project or develop the project in Visual Studio Code where it’s much easier to integrate a MongoDB database. However, I did get the results that I wanted, and it’s very interesting to see how these algorithms compare! Next time, I’d also use a larger data set to see more pronounced differences from the sorting algorithms that aren’t bubble sort. 

