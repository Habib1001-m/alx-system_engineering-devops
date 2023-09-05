## Shell Redirections

Shell redirections are a way to control where the output of a command is sent or where the input for a command comes from.

There are three main types of shell redirections:

* **Output redirection:**
    * This redirects the output of a command to a file. For example, the command `ls -la > files.txt` will list all the files in the current directory and redirect the output to the file `files.txt`.
* **Input redirection:**
    * This redirects the input for a command from a file. For example, the command `cat files.txt` will read the contents of the file `files.txt` and print them to the standard output.
* **Append redirection:**
    * This redirects the output of a command to a file, appending the output to the end of the file. For example, the command `ls -la >> files.txt` will list all the files in the current directory and append the output to the file `files.txt`.

Shell redirections can be used to automate tasks, process large amounts of data, and troubleshoot problems.

Here are some examples of how shell redirections can be used:

* To save the output of a command to a file: `ls -la > files.txt`
* To read the contents of a file into a command: `cat files.txt`
* To append the output of a command to a file: `ls -la >> files.txt`
* To redirect the output of a command to a different terminal: `ls -la | tee files.txt`
* To redirect the input of a command from a different terminal: `cat < files.txt`

# Shell Redirections techniques## Shell Redirections

Shell redirections are a way to control where the output of a command is sent or where the input for a command comes from.

There are three main types of shell redirections:

* **Output redirection:**
    * This redirects the output of a command to a file. For example, the command `ls -la > files.txt` will list all the files in the current directory and redirect the output to the file `files.txt`.
* **Input redirection:**
    * This redirects the input for a command from a file. For example, the command `cat files.txt` will read the contents of the file `files.txt` and print them to the standard output.
* **Append redirection:**
    * This redirects the output of a command to a file, appending the output to the end of the file. For example, the command `ls -la >> files.txt` will list all the files in the current directory and append the output to the file `files.txt`.

Shell redirections can be used to automate tasks, process large amounts of data, and troubleshoot problems.

Here are some examples of how shell redirections can be used:

* To save the output of a command to a file: `ls -la > files.txt`
* To read the contents of a file into a command: `cat files.txt`
* To append the output of a command to a file: `ls -la >> files.txt`
* To redirect the output of a command to a different terminal: `ls -la | tee files.txt`
* To redirect the input of a command from a different terminal: `cat < files.txt`

# Shell Redirections

This repository contains shell scripts that demonstrate various shell redirection techniques.

## Scripts

- `0-hello_world`: Prints "Hello, World" to the standard output.
- `1-confused_smiley`: Displays a confused smiley "(Ôo)'".
- `2-hellofile`: Displays the content of the `/etc/passwd` file.
- `3-twofiles`: Displays the content of both the `/etc/passwd` and `/etc/hosts` files.
- `4-lastlines`: Displays the last 10 lines of the `/etc/passwd` file.
- `5-firstlines`: Displays the first 10 lines of the `/etc/passwd` file.
- `6-third_line`: Displays the third line of the `iacta` file.
- `7-file`: Creates a file named `*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text "Best School".
- `8-cwd_state`: Writes the result of the `ls -la` command into the file `ls_cwd_content`.
- `9-duplicate_last_line`: Duplicates the last line of the `iacta` file.
- `10-no_more_js`: Deletes all regular files with a `.js` extension in the current directory and its subdirectories.

# This repository contains shell scripts that demonstrate various shell redirection techniques.
Feel free to explore each script to learn more about shell redirections and their usage.

## Scripts

- `0-hello_world`: Prints "Hello, World" to the standard output.
- `1-confused_smiley`: Displays a confused smiley "(Ôo)'".
- `2-hellofile`: Displays the content of the `/etc/passwd` file.
- `3-twofiles`: Displays the content of both the `/etc/passwd` and `/etc/hosts` files.
- `4-lastlines`: Displays the last 10 lines of the `/etc/passwd` file.
- `5-firstlines`: Displays the first 10 lines of the `/etc/passwd` file.
- `6-third_line`: Displays the third line of the `iacta` file.
- `7-file`: Creates a file named `*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text "Best School".
- `8-cwd_state`: Writes the result of the `ls -la` command into the file `ls_cwd_content`.
- `9-duplicate_last_line`: Duplicates the last line of the `iacta` file.
- `10-no_more_js`: Deletes all regular files with a `.js` extension in the current directory and its subdirectories.