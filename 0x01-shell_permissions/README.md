su betty--script that changes your user ID to betty
id -un--prints the effective username of the current user
id -Gn--prints all the groups the current user is part of
chown betty hello--changes the owner of the file hello to the user betty
touch hello--create an empty file called hello
chmod u+x hello--add execute permission to the owner of the file hello
chmod ug+x,o+r hello--add execute permission to user and group owner and read permission to others to the file hello