# Shell Scripts Description

This README file provides a description of each shell script in the alx-system_engineering-devops repository, specifically in the 0x03-shell_variables_expansions directory.

## 0-alias

This script creates an alias named `ls` with the value `rm *`. The purpose of this alias is to provide a shortcut for removing all files in the current directory. To use the alias, simply type `ls` in the terminal.

## 1-hello_you

The script `1-hello_you` prints the message "Hello user", where "user" is the current Linux user. It retrieves the username using the `whoami` command and displays the personalized greeting.

## 2-path

The `2-path` script adds the directory `/action` to the `PATH` environment variable. By doing so, it ensures that the shell looks into this directory when searching for a program. This allows for easy execution of programs located in the `/action` directory.

## 3-paths

The `3-paths` script counts the number of directories in the `PATH` environment variable. It uses the `tr` command to replace the colons (`:`) in the `PATH` with newlines, and then uses the `wc -l` command to count the number of lines, which corresponds to the number of directories.

## 4-global_variables

The `4-global_variables` script lists all the environment variables. It uses the `env` command to retrieve the environment variables and displays them in the terminal.

## 5-local_variables

The `5-local_variables` script lists all the local variables, environment variables, and functions. It uses the `set` command to retrieve and display these variables and functions in the terminal.

## 6-create_local_variable

The `6-create_local_variable` script creates a new local variable named `BEST` with the value `School`. This local variable can be accessed and used within the script but is not available outside of it.

## 7-create_global_variable

The `7-create_global_variable` script creates a new global variable named `BEST` with the value `School`. This global variable can be accessed and used both within the script and in other scripts or programs.

## 8-true_knowledge

The `8-true_knowledge` script prints the result of adding 128 to the value stored in the environment variable `TRUEKNOWLEDGE`. It retrieves the value of `TRUEKNOWLEDGE` using the `<span class="math-inline">\` symbol and performs the addition using the \`expr\` command\.
\#\# 9\-divide\_and\_rule
The \`9\-divide\_and\_rule\` script prints the result of dividing the value stored in the environment variable \`POWER\` by the value stored in the environment variable \`DIVIDE\`\. It retrieves the values of \`POWER\` and \`DIVIDE\` using the \`</span>` symbol and performs the division using the `expr` command.

## 10-love_exponent_breath

The `10-love_exponent_breath` script displays the result of raising the value stored in the environment variable `BREATH` to the power of the value stored in the environment variable `LOVE`. It retrieves the values of `BREATH` and `LOVE` using the `$` symbol and performs the exponentiation using the `expr` command.

## 11-binary_to_decimal

The `11-binary_to_decimal` script converts a number from base 2 (binary) to base 10 (decimal). It retrieves the binary number from the environment variable `BINARY` and uses the `echo` command with the `ibase=2` option to convert it to decimal.

## 12-combinations

The `12-combinations` script prints all possible combinations of two letters, except "oo". It uses a loop to iterate through the lowercase letters from "a" to "z" and prints each combination in alphabetical order, starting with "aa".

## 13-print_float

The `13-print_float` script prints a number with two decimal places. It retrieves the number from the environment variable `NUM` and uses the `printf` command with the `%.2f` format specifier to display it with two decimal places.

## 100-decimal_to_hexadecimal

The "100-decimal_to_hexadecimal" script converts a number from base 10 (decimal) to base 16 (hexadecimal). It retrieves the decimal number from the environment variable "DECIMAL" and uses the printf command with the "%x" format specifier to convert and display it in hexadecimal.

## 101-rot13

The "101-rot13" script encodes and decodes text using the rot13 encryption. It reads input from the user and applies the rot13 algorithm to each character, replacing it with the corresponding rot13 character. The script assumes ASCII encoding.

## 102-odd

The "102-odd" script prints every other line from the input, starting with the first line. It uses the awk command with the NR%2==1 condition to select and print the odd-numbered lines.

## 103-water_and_stir
The "103-water_and_stir" script adds the two numbers stored in the environment variables "WATER" and "STIR" and prints the result. It retrieves the numbers from the environment variables and uses the bc command for arithmetic calculations. The numbers are assumed to be in different bases: "WATER" in base "water" and "STIR" in base "stir". The result is displayed in base "bestchol".

## How to use

To use the scripts, first make sure that they are executable. You can do this by running the following command:
chmod +x *.sh

Once the scripts are executable, you can run them by typing the following command:

./script_name.sh

For example, to run the `alias.sh` script, you would type the following command:

./alias.sh

## Contributing

Contributions to this repository are welcome! Feel free to submit a pull request if you have any improvements, suggestions, or additional resources related to Shell scripting.

## License

This project is a part of the ALX System Engineering DevOps curriculum.

