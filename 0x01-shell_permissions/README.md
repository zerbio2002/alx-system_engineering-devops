Shell, Permissions Exercise 

Task 0: su betty script will switch user to betty.

Task 1: id -un prints current username.

Task 2: id -Gn will print all group part of current user.

Task 3: chown betty hello will change owner of the file hello to user betty.

Task 4: touch hello command will create empty file called hello.

Task 5: chmod u+x hello command will make hello file excutable permission.

Task 6: chmod u+x,g+o,o+x hello script will give execuation permission to current user and group, and read permission to other users.

Task 7: chmod ugo+x hello will give permission to all owner, group and other users.

Task 8: chmod 007 hello will set no permission to all owner, group and other to hello file.

Task 9: chmod 753 hello set permission to owner to execute, read and write, and set group to read and execute, others write and execute permissions on hello file.

Task 10: hello file copies mode from olleh file using scrit chmod --reference olleh hello.

Task 11: adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

