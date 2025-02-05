# Doxygen Example - C++ Documentation  

## Overview  
This project illustrates the use of **Doxygen-style comments** to document a C++ program file and its functions. The program provides example functions and descriptions to demonstrate how to format comments for generating HTML documentation using Doxygen.

## Features  
- **Doxygen documentation** for file, functions, and parameters  
- **Example functions**:  
  - `DoSomething()`: Modifies a character and creates a string  
  - `numberOfDigits()`: Calculates the number of digits in an integer  
- **Console output** demonstrating the functions  

## Installation & Compilation  
1. Install a C++ compiler (e.g., `g++` for GCC).  
2. Save the file as `doxygen_example.cpp`.  
3. Compile using:  
   ```sh
   g++ doxygen_example.cpp -o doxygen_example
   ```
4. Run the program:  
   ```sh
   ./doxygen_example
   ```

## Using Doxygen  
1. Install **Doxygen** (if not installed):  
   ```sh
   sudo apt install doxygen    # Ubuntu/Linux  
   brew install doxygen        # macOS  
   ```
2. Generate documentation:  
   ```sh
   doxygen -g                  # Generates a config file (optional)  
   doxygen                     # Runs Doxygen to generate documentation  
   ```
3. Open the generated `index.html` file in the `html` directory to view the documentation.

## Example Output  
```
6 V PPPPPP

Number of digits in 0 ...... 1
Number of digits in 7 ...... 1
Number of digits in 123 .... 3
Number of digits in 12345 .. 5

Press Enter to continue ...
```

## Notes  
- The **Doxygen comments** (indicated by `/** ... */`) will appear in the generated HTML documentation.  
- The program is designed **only for demonstration purposes** and does not implement advanced error handling.  

## Author  
Lastname Firstname (A00123456)  
CSCxxxxx - Example Course  

## License  
This project is open-source and free to use for educational purposes.
