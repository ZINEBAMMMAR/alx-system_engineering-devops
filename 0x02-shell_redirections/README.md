1-who_am_i:

This script simply prints the effective username of the current user. It uses the whoami command to determine the current user's username and then echoes it to the standard output.

2-groups:

This script prints all the groups that the current user is a part of. It uses the groups command to list the groups for the current user and then echoes the list to the standard output.

3-new_owner:

This script changes the owner of the file "hello" to the user "betty." It uses the chown command to change the ownership of the file "hello" to the user "betty."

4-empty:

This script creates an empty file called "hello" in the current working directory. It uses the touch command to create an empty file named "hello."

5-execute:

This script adds execute permission to the owner of the file "hello." It uses the chmod command to modify the permissions of the file "hello" and give the owner execute permission.

6-multiple_permissions:

This script adds execute permission to the owner, the group owner, and other users for the file "hello." It uses the chmod command to modify the permissions of the file "hello" accordingly.

7-everybody:

This script adds execute permission to the owner, the group owner, and other users for the file "hello" without using commas. It also modifies the permissions of the file "hello" using the chmod command.

8-James_Bond:

This script sets the permissions of the file "hello" to "-rwxr-x-wx," which means read, write, execute for the owner, read and execute for the group owner, and write and execute for others. It uses the chmod command to set these permissions.

9-John_Doe:

This script sets the permissions of the file "hello" to "-rwxr-x-wx," similar to the previous script. It uses the chmod command to set these permissions.

10-mirror_permissions:

This script sets the permissions of the file "_hello" to match the permissions of the file "hello." It uses the chmod command along with stat to determine the permissions of "hello" and then applies the same permissions to "_hello."

11-directories_permissions:

This script adds execute permission to all subdirectories in the current directory for the owner, group owner, and other users. It uses the find command to locate subdirectories and the chmod command to modify their permissions.

12-directory_permissions:

This script creates a directory called "my_dir" with permissions 751 in the current working directory. It uses the mkdir and chmod commands to create the directory with the specified permissions.

13-change_group:

This script changes the group owner of the file "hello" to "school." It uses the chown command to change the group ownership of the file.

100-change_owner_and_group:

This script changes the owner and group owner of all files and directories in the current working directory to "vincent" and "staff," respectively. It uses a combination of find, xargs, and chown commands to achieve this.

101-symbolic_link_permissions:

This script changes the owner and group owner of the symbolic link "_hello" to "vincent" and "staff," respectively. It uses the chown command to modify the ownership of the symbolic link.

102-if_only:

This script changes the owner of the file "hello" to "betty" only if it is currently owned by the user "guillaume." It uses conditional statements to check the current owner and then applies the change if the condition is met.

103-Star_Wars:

This script plays the Star Wars Episode IV in the terminal using the telnet command to connect to a remote server that streams the Star Wars ASCII art.
