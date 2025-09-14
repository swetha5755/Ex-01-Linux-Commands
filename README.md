# Ex-01-Linux-Commands
# NAME: Swetha S
# REG NO: 212224040344

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

<img width="895" height="175" alt="image" src="https://github.com/user-attachments/assets/128b4145-5641-4e13-84f2-1b9f8e5e47a3" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="414" height="147" alt="image" src="https://github.com/user-attachments/assets/ee3d3107-aba0-4fde-bc72-034eaffcd78b" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="351" height="103" alt="image" src="https://github.com/user-attachments/assets/8342d1a1-b6dc-43e1-ac1d-3957cf290104" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="355" height="103" alt="image" src="https://github.com/user-attachments/assets/b5c74bec-3125-4259-99bd-e7f0c09feb82" />



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="355" height="103" alt="image" src="https://github.com/user-attachments/assets/8a5729cd-ef86-40df-b0ad-be625dd153b3" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="697" height="338" alt="image" src="https://github.com/user-attachments/assets/377713a4-4da4-4f59-8bf0-2ea7a7d430e2" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="494" height="98" alt="image" src="https://github.com/user-attachments/assets/e6a714c5-a3a1-4afe-b707-3507bea9a4b8" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="1308" height="444" alt="image" src="https://github.com/user-attachments/assets/561d47ae-421f-4f43-915a-569f5fdd3d68" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="1308" height="444" alt="image" src="https://github.com/user-attachments/assets/b5ed8f03-663f-4e5f-a0ba-78314384002e" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="1308" height="444" alt="image" src="https://github.com/user-attachments/assets/ef1883e5-6e51-4642-a621-091fda4d82db" />



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="1311" height="592" alt="image" src="https://github.com/user-attachments/assets/fc936c85-ad39-4bb8-9b6a-e381be25649e" />



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="1311" height="592" alt="image" src="https://github.com/user-attachments/assets/cd5959cb-c496-468b-99c5-cd7e65939fb6" />

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="2032" height="361" alt="image" src="https://github.com/user-attachments/assets/712698ff-1f69-434a-a504-037189135c40" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="738" height="207" alt="image" src="https://github.com/user-attachments/assets/903b91c6-2c97-4caa-8550-c942777712d4" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="738" height="207" alt="image" src="https://github.com/user-attachments/assets/7071d837-92a4-425c-88a6-8f4be609398a" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="738" height="207" alt="image" src="https://github.com/user-attachments/assets/9a91cb07-0337-4d7a-8900-d807751c4613" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

 <img width="1131" height="338" alt="image" src="https://github.com/user-attachments/assets/d406914c-57cd-4a9b-8d77-780f3b8cd524" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="1131" height="338" alt="image" src="https://github.com/user-attachments/assets/2fd6194b-8fd3-40d9-a675-40987a06d22a" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="1131" height="338" alt="image" src="https://github.com/user-attachments/assets/8785cf29-328a-4eb9-8830-1d1156195dc8" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="1131" height="338" alt="image" src="https://github.com/user-attachments/assets/aa0ddec1-43c9-488f-a477-73964078eb1a" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

<img width="1156" height="144" alt="image" src="https://github.com/user-attachments/assets/059fb42d-2e3d-4304-9afc-a6934695ef96" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="936" height="124" alt="image" src="https://github.com/user-attachments/assets/ddc8b562-6cc5-43a8-b8af-381b04243c44" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="1428" height="226" alt="image" src="https://github.com/user-attachments/assets/f4cb96da-72cc-4588-990b-2725831e1099" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="1428" height="226" alt="image" src="https://github.com/user-attachments/assets/b6d71213-4177-4466-804e-8e5923c2e1f3" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="1428" height="226" alt="image" src="https://github.com/user-attachments/assets/bd4d9eb6-557c-461c-8197-7350dde19aa7" />

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="725" height="200" alt="image" src="https://github.com/user-attachments/assets/468d05c4-e9a6-44fc-98de-f9df699add7a" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="527" height="169" alt="image" src="https://github.com/user-attachments/assets/55751fae-2fbd-4608-a869-ae813302eb52" />


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="527" height="169" alt="image" src="https://github.com/user-attachments/assets/b0bb9b63-526a-4573-917c-258e4297cdd4" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="527" height="169" alt="image" src="https://github.com/user-attachments/assets/95f48e75-8ba0-46f8-9507-433dee8b4d7b" />






















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
