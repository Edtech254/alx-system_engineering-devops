su betty -> switches the current user to the user betty
whoami -> prints the effective username of the current user
groups -> prints all the groups the current user is part of
sudo chown betty helloy -> changes the owner of the file hello to the user betty
touch hello -> creates an empty file called hello
chmod u+x hello -> adds execute permission to the owner of the file hello
chmod ug+x,o+r hello -> adds execute permission to the owner of the file hello
chmod a+x hello ->  adds execution permission to the owner, the group owner and the other users, to the file hello
chmod ug-rwx,o+rwx hello -> sets the permission to the file hello as follows
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
