# **Project Overview**
***
The project includes several C files and headers, each of which serves a specific purpose in the 
program. It adheres to principles of clarity, readability, neat writing, and data abstraction.

Assembler Stages

The assembler works in four main stages:

## **1. Pre-Processing**
***
The pre-assembler reads the source file line by line and identifies micro definitions. When a
micro is identified, it adds its lines to the micro table and replaces them in the source file.

## **2. Front - Error Checking**
***
After the preprocessing stage, the assembler checks the code for errors and informs the user if
any are found. This stage verifies that the source code conforms to the expected syntax and
semantics.

## **3. First Pass**
***
The first pass identifies symbols (labels) and assigns them numerical values ​​that represent their
corresponding memory address. It also begins to generate the label-independent binary code.

##**4. Second Pass**
***
In the second pass, the assembler generates the final computer code by replacing the names of
the operations with their binary equivalents and the names of the symbols with their assigned
memory locations.
