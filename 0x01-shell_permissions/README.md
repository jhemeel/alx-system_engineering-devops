## su betty
### This command change the user to betty

## whoami
### This command otput the current user

## groups
### This command prints out all the groups the currentlu user belong to

## chown betty 3-new_owner
### The command changes the owner of a file

## echo -n "" > hello
### This command creates a new empty file

## chmod 744 hello
### This adds only the execute right for the owner

## chmod 774 hello
## This command allows owner and group owner to executer the file, but others to just read

##chmod 751 hello
### This command allows everybody to read,write and exexcute.

##chmod 007
### Only others have all access, owner and group:none

## chmod 753 hello
### octal notation command for -rwxr-x-wx.

## sudo find . -type d -exec chmod ugo=+x {} \
script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed
