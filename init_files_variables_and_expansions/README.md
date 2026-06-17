# Shell, init files, variables and expansions

This project introduces shell initialization files, shell variables, environment variables, aliases, arithmetic operations, and shell expansions.

## Learning Objectives

* Understand shell initialization files
* Create and manage shell variables
* Understand the difference between local and environment variables
* Use shell expansions
* Perform arithmetic operations in Bash
* Create and manage aliases
* Understand reserved variables such as `HOME`, `PATH`, and `PS1`
* Use special parameters such as `$?`

## Files

| File                      | Description                                                            |
| ------------------------- | ---------------------------------------------------------------------- |
| 0-alias                   | Creates an alias named `ls` with the value `rm -f *`                   |
| 1-hello_you               | Prints `hello user`, where user is the current Linux user              |
| 2-path                    | Adds `/action` to the `PATH`                                           |
| 3-paths                   | Counts the number of directories in the `PATH`                         |
| 4-global_variables        | Lists environment variables                                            |
| 5-local_variables         | Lists local variables, environment variables, and functions            |
| 6-create_local_variable   | Creates a new local variable                                           |
| 7-create_global_variable  | Creates a new global variable                                          |
| 8-true_knowledge          | Prints the result of adding 128 to the value stored in `TRUEKNOWLEDGE` |
| 9-divide_and_rule         | Prints the result of `POWER` divided by `DIVIDE`                       |
| 10-love_exponent_breath   | Displays the result of `BREATH` raised to the power of `LOVE`          |
| 11-binary_to_decimal      | Converts a binary number to decimal                                    |
| 12-combinations           | Prints all possible two-letter combinations except `oo`                |
| 13-print_float            | Prints a number with two decimal places                                |
| 14-decimal_to_hexadecimal | Converts a decimal number to hexadecimal                               |
| 100-rot13                 | Encodes and decodes text using ROT13                                   |
| 101-odd                   | Prints every other line from input                                     |
| 102-water_and_stir        | Adds two numbers stored in custom bases                                |

## Requirements

* Ubuntu 20.04 LTS
* All scripts are exactly two lines long
* All files start with `#!/bin/bash`
* All files are executable
* No use of `&&`, `||`, or `;`
* No use of `bc`, `sed`, or `awk`
