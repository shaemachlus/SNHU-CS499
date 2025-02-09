# SNHU-CS499
Computer Science Capstone

Professional Self-Assessment:


Code Review:
https://drive.google.com/file/d/1iHL3Jb9dDs2tcFdP0pn-wRLrEeSmxqXW/view?usp=sharing

Original Code, from CS-300, Data Structure & Algorithms:

Vector Sorting: https://drive.google.com/file/d/1FSt-hcQRqSK3kyrp_cjQOgGWW4w7qD49/view?usp=sharing

Linked List: https://drive.google.com/file/d/1tfSDdhKwkrRjcVvUojB0Ne9h06AbKCUD/view?usp=sharing

Hash Table: https://drive.google.com/file/d/1AGKFkg5T3YwD6JQZNO1deyPfCw0GFy0r/view?usp=sharing

Binary Search Tree: https://drive.google.com/file/d/1AXUzupCy6LOb2PKGhsT-nxyRnzkrFBbn/view?usp=sharing

The original artifact is a collection of files from CS 300 - Data Structures and Algorithms. Specifically, four different data structures--vector, linked list, hash table, and binary search tree--were explored to see their efficiency in performing basic operations on a large database of property bids. I took this class in the summer of 2024. I like this artifact because it demonstrates competency in solving a problem using different strategies. Data structures are ubiquitous in computer programming, so having mastery of them and knowing how they compare to each other is essential. I am improving this artifact by making it easier to compare the data structures. Instead of running different main functions in different files for each data structure, each data structure and its CRUD operations can be accessed from a single menu in the main function, allowing for side-by-side comparisons of the efficiencies of the data structures for each of the four CRUD operations and the vector sorting algorithms.

Enhancement 1: Software Engineering
https://drive.google.com/file/d/1A_mTsuSpbifjIMZnON8fSLgVbwdudgqj/view?usp=sharing

- Briefly describe the artifact. What is it? When was it created?

The original artifact is a collection of files from CS 300 - Data Structures and Algorithms. Specifically, four different data structures--vector, linked list, hash table, and binary search tree--were explored to see their efficiency in performing basic operations on a large database of property bids. I took this class in the summer of 2024.

- Justify the inclusion of the artifact in your portfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?

I like this artifact because it demonstrates competency in solving a problem using different strategies. Data structures are ubiquitous in computer programming, so having mastery of them and knowing how they compare to each other is essential. I am improving this artifact by making it easier to compare the data structures. Instead of running different main functions in different files for each data structure, each data structure and its CRUD operations can be accessed from a single menu in the main function, allowing for side-by-side comparisons of the efficiencies of the data structures for each of the four CRUD operations. In Milestone Four, the results will be sent to MongoDB to be recorded in a database.

- Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

This enhancement taught me the importance of modularizing code. Specifically, I found it helpful to make separate header files for code belonging to different data structures. I ended up with 10+ header files with their corresponding cpp files, including header files for classes, header files for functions for specific classes, and header files for general functions. Although this may have been overkill, I know where each function goes, and when I develop more functions for specific classes in Milestone Three, I know exactly where to put them. I kept running into the issue of multiple files including identical functions. By allowing myself to make many header files and associated cpp files as desired, I could achieve the organization necessary to make function inclusion intuitive. It’s better to over-organize than under-organize, especially when more additions will be made to a project.


Enhancement 2: Data Structures and Algorithms
https://drive.google.com/file/d/10GAQoelHszot03fw6ey5LUNRLsv9CLE5/view?usp=sharing

- Briefly describe the artifact. What is it? When was it created?
  
The artifact is a collection of files that use different data structures to hold property auction bids and perform operations on those data structures. Specifically, the data structures are the std::vector, and implementations of a linked list, a hash table, and a binary search tree. These artifacts were developed in CS 300: Data Structures and Algorithms.


- Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in algorithms and data structure? How was the artifact improved?

These files are the perfect artifacts to showcase competency with algorithms and data structures because that’s the class from which they were taken. Specifically, I called upon the CR and D operations for each of the data structures. Create, to populate the data structure with entries, Read, to display the entries, and Delete, to delete an entry. The clock ticks associated with each of these operations are counted and displayed. The artifact was improved by incorporating more sorting algorithms for the vector data structure. Specifically, I added the following algorithms: bubble sort, insertion sort, linear sort, binary sort, and jump sort. I included a variety of sorting algorithms because it’s interesting to compare the runtimes. 


- Reflect on the process of enhancing and modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?

I learned that vector sorting, using any method, takes much longer than simple CRUD operations, and there is much greater variety in the runtimes of sorting algorithms than between CRUD operations (for any of the four data structures). This has made me re-evaluate my plan for the database enhancement. Instead of recording each runtime for each function, I will only record the vector sorting algorithms. When the random fluctuations are averaged out, the vector sorting algorithms are the only ones with interesting (varied and non-zero) runtimes. One challenge was the decision of which aspect of the bids to sort (title, ID, fund amount, etc.). After deciding to sort the bids alphabetically instead of by bid ID, I needed to edit the algorithms to make the comparison element a string rather than an integer. This edit was straightforward, but it did require an important decision. I took a cue from the previously written sorting algorithms (selection sort and quick sort), which sort bids alphabetically.

Enhancement 3: Databases
https://drive.google.com/file/d/1nUdGTgM4RWYAxQFtusAVcYXAzn0kczL2/view?usp=sharing

At first, I was very ambitious--I wanted to log all the data to MongoDB with the two attributes of sorting algorithm type and runtime in clock ticks. However, it was very complicated to set up a connection to MongoDB in Visual Studio (unlike MongoDB’s seamless integration in Visual Studio Code). I explored alternate ways to output data. The simplest and most effective route I found was to upload the data to a .csv file and then import that value in Excel where a graph can be easily made. If I were to do this again, I’d make a copy of my project or develop the project in Visual Studio Code where it’s much easier to integrate a MongoDB database. However, I did get the results that I wanted, and it’s very interesting to see how these algorithms compare! Next time, I’d also use a larger data set to see more pronounced differences from the sorting algorithms.
