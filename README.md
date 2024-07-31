# Jack Standard Library

## Overview

The **Jack Standard Library** project is a comprehensive effort to extend the Jack programming language by introducing a well-rounded collection of data structures and utility functions. While Jack is a low-level, object-oriented language, it lacks the rich standard libraries available in more mature languages such as Java or Python. This library fills that gap, offering developers the tools they need to write more effective and efficient code within the Jack environment.

## Key Features

### Data Structures

The library includes a variety of essential data structures:

1. **List**: A dynamic array that can grow or shrink in size as needed, providing flexibility in memory management.
   
2. **Vector**: Similar to a List but optimized for index-based access, allowing for quick retrieval of elements.
   
3. **Queue**: A first-in-first-out (FIFO) data structure, ideal for scenarios where the order of elements is important.
   
4. **Priority Queue (pQueue)**: An advanced version of the Queue, where each element is associated with a priority. Elements with higher priority are dequeued before those with lower priority.
   
5. **Matrix**: A two-dimensional array supporting a variety of matrix operations, essential for mathematical computations.
   
6. **Binary Search Tree (BST)**: A tree structure that maintains its elements in a sorted order, facilitating quick search, insertion, and deletion operations.
   
7. **Hash Table**: A data structure that maps keys to values, providing efficient lookups, insertions, and deletions.
   
8. **Set**: A collection of unique elements, preventing duplicates and allowing for set operations such as union and intersection.

### Utility Functions

This library also provides a set of utility functions to perform common operations, including:

#### Sorting Algorithms

1. **Bubble Sort**: A straightforward sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are out of order.
   
2. **Insertion Sort**: An algorithm that builds a sorted array one element at a time, making it efficient for small data sets.
   
3. **Selection Sort**: A sorting algorithm that repeatedly selects the smallest or largest remaining element and moves it to its correct position in the array.
   
4. **Quick Sort**: A highly efficient sorting algorithm that employs a divide-and-conquer strategy to sort elements.

#### String Manipulation

1. **String Comparison**: Compares two strings lexicographically to determine their order.
   
2. **toUppercase**: Converts all characters in a string to uppercase, standardizing text formatting.
   
3. **toLowercase**: Converts all characters in a string to lowercase, useful for case-insensitive comparisons.
   
4. **String Reversal**: Reverses the order of characters in a string, useful for certain algorithmic challenges.

#### Mathematical Operations

1. **Greatest Common Divisor (GCD)**: Computes the largest number that divides two integers without leaving a remainder, useful in fraction simplification and number theory.
   
2. **Exponentiation**: Raises a base number to the power of an exponent, a fundamental operation in many mathematical formulas.
   
3. **Hypotenuse Calculation**: Determines the hypotenuse of a right-angled triangle using the Pythagorean theorem, essential in geometry.
   
4. **Cube Root Calculation**: Computes the cube root of a number, important in volume calculations and solving cubic equations.

## Getting Started

### Prerequisites

To use the Jack Standard Library, you need the following:

- **Jack Compiler and VM Emulator**: These tools are usually part of the NAND2Tetris software suite. Ensure they are installed on your system.
- **Basic Knowledge of the Jack Programming Language**: Familiarity with Jack syntax and concepts is essential to effectively use the library.

### Installation

To install the Jack Standard Library, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-repository/jack-standard-library.git
    ```

2. **Navigate to the Project Directory**:
    ```sh
    cd jack-standard-library
    ```

3. **Compile the Jack Files**:
   Use the Jack compiler to compile the source files within the repository. This will generate the corresponding VM files.

## Execution

### Writing and Compiling Jack Code

1. **Create Your Jack Code**: Write your Jack programs and save them with a `.jack` extension (e.g., `Main.jack`).

2. **Compile the Code**:
   - **Using the Jack Compiler GUI**:
     - Open the Jack compiler provided by NAND2Tetris.
     - Select the directory containing your `.jack` files.
     - The compiler will process all the files and generate `.vm` files in the same directory.
   - **Using the Command Line**:
     - Navigate to the directory containing your Jack files.
     - Run the following command:
       ```sh
       JackCompiler Main.jack
       ```
     - This command will generate a `Main.vm` file.

### Running the VM Code

1. **Open the VM Emulator**: Launch the VM emulator that comes with the NAND2Tetris suite.

2. **Load the VM Code**:
   - In the VM emulator, use the "Load Program" option to load your `.vm` files.
   - Navigate to the directory containing the `.vm` files and select them (e.g., `Main.vm`).

3. **Configure the VM Emulator**:
   - Ensure that the emulator's settings (like memory and CPU configuration) are properly adjusted according to your program's requirements.

4. **Run the Code**:
   - You can use the "Step" button to execute the code line by line, which is useful for debugging.
   - Alternatively, use the "Run" button to execute the entire program without interruption.

### Example Execution Workflow

- **Example**: If you have implemented a bubble sort algorithm, compile the `BubbleSort.jack` file and load the resulting `BubbleSort.vm` file into the VM emulator. Then, use the emulator's controls to run and observe the sorting process.

### Debugging and Testing

- The VM emulator offers various tools to help you debug your program, such as viewing the stack, memory, and registers.
- Carefully observe the program's output and behavior to ensure it meets your expectations.
- If issues are found, modify your Jack code, recompile it, and rerun the tests until the program behaves as desired.
