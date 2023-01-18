# common-linux-commands-documentation

A documentation of the most commonly used linux commands.

Recommendation: Try the commands on a linux shell on your own to learn more!

## ls

This command is used to "list" the contents in a directory.

```bash
# list directory contents
ls

# do not ignore entries starting with .
ls -a

# use long listing format
ls -l

# combine flags
ls -al
```

## cd

This command is used to change the working directory to the specified path.

```bash
# change directory
cd users/me/this_folder

# change directory to current directory (same as doing nothing)
cd .

# go to parent directory
cd ..
```

## echo

This command is used to display line of text/string that is passed in the argument.

```bash
# prints the string
echo "UwU world!"

# prints all contents in the current directory (same as using ls)
echo *

# puts all contents into a file
echo "UwU world!" > file1.txt

# appends all contents into a file
echo "UwU world!" >> file1.txt
```

## pwd

`pwd` stands for Print Working Directory. This command is used to print the path of the working directory, starting from the root.

```bash
# prints the current working directory
pwd


# $PWD is environment variable in linux for current working directory
echo $PWD
```

## clear

This command is used to clear the terminal windows.

```bash
clear
```

## man

This command is used to get the documentation of a command in linux.

```bash
# get documentation of command ls
man ls

# get documentation of man
man man
```

## cat

`cat` stands for concatenate. This command is used to read data from the file and gives its content as output. It helps us to create, view, concatenate files.

```bash
# view contents of file1.txt on terminal
cat file1.txt

# view contents of multiple files
cat file1.txt file2.txt

# copy contents of file1.txt to file2.txt
cat file1.txt > file2.txt

# append contents of file1.txt to file2.txt
cat file1.txt >> file2.txt
```

## touch

This command is used to create a file without the contents.

```bash
# creates a file named file1.txt
touch file1.txt

# creates multiple commands in same command
touch file1.txt file2.txt file3.txt file4.txt
```

## mkdir

This command is used to create folders/directories.

```bash
# creates a directory
mkdir my_folder

# creates the folder your_uwu inside my_folder only if my_folder exists, otherwise throws error
mkdir my_folder/your_uwu

# creates the folder and all the parent folders
mkdir -p folder_1/folder_2/folder_3/folder_4
```

## mv

```bash

```

## cp

```bash

```

## rm

```bash

```

## rmdir

```bash

```

## sort

```bash

```

## cut

```bash

```

## sudo

```bash

```

## find

```bash

```

## awk

```bash

```

## sed

```bash

```

## grep

```bash

```

## rev

```bash

```

## chmod

```bash

```
