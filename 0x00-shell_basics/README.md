# Repository Scripts

This repository contains various scripts that perform different tasks. Below is a description of each script:

## Script 0: Print Current Working Directory
To print the absolute path name of the current working directory, use the command `pwd`.

## Script 1: Display Contents List
To display the contents list of your current directory, use the command `ls`.

## Script 2: Change to Home Directory
To change the working directory to the user's home directory, use the command `cd ~`.

## Script 3: Display Contents in Long Format
To display the current directory contents in a long format, use the command `ls -l`.

## Script 4: Display Contents, Including Hidden Files
To display the current directory contents, including hidden files, use the command `ls -la`.

## Script 5: Display Contents in Long Format with Numerical IDs
To display the current directory contents in the long format, with user and group IDs displayed numerically, and including hidden files, use the command `ls -lan`.

## Script 6: Create Directory
To create a directory named "my_first_directory" in the "/tmp/" directory, use the command `mkdir /tmp/my_first_directory`.

## Script 7: Move File to Directory
To move the file "betty" from "/tmp/" to "/tmp/my_first_directory", use the command `mv /tmp/betty /tmp/my_first_directory`.

## Script 8: Delete File
To delete the file "betty" from "/tmp/my_first_directory", use the command `rm /tmp/my_first_directory/betty`.

## Script 9: Delete Directory
To delete the directory "my_first_directory" from the "/tmp" directory, use the command `rmdir /tmp/my_first_directory`.

## Script 10: Change to Previous Directory
To change the working directory to the previous one, use the command `cd -`.

## Script 11: List Files in Multiple Directories
To list all files in the current directory, the parent of the working directory, and the "/boot" directory in long format, use the command `ls -la . .. /boot`.

## Script 12: Print File Type
To print the type of the file named "iamafile" in the "/tmp" directory, use the command `file /tmp/iamafile`.

## Script 13: Create Symbolic Link
To create a symbolic link to "/bin/ls" named "ls" in the current working directory, use the command `ln -s /bin/ls ls`.

## Script 14: Copy HTML Files
To copy all HTML files from the current working directory to the parent of the working directory, but only copy files that do not exist in the parent directory or are newer than the versions in the parent directory, use the command `cp -u .html ..`.

## Script 15: Move Uppercase Files
To move all files beginning with an uppercase letter to the directory "/tmp/u", use the command `mv [[:upper:]] /tmp/u`.

## Script 16: Delete Files Ending with "."
To delete all files in the current working directory that end with the character ".", use the command `rm *`.

## Script 17: Create Nested Directories
To create the directories "welcome/", "welcome/to/", and "welcome/to/school" in the current directory, use the command `#!/bin/bash mkdir -p welcome/to/school`.

## Script 18: List Files and Directories Separated by Commas
To list all the files and directories of the current directory, separated by commas (","), use the command `#!/bin/bash ls -xamp`.

## Script 19: Create Magic File
To create a magic file "school.mgc" that can be used with the command `file` to detect School data files, use the command `0 string SCHOOL School data !:mime School`.

## Contributing
Contributions to this repository are welcome! Feel free to submit a pull request if you have any improvements, suggestions, or additional resources related to Shell scripting.

## License
This project is a part of the ALX System Engineering DevOps curriculum.

## End of file
