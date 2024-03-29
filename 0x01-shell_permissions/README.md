# README.md

This is a Bash project that contains various scripts to demonstrate the basic concepts of shell permissions. The scripts are written in Bash and follow the following requirements:

- All scripts are exactly two lines long
- All scripts have a shebang line as `#!/bin/bash`
- All scripts end with a new line
- All scripts are executable
- All scripts use standard commands and built-ins

The project contains the following scripts:

- `0-iam_betty`: A script that switches the current user to the user betty
- `1-who_am_i`: A script that prints the effective username of the current user
- `2-groups`: A script that prints all the groups the current user is part of
- `3-new_owner`: A script that changes the owner of the file hello to the user betty
- `4-empty`: A script that creates an empty file called hello
- `5-execute`: A script that adds execute permission to the owner of the file hello
- `6-multiple_permissions`: A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
- `7-everybody`: A script that adds execution permission to the owner, the group owner and the other users, to the file hello
- `8-James_Bond`: A script that sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissions
- `9-John_Doe`: A script that sets the mode of the file hello to `-rwxr-x-wx`
- `10-mirror_permissions`: A script that sets the mode of the file hello the same as olleh’s mode
Sure, here are the additional scripts that you mentioned:
- `11-directories_permissions`: A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
- `12-directory_permissions`: A script that creates a directory called my_dir with permissions 751 in the working directory.
- `13-change_group`: A script that changes the group owner to school for the file hello
- `100-change_owner_and_group`: A script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
- `101-symbolic_link_permissions`: A script that changes the owner and the group owner of _hello to vincent and staff respectively. The file _hello is a symbolic link.
- `102-if_only`: A script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
- `103-Star_Wars`: A script that will play the StarWars IV episode in the terminal.

## Contributing

Contributions to this project are welcome! If you have any improvements, suggestions, or additional scripts related to shell permissions, feel free to submit a pull request.

## License
These scripts are part of the ALX System Engineering DevOps curriculum.
## End
