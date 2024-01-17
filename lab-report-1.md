# Lab Report 1

***	

## No arguments:

```
[user@sahara ~]$ cd
[user@sahara ~]$ ls
lecture1
[user@sahara ~]$ cat
hola!
hola!
```

`cd` is used to change the directory. When cd is used in the terminal it jumps from one directory to another directory. 

`ls` shows the names of the files and folders inside the current working directory. It's another useful status-checking command.

`cat` essentially returns whats initially inputted.

Hence we see the following output as displayed in the above screenshot

## Path to a directory:

```
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$ cd
[user@sahara ~]$ ls lecture1
Hello.class  Hello.java  messages  README
[user@sahara ~]$ cd
[user@sahara ~]$ cat lecture1
cat: lecture1: Is a directory
```

When a directory is provided in the code:

`cd` redirects to the directory lecture1 (Change Directory)

`ls` lists all the files in the directory lecture1

`cat` returns the content of the directory

## Path to a file:

```
[user@sahara ~]$ cd lecture1/messages/en-us.txt
bash: cd: lecture1/messages/en-us.txt: Not a directory
[user@sahara ~]$ ls lecture1/messages/en-us.txt
lecture1/messages/en-us.txt
[user@sahara ~]$ cat lecture1/messages/en-us.txt
Hello World!
```

When a file is provided in the code:

`cd` causes an __error__ as it only works with directories and not files

`ls` essentially lists the file

`cat` in this case is just used to print the contents of the file en-us.txt given by the path



