## Arduino Prgramming 


**Arduino programming** involves writing code using the Arduino Integrated Development Environment (IDE) to control and interact with hardware components. The language used is based on **C/C++** with additional Arduino-specific functions and libraries to simplify hardware interaction.

Its file extension is `.ino`

### Key Concepts:
- **Sketch**: An Arduino program is called a sketch. It typically consists of two main functions:
  - `setup()`: Runs once when the board is powered on or reset, used to initialize settings such as pin modes (input/output).
  - `loop()`: Repeats continuously after `setup()` and contains the logic that controls the board's actions.

### Example Structure:
```cpp
void setup() {
  pinMode(LED_BUILTIN, OUTPUT); // Set built-in LED pin as output
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // Turn the LED on
  delay(1000);                      // Wait for 1 second
  digitalWrite(LED_BUILTIN, LOW);   // Turn the LED off
  delay(1000);                      // Wait for 1 second
}
```

### Features:
- **Pin Control**: Easily interact with digital and analog pins using functions like `digitalWrite()`, `analogRead()`, and `analogWrite()`.
- **Libraries**: Pre-built libraries for controlling sensors, motors, displays, and communication protocols like I2C, SPI, and UART.
- **Serial Communication**: Use `Serial.begin()` to communicate with the computer, useful for debugging and sending/receiving data.

It is case sensitive.