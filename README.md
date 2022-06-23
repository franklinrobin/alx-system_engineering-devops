#Shell basics description
0. pwd  prints the absolute path name of the current working directory.
1. ls  lists content of directories 
2. cd  Changes directory
3. ls -l lists directory content in long form
4. ls -la lists content of directories in long form including hidden files
5. ls -la  lists all files in long form with user and group IDs displayed numerically
6. mkdir /tmp/my_first_directory  Creates a directory named my_first_directory in the /tmp/ directory
7. mv /tmp/betty /tmp/my_first_directory/betty  Moves the file betty from /tmp/ to /tmp/my_first_directory
8. rm /tmp/my_first_directory/betty Delete the file betty
9. rmdir /tmp/my_first_directory  Delete the directory my_first_directory that is in the /tmp directory
10. cd changes the working directory to the previous one
11. ls -la . .. /boot List all files/directories, including hidden files/directories, from 3 separate directories: current directory,     parent of working directory, and /boot directory
12. file /tmp/iamafile prints the type of the file named iamafile which is in the /tmp/ directory 
13. ln -s /bin/ls __ls__ Create a symbolic link named __ls__ for /bin/ls
14. cp -u *.html .. copies all the HTML files from the current working directory to the parent of the working directory, but only copy    files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working direc    tory
15.  mv [[:upper:]]* /tmp/u moves all files beginning with an uppercase letter to the directory /tmp/u
16. rm *~ Deletes all files in the current directory that end with a ~
17. mkdir -p welcome/to/my_first_directory creates the directories welcome/, welcome/to/ and welcome/to/school in the current director    y
18. ls -pam lists all the files and directories of the current directory, separated by commas Directory names should end with a slash     (/)Files and directories starting with a dot (.) should be listed
     The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
 Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line
19. 0 string SCHOOL School data !:mime school Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0. 
