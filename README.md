# SimpleCalculator
A Simple Calculator on Arduino UNO

**Components Used**
  Arduino UNO
  Bread Board
  Jumper Wires(Male to Male(18))
  LCD Display(16*2)
  Keypad (4*4)

Circuit Diagram :


![Circuit Diagram (Tinker CAD)](https://github.com/anuragak021/SimpleCalculator/blob/main/Screenshot%20from%202024-07-23%2019-53-12.png)
![Circuit Diagram with connections](https://github.com/user-attachments/assets/50e5afe9-dfcc-45e7-8aa4-fe52e1134560)

**DESIGN**
The 4x4 matrix keypad consists of 16 keys arranged in rows and columns. Each key press generates a unique combination of row and column signals, which can be decoded to determine the pressed key.
The Arduino reads these signals from the keypad and interprets them as numeric values or operators (+, -, *, /).
Based on the user input, the Arduino performs the corresponding arithmetic operation and displays the result on an LCD display, if available, or via serial communication to a computer.

**Implementation Steps:**
Hardware Setup:  
All the rows and columns of the keypad were connected to the digital pins of the Arduino using jumper wires
One can connect an LCD Display to the Arduino to show the input and output.

**Software Implementation:**
Arduino code in c++ was written to initialize the keypad and LCD Display.Functions were implemented to read keypad input and perform arithmetic operations.
The LCD Screen was used as a display output or input 

**User Interaction:**
Users can input numeric values and select arithmetic operations using the keypad.
The Arduino performs the requested operation and displays the result.

**RESULT**
A Simple Calculator was Made using an Arduino , BreadBoard , Keypad and LCD Display
![Result From the top](https://github.com/user-attachments/assets/fdda17b2-4f75-4eb4-8443-568b009cc0b8)
![Output](https://github.com/user-attachments/assets/2400e7f5-0265-4e9b-a9a3-e30485655d07)

**CONCLUSION**
In conclusion, the development of a simple calculator using Arduino and a keypad underscores the versatility and accessibility of microcontroller-based systems in practical applications. Through this project, we have explored the fundamental principles of input interfacing, data processing, and output display, essential components of embedded systems design. By leveraging Arduino's capabilities and programming flexibility, we have successfully created a user-friendly calculator capable of performing basic arithmetic operations. This project not only serves as an educational endeavor, providing hands-on experience in electronics and programming, but also demonstrates the potential for Arduino to serve as a platform for innovation and creativity in solving everyday challenges. As we reflect on this project, we are inspired to continue exploring the vast possibilities of microcontroller technology in shaping the future of computing and automation.
