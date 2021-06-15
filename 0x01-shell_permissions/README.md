su betty -swiches the current user to the user betty
whoami - print the effective username of the current user
groups -print all the groups the current user is part of
chown betty hello -change the owner of the file hello to the user betty
touch hello- creates an empty file called hello
chmod u+x - adds execute permission to the owner of the file
chmod u+x,g+x,o+r - execute permission to the owner and the group owner, andread permission to other users
chmod a+x -execute permission to the owner,the group owner and the other users
chmod 007 - owner no permission ,group no permission other user all the permissions
chmod 753 hello -list the content of working directory in a long format
chmod --reference= olleh hello -sets the mode of the file hello the same as olleh
chgrp _ change group owner to holberton for the file hello
sudo chmod -R +111 */ - execute permission for all and regular files should not be changed
mkdir -m 751 dir_holberton- create a directory dir_holberton with permision 751
chown betty:holberton *- change owner and group
chown -h betty:holberton _hello- symbolic link
chown --from=guillaume betty hello- change the owner if the file hello to betty only id it is owned by the user guillaume
telnet towel.blinkenlights.nl -star wars