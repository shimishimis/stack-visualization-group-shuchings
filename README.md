Stack Visualizer
Stack Visualizer: A Java-Based Stack Implementation

Shuchings
Members: Palanog, Del Mundo, Castillo, Sales, Dominguez

Description of the Program
The Stack Visualizer is a Java program that demonstrates how a stack works using a graphical user interface (GUI). It allows users to add, remove, and view elements in a stack. The program follows the Last In, First Out (LIFO) principle, which means the last element added is the first one removed.

Features
- Push: Adds a number to the top of the stack.
- Pop: Removes the top element from the stack.
- Peek:Displays the top element without removing it.
- Clear: Removes all elements from the stack.
- Check Stack: Displays the current stack status, size, and remaining spaces.
- Random: Generates a random number from 1 to 100 and adds it to the stack.
- Visual Display: Shows stack elements in a graphical interface and highlights the top element.
- Input Validation: Prevents invalid number inputs and handles full or empty stack conditions.

Requirements
- Java Development Kit (JDK)
- Java-compatible IDE, such as NetBeans, IntelliJ IDEA, or Eclipse, or a terminal
- Java Swing library, which is included in the standard Java desktop environment

How to Run the Program

Using an IDE
1. Create a Java project.
2. Add `ArrayStack.java` and `StackVisualizer.java` to the source folder.
3. Make sure both files belong to the same package, or leave them in the default package.
4. Open `StackVisualizer.java`.
5. Run the file using its `main()` method.

Using the Terminal
1. Open the terminal in the folder containing both Java files.
2. Compile the program:
3. Run the program:
4. The Stack Visualizer GUI should open.

Project Structure

```text
StackProject/
├── ArrayStack.java
├── StackVisualizer.java
├── README.md
└── screenshots/
    ├── main-interface.png
    ├── push-operation.png
    └── random-operation.png
```

Stack Implementation
The program implements a stack using an array. It uses a variable named `top` to track the index of the top element. Initially, `top` is set to `-1`, which means the stack is empty.

The stack follows the **Last In, First Out (LIFO)** principle. When an element is pushed, the top index increases. When an element is popped, the top index decreases.

The program supports the following stack operations:

- push(): Adds an element to the stack.
- pop(): Removes and returns the top element.
- peek(): Returns the top element without removing it.
- isEmpty(): Checks whether the stack has no elements.
- isFull(): Checks whether the stack has reached its capacity.
- size(): Returns the number of elements in the stack.
- clear(): Removes all elements from the stack.

The stack has a maximum capacity of 10 elements. The program checks for overflow and underflow conditions to prevent adding elements to a full stack or removing elements from an empty stack.

Screenshots

The Screenshots are in the word file

AI Disclosure
Name of AI Tool and Version: ChatGPT by OpenAI, powered by GPT-6.
Task Performed by the AI Tool: ChatGPT was used to assist in drafting the Java code for the Stack Visualizer, creating the graphical user interface (GUI), explaining stack operations, and troubleshooting missing features.
Prompts Used: 
- make a simple code that has a GUI for a project named Stack Visualization, add functional buttons like push, pop, peek, clear, check stack, and random
- random button is missing
- explain the flow of this project
  
 Contributors
 Del Mundo
 Dominguez
 Sales
 Castillo
