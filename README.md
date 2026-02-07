# CS 271 - Computer Architecture & Assembly Language

Assembly language programming projects using x86 architecture and MASM (Microsoft Macro Assembler). Projects demonstrate low-level programming concepts including registers, memory addressing, arithmetic operations, control flow, and procedures.

## Course Projects

### Project 1: Basic Arithmetic Calculator
**File:** `Practice/Project1Practice.asm`  
**Description:** Prompts user to enter two integers (X and Y) where X > Y, then computes and displays their sum, difference, and product using Irvine library calls.

**Features:**
- Verifies descending order (X > Y) and allows repeat until valid input (Extra Credit)
- Handles negative results (Extra Credit)
- Computes both X - Y and Y - X (Extra Credit)
- Calculates and displays quotient X/Y with remainder (Extra Credit)

**Concepts:** Arithmetic operations, input validation, loops, conditional logic, division with remainder

### Project 2: Debug Lab
**File:** `Project2-DebugLab/DebugLab.asm`  
**Description:** Debugging exercise to identify and fix errors in assembly code.  
**Skills:** Debugging, code analysis, assembly syntax correction

### Project 3: Temperature Analyzer
**File:** `Project3-TemperatureAnalyzer/Proj3_CampMeli.asm`  
**Description:** Interactive program that collects temperature readings from users, validates input, categorizes temperatures (Cold, Cool, Warm, Hot), and calculates statistics including maximum, minimum, and average temperatures.

**Features:**
- User-defined number of temperature readings (Extra Credit)
- Input validation
- Temperature categorization system
- Statistical calculations (max, min, average)
- Average rounded to two decimal places without floating-point operations (Extra Credit)

**Concepts:** Input validation, conditional logic, arithmetic operations, integer division, modulo operations, loops

---

## Practice Programs

### Comparator
**File:** `Practice/Comparator.asm`  
**Description:** Prompts user for two unsigned integers and determines which is greater or if they are equal.  
**Concepts:** User input, comparison operations, conditional branching

### Dog Years Calculator
**Files:** 
- `Practice/DogYears.asm` - Working version
- `Practice/DogYearsWithBugs.asm` - Intentionally buggy version for debugging practice

**Description:** Converts human years to dog years.  
**Concepts:** Arithmetic operations, input/output, debugging techniques

### Guessing Game (Two Versions)
**Files:**
- `Practice/GuessingGameOneShot.asm` - Single attempt version
- `Practice/GuessingGameMultiShot.asm` - Multiple attempts version

**Description:** Number guessing game where user tries to guess a predetermined number.  
**Concepts:** Conditionals, loops, user interaction

---

## Technical Details

**Assembly Language:** x86 (32-bit)  
**Assembler:** MASM (Microsoft Macro Assembler)  
**IDE:** Visual Studio 2012  
**Instruction Set:** x86 assembly (IA-32)  
**Library:** Irvine32 (for input/output procedures)

### Key Concepts Demonstrated:
- Register manipulation (EAX, EBX, ECX, EDX)
- Memory addressing modes
- Stack operations (PUSH, POP)
- Arithmetic and logic operations
- Control flow (conditional jumps, loops)
- Procedure calls and the Irvine32 library
- Input/output operations (ReadInt, WriteString, WriteDec)
- Integer division and modulo operations (DIV instruction)
- Input validation techniques
- Signed vs unsigned arithmetic
- Handling negative numbers

---

## How to Run

### Using Visual Studio:
1. Open the `.asm` file in Visual Studio
2. Ensure MASM and Irvine32 library are configured properly
3. Build and run the project (Ctrl+F5)

### Using Command Line:
```bash
ml /c /coff filename.asm
link /subsystem:console filename.obj irvine32.lib kernel32.lib
filename.exe
```

**Note:** Requires MASM32 SDK and Irvine32 library properly installed.

---

## Course Information

**Course:** CS 271 - Computer Architecture and Assembly Language  
**Institution:** Oregon State University  
**Language:** x86 Assembly (MASM)  
**Term:** Fall 2024

### Learning Objectives:
- Understand low-level computer architecture
- Master x86 assembly language syntax and instructions
- Implement algorithms using only registers and memory
- Debug assembly code effectively
- Work with the stack and procedure calls
- Perform arithmetic without floating-point operations
- Use the Irvine32 library for I/O operations

---

*These programs were created as coursework to demonstrate understanding of assembly language programming and computer architecture fundamentals.*
```
