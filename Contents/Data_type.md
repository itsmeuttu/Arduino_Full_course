
## Data Types in Arduino:

Data types define the type of value a variable can hold. In Arduino programming (based on C/C++), several built-in data types are commonly used for various purposes.

### Common Data Types:

1. **`int` (Integer):**
   - Stores whole numbers, both positive and negative.
   - **Size**: 2 bytes (16 bits).
   - **Range**: -32,768 to 32,767.
   - **Example**:
     ```cpp
     int temperature = 25;
     ```

2. **`float` (Floating Point):**
   - Stores decimal numbers, used for precision calculations.
   - **Size**: 4 bytes (32 bits).
   - **Range**: ±3.4028235E+38 (large range, up to 6-7 digits of precision).
   - **Example**:
     ```cpp
     float voltage = 5.12;
     ```

3. **`char` (Character):**
   - Stores a single character or a small integer value (ASCII).
   - **Size**: 1 byte (8 bits).
   - **Range**: -128 to 127 (or use for characters like 'A', 'b', etc.).
   - **Example**:
     ```cpp
     char letter = 'A';
     ```

4. **`boolean` (Boolean):**
   - Stores logical values, either `true` or `false`.
   - **Size**: 1 byte (8 bits).
   - **Example**:
     ```cpp
     boolean isOn = true;
     ```

    - 1 , HIGH and true are considered same by IDE
    - 0, LOW , and flase are donsidered same by IDE
    - Alson note that anything others than 0 is also considered true by IDE

5. **`Byte`**

    ```
    byte x = 158;
    byte y = 
    ```

- Range : 0 to 255

- it is used to save memory.