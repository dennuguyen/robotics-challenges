# Arduino Programming

## Questions

1. Flash a "Hello World!" program to your Arduino board.

    <details><summary>Answer</summary>
    
    Connect the Arduino to your main computer via USB.

    Your sketch may look like:
    ```arduino
    void setup() {
        Serial.println("Hello World!");
    }

    void loop() {}
    ```

    Flash your sketch to the Arduino using the Arduino IDE.

    </details>

1. What happens if the Arduino is not on the specified serial port when flashing? Reproduce this error message.

1. What could be causing this issue in the serial monitor? How could this be fixed?

    ![]()

    <details><summary>Answer</summary>
    
    We are reading from the Arduino on the wrong baud rate. We need the baud rate in the serial monitor to match the serial port baud rate initialisation on the Arduino. To fix this, we can either:
    - Set correct baud rate in `Serial.begin(baud_rate)` or
    - Change to correct baud rate in the serial monitor.

    </details>

1. Write pseudo-C code with an `if` statement to reflect a real-life example for passengers boarding a plane.

1. Write pseudo-C code with a `while` statement to reflect a real-life example of a waiter taking orders.

1. Write the classic "Fizzbuzz" program on the Arduino. Incrementing from 1 up to 32, replace:
    - Any number divisible by three with "fizz"
    - Any number divisible by five with "buzz"
    - Any number divisible by both three and five with "fizzbuzz"
    - Otherwise, print the number itself

1. What procedures could you use to debug programs that don't give desired output?

1. This program is meant to print the number "64". Debug this following program to identify the single line causing the bug.

1. Refactor this program using functions so that it minimises repetition.

1. Refactor the above program so that its function is defined in a separate header file. You should have two files in total: `file1.ino`, `file2.h`.

1. Refactor the above program so that its function is declared in a separate header file and defined in a separate source file. You should have three files in total: `file1.ino`, `file2.h`, `file3.c`.

1. Write an Arduino program which reads an integer and prints its double.

1. Define the following terms:
    - Class
    - Object
    - Instance
    - Method
    - Member
    - Public
    - Private

1. Given this class, how could multiple objects be created from it?

1. Complete this class interface.

1. Design a class which models a skid-steer robot.