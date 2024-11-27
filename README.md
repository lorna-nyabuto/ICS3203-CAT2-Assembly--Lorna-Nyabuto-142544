# **ICS3203-CAT2-Assembly**

This repository contains solutions for the ICS3203 CAT 2 assignment. Each program is implemented in assembly language and demonstrates concepts such as control flow, array manipulation, modular programming, and hardware simulation.

## **Programs Overview**

### **1. Control Flow and Conditional Logic**
- **Purpose**: Classifies a user input number as POSITIVE, NEGATIVE, or ZERO.  
- **Highlights**:  
  - Uses both conditional and unconditional jumps.  
  - Demonstrates branching logic for clear decision-making.  

### **2. Array Manipulation with Looping and Reversal**
- **Purpose**: Reverses an array of integers in place using loops.  
- **Highlights**:  
  - Operates directly on memory to avoid extra storage.  
  - Implements efficient element swapping and boundary checks.  

### **3. Modular Program with Subroutines for Factorial Calculation**
- **Purpose**: Computes the factorial of a number using a recursive subroutine.  
- **Highlights**:  
  - Demonstrates stack usage for preserving registers.  
  - Modular design with a clean separation of tasks.  

### **4. Data Monitoring and Control Using Port-Based Simulation**
- **Purpose**: Simulates a water level control system with actions based on sensor inputs.  
- **Highlights**:  
  - Implements memory-mapped I/O to control motor and alarm status.  
  - Uses conditional logic for threshold-based decision-making.  

---

## **How to Compile and Run**

1. **Prerequisites**:  
   - Ensure `nasm` (Netwide Assembler) is installed.  
   - Use a Linux environment or emulator for system calls.

2. **Compiling**:  
   Run the following command for each program:  
   ```bash
   nasm -f elf32 program_name.asm -o program_name.o
   ld -m elf_i386 -s -o program_name program_name.o
