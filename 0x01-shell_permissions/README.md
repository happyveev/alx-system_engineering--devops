su betty--script that changes your user ID to betty
id -un--prints the effective username of the current user
id -Gn--prints all the groups the current user is part of
chown betty hello--changes the owner of the file hello to the user betty
touch hello--create an empty file called hello
chmod u+x hello--add execute permission to the owner of the file hello
chmod ug+x,o+r hello--add execute permission to user and group owner and read permission to others to the file hello
chmod ugo+x hello--adds execution permission to all users to the file hello
chmod 007 hello--set permission to the file so that owner and group dont have any permission and other users have all permissions
chmod 753 hello--set permission so owner has all permissions, group has read and execute permissions and others have write and execute permissions