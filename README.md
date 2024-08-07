# REPL Application Documentation

## Overview

This application provides a Read-Eval-Print Loop (REPL) interface for running code. It allows users to input code interactively, which is then executed using a specified command.

```shell

PS G:\NueRepl> nRepl  
 :: Start typing your code (type `$$END` to run your code):
 :: Type `$$version` for version 
 :: Type `$$help` for help       
 :: Type `$$END` to end your code
println("Hallo worlds") 

let abc = [1,2,3,4,5,6,7,8,9,11]

for a in abc {

println(a+(a*(a/2)))

}

$$END
Hallo worlds
1.5
4
7.5
12
17.5
24
31.5
40
49.5
71.5
PS G:\fri3nds\x-category-projects\NueRepl> 

```

## Usage

1. Start the application.
2. Begin typing your code.
3. Use special commands as needed.
4. Type `$$END` when you're finished to execute your code.

## Special Commands

- `$$END`: Signals the end of your code input and executes it.
- `$$version`: Displays the current version of the REPL.
- `$$help`: Shows available commands and basic usage information.

## Workflow

1. The application prompts you to start typing your code.
2. Enter your code line by line.
3. Use special commands if needed.
4. When finished, type `$$END`.
5. Your code will be saved to a temporary file and executed.
6. The output of your code will be displayed.
7. The temporary file is automatically deleted after execution.

## Notes

- The application uses a specific command to execute your code, which may vary depending on your system configuration.
- Any errors during file operations or code execution will be displayed.

## Error Handling

The application handles and displays errors for:
- Writing to the temporary file
- Executing the command
- Deleting the temporary file

For any issues or unexpected behavior, check the error messages provided by the application.

