# Basic Linux Commands
- Some of the basic linux commands are as follows:
    - `ls`
    - `mkdir`
    - `pwd`
    - `cd` 
    - `man`
    - `help`
    - `cp`
    - `mv`
    - `rm`
- These are some of the common linux commands.
- Let's understand them one-by-one.

## The `ls` command
- It is one of the most common linux command used most oftenly.
- It stands for ***list***.
- It lists all the files & directories that are present in the current directory.
- The `ls -a` shows all the directories including those are hidden, e.g. `.themes`, `.icons`, etc.
```
as@as-VirtualBox~$ ls
Desktop Documents Downloads Music 
Videos Picture Public Template 
as@as-VirtualBox~$
```

## The `mkdir` command
- It stands for ***make directory***.
- It is used to create a new directory.

```
as@as-VirtualBox~$ mkdir test
as@as-VirtualBox~$ ls
Desktop Documents Downloads Music 
Videos Picture Public Template test
as@as-VirtualBox~$
```

## The  `pwd` command
- It stands for ***print working directory***.
- It displays currently which directory, you are in.
```
as@as-VirtualBox~$ pwd
/home/as
as@as-VirtualBox~$
```

## The `cd` command
- It stands for ***change directory***.
- This command is used to change directories.
```
as@as-VirtualBox~$ cd Music
as@as-VirtualBox: ~/Music~$
```

### Did you noticed `~/` in the beginning of Music. It basically means `/home/username`.

## The `cp` command
- This is the copy command.
- It is used to copy file and directories into designated location.

```
as@as-VirtualBox: ~/Documents$ cp newfile.txt /home/as/Downloads
as@as-VirtualBox: ~/Documents$ cd ..
as@as-VirtualBox~$ cd Downloads
as@as-VirtualBox: ~/Downloads$ ls
newfile.txt
as@as-VirtualBox: ~/Downloads$