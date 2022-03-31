#!/bin/bash
0. My name is betty switches the current user to betty using (su betty)
1. To print effective username of the current user, use (whoami)
2. Script prints all the groups the current user is part of.(groups)
3. Change the owner of a file to betty (chown betty hello)
4. Script that creates an empty file 'hello' (touch hello)
5. script that adds execute permission to the owner of the file hello (chmod u+x hello)
6. Script that add execute permissions to file owner and group and give others read permission(chmod u+x,g+x,o+r)
7. A script that adds execution permission to the owner, the group owner and the other users, to the file hello (chmod ugo+x)
8. Write a script that sets the permission to the file hello as follows:
   Owner: no permission at all

   Group: no permission at all

   Other users: all the permissions (chmod 007)
9. A script that sets the mode of the file hello to this:-rwxr-x-wx (chmod 753 hello)
10. Write a script that sets the mode of the file hello the same as olleh’s mode.
    The file hello will be in the working directory

    The file olleh will be in the working directory (sudo chmod --reference=oleh hello)
11. A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other    users. Regular files should not be changed. (chmod a+x *)
12.
13.
