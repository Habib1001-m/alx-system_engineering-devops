# Shell Redirections techniques

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
- `11-directories`: Counts the number of directories and subdirectories in the current directory.
- `12-newest_files`: Displays the 10 newest files in the current directory.
- `13-unique`: Prints only words that appear exactly once from a list of words.
- `14-hidethisword`: Displays lines containing the pattern "root" from a file.
- `19-AZ`: Displays lines starting with either "A" or "Z" from the `/etc/ssh/sshd_config` file.
- `20-hiago`: Removes all occurrences of the letter "c" (both uppercase and lowercase) from the input.
- `21-reverse`: Reverses the input.
- `22-users_and_homes`: Displays all users and their home directories, sorted by users.
- `24-empty_casks`: Lists the names of empty files and directories in the current directory and its subdirectories.
- `25-acrostic`: Decodes an acrostic by extracting the first character of each line.
- `26-the_biggest_fan`: Parses web server logs in TSV format and displays the 11 hosts or IP addresses that made the most requests.
  # To make the files executable, you can use the `chmod` command. For example, to make `0-hello_world` executable, you can run the following command:

```bash
chmod +x 0-hello_world
```
## Contributing

Contributions to this project are welcome! If you have any improvements, suggestions, or additional scripts related to shell permissions, feel free to submit a pull request.

## License

These scripts are part of the ALX System Engineering DevOps curriculum.

## End
