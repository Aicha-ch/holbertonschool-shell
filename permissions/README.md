Su betty: is a script that switches the current user to the userbetty
Whoami: is a script that prints the effective username of the current user
groups: is a script that prints all the groups the current user is part of
chown betty hello: is  a script that changes the owner of the file hello to the user betty
touch: is a script that creates an empty file called hello
chmod u+x hello: is a script that adds execute permission to the owner of the file hello
chmod 754 hello: is a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod a+x hello: is  a script that adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 753 hello: is a script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
chmod -R a+rX *: is a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
mkdir -m 751 my_dir: is a script that creates a directory called my_dir with permissions 751 in the working directory
chgrp school hello: is a script that changes the group owner to school for the file hello
chown -R vincent:staff *: is a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory

