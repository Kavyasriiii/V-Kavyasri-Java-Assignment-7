# V-Kavyasri-Java-Assignment-7
This is a simple calculator program implemented in Java. It provides a menu-driven interface to perform basic arithmetic operations: addition, subtraction, multiplication, and division.

## Features

- Menu-driven interface for ease of use
- Separate Java files for each operation (addition, subtraction, multiplication, division)
- Exception handling for invalid inputs (InputMismatchException)
- Division by zero error handling

## How to Run

1. Compile all the Java files using a Java compiler.
2. Run the `Main` class.
3. Follow the menu prompts to perform the desired operation.

## File Structure

- `Main.java`: Contains the main method and the menu-driven interface.
- `Addition.java`: Implements the addition operation.
- `Subtraction.java`: Implements the subtraction operation.
- `Multiplication.java`: Implements the multiplication operation.
- `Division.java`: Implements the division operation.

## Functions/Methods

### Main.java
- `main(String[] args)`: The entry point of the program, responsible for displaying the menu and delegating operations based on user choice.

### Addition.java
- `add()`: Performs the addition operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs.

### Subtraction.java
- `subtract()`: Performs the subtraction operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs.

### Multiplication.java
- `multiply()`: Performs the multiplication operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs.

### Division.java
- `divide()`: Performs the division operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs and division by zero error.

