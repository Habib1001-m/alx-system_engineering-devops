Shell variables expansions

This repository contains 13 bash scripts that demonstrate the use of shell variables expansions.
Scripts

    alias.sh - Creates an alias named ls that is assigned the value rm *.
    hello_you.sh - Prints the message "hello user" to the terminal, where user is the current Linux user.
    path.sh - Adds the directory /action to the PATH environment variable.
    paths.sh - Counts the number of directories in the PATH environment variable.
    global_variables.sh - Lists all environment variables.
    local_variables.sh - Lists all local variables and environment variables, and functions.
    create_local_variable.sh - Creates a new local variable named BEST and assigns it the value School.
    create_global_variable.sh - Creates a new global variable named BEST and assigns it the value School.
    true_knowledge.sh - Prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE. If the environment variable TRUEKNOWLEDGE is not set, then the value 0 is used instead.
    divide_and_rule.sh - Prints the result of POWER divided by DIVIDE. If the environment variables POWER or DIVIDE are not set, then the value 1 is used instead.
    love_exponent_breath.sh - Displays the result of BREATH to the power LOVE. If the environment variables BREATH or LOVE are not set, then the value 1 is used instead.
    binary_to_decimal.sh - Converts a number from base 2 to base 10. The number in base 2 is stored in the environment variable BINARY. If the environment variable BINARY is not set, then the value 0 is used instead.
    combinations.sh - Prints all possible combinations of two letters, except oo. The letters are lower cases, from a to z. One combination per line is printed. The output is alpha ordered, starting with aa. The script file should contain maximum 64 characters.
    print_float.sh - Prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM. If the environment variable NUM is not set, then the value 0.0 is used instead.

How to use

To use the scripts, first make sure that they are executable. You can do this by running the following command:

chmod +x *.sh


Once the scripts are executable, you can run them by typing the following command:

./script_name.sh


For example, to run the `alias.sh` script, you would type the following command:

./alias.sh


This will create an alias named `ls` that is assigned the value `rm *`.
