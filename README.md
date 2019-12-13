# Welcome to TaJah Reynolds' page

This page has been created to showcase the projects I have completed in Data Structures and Abstractions throughout this semester, as well as the key points learned as a result of these projects.

## Project 1: Java Review (Array, Interface, Class, JUnit Test, Driver)

Our first project was designed to introduce us to data structures. This project required students to implement a simple container by writing a java class called ArrayUtility, which implements an interface called UtilityInterface. The array-based implementation of the container (ArrayUtility) has the ability to store multiple Integer objects in an array, and define the methods from the UtilityInterface to manipulate the array. The methods that needed to be implemented were documented in the provided UtilityInterface.html file.

```//TODO: Link to Proj 1 [Link](url)```

### Project 1 Learning Outcomes

- Use an array to implement a simple container.
- Write and understand javadoc documentation.
- Follow a set of specifications for class implementation, including constructors and methods.
- Write a driver class to test a class and its methods.
- Use JUnit library to test code.
- Test code for edge cases, corner cases, and typical cases.
- Format and comment source code that adheres to a given set of formatting guidelines.

### Personal Takeaways from Project 1

Project 1 serves as a refresher for students to re-familiarize themselves with standard coding practices, but it was my first introduction to JUnit and unit testing. JUnit is incredibly useful for making sure my code worked as expected, and testing for all cases became manageable immediately.

***
## Project 2: Set, Resizable Array-based Implementation

Project 2 required students to create a ResizableArraySet class that implements all methods in the SetInterface interface provided. The implementation of the set uses a resizable array of Book objects, which was written following a UML class diagram.

```//TODO: Link to Proj 2```

### Project 2 Learning Outcomes

- Implement a resizable array-based Set ADT.
- Test a class using the JUnit library.

### Personal Takeaways from Project 2

This project tested my ability to implement a class using UML diagrams and interface, which are commonly used in writing Java classes. The use of the UML diagram and interface made this project straightforward to complete, and set a strong foundation for continued use throughout the rest of this class.

***
## Project 3: Set ADT, Sorted Set, Circular Doubly Linked List

Project 3's assignment was to implement the SortedSet class using doubly linked nodes. The SortedSet class was written by implementing the methods in SetInterface, which was provided by the instructor. The SortedSet differs from Set as it is kept sorted at all times, including while adding and removing elements from the SortedSet.

```//TODO: Link to Proj 3```

### Project 3 Learning Outcomes

- Implement a linked-node based Set ADT in which all elements of the set are kept sorted.
- Implement a circular doubly linked list.

### Personal Takeaways from Project 3

This project showed me how interfaces can be used for different implementations, such as the Set implementation from Project 2 and the SortedSet implementation from this project. Additionally, I was introduced to linked implementations of ADT's, which were used consistently moving forward through the class.

***
## Project 4: Stack, Array-based Implementation, Algebraic Expressions: Infix, Postfix, Evaluation

The goal of Project 4 was to write a program that allows the user to type an infix expression and check the expression for validity. If the expression is valid, the program gives the user the equivalent postfix expression and evaluates the expression.

```//TODO: Link to Proj 4```

### Project 4 Learning Outcomes

- Implement a Stack using an array (resizable).
- Implement an algorithm to convert infix expressions into postfix expressions.
- Implement an algorithm to evaluate infix expressions.
- Implement an algorithm to evaluate postfix expressions.

### Personal Takeaways from Project 4

This project challenged me to fully understand infix and postfix expressions, and be able to write algorithms that could convert infix expressions to postfix and evaluate them. This project also showed me how different data structures are more efficient at solving problems than other data structures.

***
## Project 5: No Duplicates Queue and Priority Queue

Project 5 was split into two parts. In the first part, students were instructed to consider a queue that only allows a single copy of an object into the queue at any time. Then, students were to create an interface NoDuplicatesQueueInterface that extends QueueInterface, provided by the instructor. The NoDuplicatesQueueInterface was then used to write the NoDuplicatesQueueArray class. The second part of Project 5 was to create a priority queue that does not allow duplicates. This was accomplished by writing an interface NoDuplicatesPriorityQueueInterface that extends PriorityQueueInterface, provided by the instructor. Finally, students wrote a sorted linked implementation of NoDuplicatesPriorityQueueLinkedNodes using the NoDuplicatesPriorityQueueInterface.

```//TODO: Link to Proj 5```

### Project 5 Learning Outcomes

- Implement an array-based queue.
- Implement a linked nodes-based priority queue.

### Personal Takeaways from Project 5

This project challenged me to write my own interfaces in order to create a class. It also taught me how interfaces interact with other interfaces in a compounding nature. This is a skill that I am thankful for learning, as writing an interface allows for easy implementation of a class. 

***
## Project 6: Hashing, Dictionary and Game Moves

Project 6 asked students to consider all possible boards in a game of Tic Tac Toe. For each board position there is a "best move". Then, write a program that plays a game of Tic Tac Toe in which a dictionary calculates and stores all possible board positions, as well as the best move associated with that position.

```//TODO: Link to Proj 6```

### Project 6 Learning Outcomes

- Define a class to represent a game board.
- Generate game board configuration using recursion.
- Determine the best move for a given game board configuration.
- Store game moves in a dictionary.
- Define and use a class to work with a data structure (Dictionary, Hashing).

### Personal Takeaways from Project 6

Project 6 was a lot of fun to work on. I used a recursive method that generated all valid boards that was outlined by the instructor, which was a majority of the work load for this project. Once the boards were generated, I needed to determine the best move for each board. I used the following steps to determine the best move:

1. Look at all empty spaces to see if there is a winning move. If there is, make the move to win.
2. See if the other player will win on the next move. If they will, make the move to block the win.
3. If none of the above are true, make a move, and then another if there is an empty space. If that board generates a winning move, then it is the best move.

Once the boards and best moves were generated, it was simply a matter of creating a user interface to allow interaction with the game. Overall, this project pushed me to come up with creative solutions in order to complete the project.

***
## Project 7: Speedy Lookup

The final project in this course gave students complete freedom to implement a data structure to store and access data in a timely manner. The only restriction for the project is that students must write their own data structures, and not use Java's data structure library. The class was tested by reading in a string of terms from a text file, which were fed into a StudentLookup object. The StudentLookup object contains the name of a student as a String, and the frequency of the student as an int.

```//TODO: Link to Proj 7```

### Project 7 Learning Outcomes

- Implement a data structure to solve a problem efficiently.

### Personal Takeaways from Project 7

Project 7 was challenging for me to implement a data structure without direction. Initially I wanted to use a Dictionary to store the student name as the key with the frequency as the associated value, but that didn't allow me to easily rank the most popular names. I settled with a LinkedSortedList, which allowed me to store the StudentLookup objects in order from highest to lowest frequency. This method turned out to be pretty efficient, and I recieved bonus points for being within the top 8 fastest implementations.
