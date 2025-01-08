## Author
Samridhi Gupta

## Date
08/01/2025

## Topic
Finding Maximum and Minimum Value in an Array

## Description
The MaxMin program is a simple Java application that prompts the user to enter a number of elements and then the elements themselves. It calculates and displays the maximum and minimum values from the provided array of integers.

## Features
- Accepts user input for the number of elements in the array.
- Allows the user to input the elements of the array.
- Computes the maximum and minimum values from the array.
- Displays the results clearly.

## How to Run the Program

### Prerequisites
- Java Development Kit (JDK) installed on your machine.

### Steps
1. **Clone the Repository** (if applicable):
   ```bash
   git clone https://github.com/Samridhi060/MinMax.git
   cd MaxMin
   ```

2. **Compile the Program**:
   Open a terminal and navigate to the directory containing the `MaxMin.java` file. Then run:
   ```bash
   javac MaxMin.java
   ```

3. **Run the Program**:
   Execute the compiled Java program using:
   ```bash
   java MaxMin
   ```

4. **Input**:
   - When prompted, enter the number of elements in the array.
   - Then, input each element of the array one by one.

5. **Output**:
   The program will display the maximum and minimum numbers from the array.

## Example

### Input:
```
Enter the number of elements in the array: 
5
Enter the elements of the array: 
12
5
8
20
3
```

### Output:
```
Maximum number is: 20
Minimum number is: 3
```

## Code Explanation

- The program begins by importing the `Scanner` class for user input.
- It defines the `MaxMin` class, which contains the `main` method and the `maxmin` method.
- The `main` method handles user input and calls the `maxmin` method.
- The `maxmin` method iterates through the array to find the maximum and minimum values and prints them.

## Conclusion
This program is a straightforward implementation to find the maximum and minimum values in an array of integers, demonstrating basic Java programming concepts such as arrays, loops, and user input.
