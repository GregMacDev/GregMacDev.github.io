## Data Structures and Algorithms
 For my second enhancement, which covers Algorithms and Data Structure, I am building off my previous enhancement done to Lab 1-3 from my Data Structures and Algorithms course which was originally created in May of 2020 and converted from C++ to Java in May of 2021. The enhancements I have performed are implementing an ArrayList structure, to store the data objects, and a sorting algorithm, specifically quicksort, to sort the data within the ArrayList. Originally, this program was used to demonstrate the functionality of a struct data type in C++. After the previous enhancement to convert the original C++ program to Java, the program continued to function in an identical fashion, but utilized a Java class to store the data rather than the struct data type.
  
I chose to continue working with my Lab 1-3 artifact as I felt the conversion from C++ to Java created a great base to continue expanding upon the functionality and complexity of the program, allowing me to demonstrate my understanding of more complex concepts and algorithms. By implementing an ArrayList, I am demonstrating my understanding of using containers to store multiple elements of a data type in java. Specifically, I will be storing class objects with the ArrayList and accessing the different elements of each of the objects being stored. The implementation of the quicksort algorithm will demonstrate my ability to recursively traverse and sort a list of objects in an efficient way. The quicksort algorithm was chosen due to its complexity, O(n log n), which will scale well with larger data sets, and are expected for this program. Aside from implementing an ArrayList and quicksort algorithms, security continues to be emphasized through user input validation of menu options and entering new class object data.
  
The outline for this enhancement, presented in the proposal from module one, introduced the ArrayList and Quicksort implementations and I feel as though I met, and in some areas exceeded the expectations of the proposal. Initially, I had set out to only allow the user to sort on two of the four elements of each class object, but when implementing these changes, I included the functionality to sort on each of the four elements of each class object. While creating and testing the enhancements proposed, I have considered expanding up this project even further and implementing a full array of CRUD functionality in the future. I am hoping to implement update and delete functionality, alongside the add functionality that already exists, as well as a search function to round out the program’s user experience.
  
The implementation of these enhancements caused several drawbacks in areas I was not expecting while also proving to be less disruptive in areas that I had anticipated. Creating, populating, and accessing the ArrayList and its elements did not provide any unforeseen challenges. Creating a method to properly display all the elements of the ArrayList was an initial oversight that I had not planned for. Developing the proper formatting and visuals for this method was the lengthiest part of it. Implementation of the quicksort algorithm proved to be more difficult than anticipated in other unexpected ways. Going in, and one of the reasons to implement the quicksort algorithm, recursion was an element I wanted to utilize with the expectation of struggling to implement it. However, the recursive element of quicksort was implemented quickly and correctly. Understanding that after partitioning the list, it was necessary to traverse the list numerous times, the recursive calls were an easy implementation. However, the iterations through each part of the ArrayList and making the comparisons proved to be the most difficult part of this algorithm. Finding the proper syntax for comparison on each element became problematic. Once I worked out the proper comparisons, the remainder of the quicksort algorithm came together successfully.

### Repository
[Enhancement Two](https://github.com/GregMacDev/CS-499-AlgorithmsAndDataStructures/tree/main/CapstoneEnhancementTwo)

## ePortfolio Links
- [Main Page](https://GregMacDev.github.io/index.html)
- Code Review
- Enhancement One
- Enhancement Three