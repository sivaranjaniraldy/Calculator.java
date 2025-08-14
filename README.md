# Java Swing Calculator

This is a simple calculator application built using Java Swing. It provides basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

  * **GUI Interface**: A graphical user interface created with Java Swing.
  * **Basic Arithmetic**: Supports addition (+), subtraction (-), multiplication (\*), and division (/).
  * **Clear Functionality**: The 'C' button clears the current input and resets the calculator.
  * **Error Handling**: Displays "Error" if a division by zero is attempted.

## How to Run

1.  **Compile the Java file**: Open a terminal or command prompt and navigate to the directory where `Calculator.java` is saved. Compile the code using the Java compiler:
    ```sh
    javac Calculator.java
    ```
2.  **Run the application**: After successful compilation, run the application with the following command:
    ```sh
    java Calculator
    ```

## Code Overview

The `Calculator.java` file contains a single class `Calculator` that extends `JFrame` and implements the `ActionListener` interface.

  * `Calculator()`: The constructor sets up the main window, display field, and buttons.
  * `actionPerformed(ActionEvent e)`: This method handles all button clicks. It processes numbers, operators, the clear button ('C'), and the equals button ('=').
  * `main(String[] args)`: The entry point of the application, which creates and displays the `Calculator` frame.
