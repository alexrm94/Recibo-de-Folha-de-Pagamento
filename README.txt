Using COBOL Compiler and Executable for File Modification
Introduction
This guide demonstrates how to compile a COBOL program and execute it to modify an output file using the terminal/command line.

Requirements
Terminal or Command Prompt
COBOL Compiler (cobc)
COBOL Source Code (Folha.cbl)
Output File (Example: Folha)

Steps
1. Compilation
Open your terminal or command prompt.

Navigate to the directory where your COBOL source code (Folha.cbl) is located using the cd command:
cd /path/to/your/cobol/code/directory

Use the COBOL compiler (e.g., cobc) to compile the source code (Folha.cbl). The -x flag generates an executable file.
cobc -x Folha.cbl
This command compiles the COBOL code and generates an executable file (e.g., Folha).

2. Execution
After successful compilation, execute the generated executable to modify the output file.
./Folha
Running this command uses the compiled COBOL program (Folha) to modify the output file. Ensure that the output file (SAIDA.DAT) is available in the directory.
Check the modified output file to view the changes made by the COBOL program.

Notes
Ensure that the COBOL compiler (cobc) is properly installed and configured on your system.