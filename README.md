# Ex-01-Linux-Commands
#NAME: SWETHA S
#REG.NO:212224040344

## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 
<img width="414" height="147" alt="image" src="https://github.com/user-attachments/assets/beb28310-f194-4d69-8068-3aa4236b1dc4" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="414" height="147" alt="image" src="https://github.com/user-attachments/assets/b7c72f03-9e6a-4b9d-b1a4-42168556635f" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="351" height="103" alt="image" src="https://github.com/user-attachments/assets/21d278de-5b08-4e83-aa57-5f7679280348" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="355" height="103" alt="image" src="https://github.com/user-attachments/assets/41f6491e-c6af-48c2-a1c9-ad02449d5c18" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="361" height="110" alt="image" src="https://github.com/user-attachments/assets/a06a8718-df2a-4e5a-bc74-6cd897f3f110" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="697" height="338" alt="image" src="https://github.com/user-attachments/assets/0b30a18c-afa7-49b8-85d5-d718f7562a9c" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="494" height="98" alt="image" src="https://github.com/user-attachments/assets/7f1683b5-3144-49c8-b4fa-cead72218a86" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="1024" height="334" alt="image" src="https://github.com/user-attachments/assets/4c4da6e3-c805-4515-81ab-663855f242a6" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="1024" height="334" alt="image" src="https://github.com/user-attachments/assets/41b30844-7ba7-4d43-9f35-ca1a82a64e7b" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="737" height="292" alt="image" src="https://github.com/user-attachments/assets/5f3e011d-be3f-484b-addb-a9e543589895" />



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="737" height="292" alt="image" src="https://github.com/user-attachments/assets/f02803b7-e8e2-4b5a-9fe2-5361c5e61287" />



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="737" height="292" alt="image" src="https://github.com/user-attachments/assets/5c682533-6a0d-4094-828a-bfb99e597c4c" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="737" height="292" alt="image" src="https://github.com/user-attachments/assets/219133e9-348f-4ee9-8036-716116d83828" />



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="737" height="292" alt="image" src="https://github.com/user-attachments/assets/28c637a7-74b8-40ca-9bbd-cd09fb1ccde3" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="737" height="292" alt="image" src="https://github.com/user-attachments/assets/0d3e3660-10a1-4062-9d0b-f68cb22ffabd" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="1131" height="338" alt="image" src="https://github.com/user-attachments/assets/bcaccd1b-126c-4d88-b276-e43c754c15b7" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="1131" height="338" alt="image" src="https://github.com/user-attachments/assets/56bc3e92-e4e1-4ec1-97b4-80d3c5c4beb5" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="731" height="148" alt="image" src="https://github.com/user-attachments/assets/08fee3f5-0e3d-47ed-812d-5c1868c990e3" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="910" height="770" alt="image" src="https://github.com/user-attachments/assets/8639f589-c12b-4327-8d68-ebc6f09a106e" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="1323" height="765" alt="image" src="https://github.com/user-attachments/assets/ab31b45d-a360-4d3d-807f-1f4f1448da47" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="1156" height="144" alt="image" src="https://github.com/user-attachments/assets/1e9414a1-e60f-4a2a-86e2-7b5d519d4523" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="936" height="124" alt="image" src="https://github.com/user-attachments/assets/085a4282-e7c3-4b9a-8891-fb277935c1ff" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="1428" height="226" alt="image" src="https://github.com/user-attachments/assets/93685373-eaca-4c3a-be18-b2b87c9d7bc7" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="488" height="238" alt="image" src="https://github.com/user-attachments/assets/3cb79961-ae7f-4c25-ba13-192068c4ee04" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="733" height="354" alt="image" src="https://github.com/user-attachments/assets/524775ce-449d-408b-8c49-ccb1965f335a" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="725" height="200" alt="image" src="https://github.com/user-attachments/assets/70c71839-f4e3-4818-a291-3acd2b2d95f3" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="527" height="169" alt="image" src="https://github.com/user-attachments/assets/27fd77fe-e49b-4fb3-be14-8b40f0ef6f3d" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="1100" height="319" alt="image" src="https://github.com/user-attachments/assets/671242a8-81aa-450c-b173-cae0b99c7d98" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="491" height="132" alt="image" src="https://github.com/user-attachments/assets/5ea727f0-e080-4d59-8896-b21dc9c0c74a" />






















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
