0-iambetty:script that switches the current user to the user betty.

1-whoami:script that prints the effective username of the current user.

2-groups:script that prints all the groups the current user is part of.

3-newowner:script that changes the owner of the file hello to the user betty.

4-empty:script that creates an empty file called hello.

5-execute:script that adds execute permission to the owner of the file hello.

6-multiplepermissions:script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

7-everybody:script that adds execution permission to the owner, the group owner and the other users, to the file hello.

8-JamesBond:script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions


9-JohnDoe:script that sets the mode of the file hello to this:-rwxr-x-wx

10-mirrorpermissions:script that sets the mode of the file hello the same as olleh’s mode. (olleh's mode:-rw-rw-r--)

11-directoriespermissions:script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

12-directorypermissions:script that creates a directory called mydir with permissions 751 in the working directory.

13-changegroup:script that changes the group owner to school for the file hello
