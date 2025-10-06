# Ex-01-Linux-Commands


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
 
<img width="841" height="61" alt="Screenshot 2025-09-08 191419" src="https://github.com/user-attachments/assets/32566ef2-fbf1-4645-a4e2-1681c80f7755" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="223" height="64" alt="Screenshot 2025-09-08 191433" src="https://github.com/user-attachments/assets/fbaa95bc-80a4-4083-b995-f045972681aa" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="1685" height="207" alt="Screenshot 2025-09-08 200008" src="https://github.com/user-attachments/assets/dc443101-a089-425a-ae85-db7ef1a46611" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="1574" height="227" alt="Screenshot 2025-09-08 200021" src="https://github.com/user-attachments/assets/cd893401-e9ce-408c-94ac-575e768ed00b" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="615" height="290" alt="Screenshot 2025-09-08 200049" src="https://github.com/user-attachments/assets/15810901-c8eb-4693-a85c-7b593ff0144d" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="589" height="180" alt="Screenshot 2025-09-08 200102" src="https://github.com/user-attachments/assets/7a37b4a8-46c8-451d-9346-cbd4c2d3cce2" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="600" height="245" alt="Screenshot 2025-09-08 200114" src="https://github.com/user-attachments/assets/490aa1d7-ab5b-4a66-a3c7-68dd74c7a4f7" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="535" height="66" alt="Screenshot 2025-09-08 200122" src="https://github.com/user-attachments/assets/6c6ade4a-cfd4-477c-9680-139086f56d43" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="499" height="166" alt="Screenshot 2025-09-08 200131" src="https://github.com/user-attachments/assets/b88723d8-3b19-4779-9efa-cacb80f12dc1" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="530" height="491" alt="Screenshot 2025-09-08 200142" src="https://github.com/user-attachments/assets/8fcd0340-869a-43b7-9e37-3601a037c2e3" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="712" height="320" alt="Screenshot 2025-09-08 200150" src="https://github.com/user-attachments/assets/d28204e0-9b1f-4f14-a691-4043fcff36d2" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="498" height="766" alt="Screenshot 2025-09-08 200207" src="https://github.com/user-attachments/assets/3ba36785-c479-4a0c-b361-fbeda22b89af" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="356" height="327" alt="Screenshot 2025-09-08 200219" src="https://github.com/user-attachments/assets/e2ee9ead-af8e-40a0-bf14-51317e3137dd" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="1791" height="75" alt="Screenshot 2025-09-08 200300" src="https://github.com/user-attachments/assets/0c879061-a8b4-43bd-a803-c175ee72bdc7" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="571" height="110" alt="Screenshot 2025-09-08 200308" src="https://github.com/user-attachments/assets/86ed1648-1454-4649-99dc-fc51f9ea72f6" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="753" height="574" alt="Screenshot 2025-09-08 200316" src="https://github.com/user-attachments/assets/0cf99108-812b-4189-9d17-d842a90da943" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="905" height="128" alt="image" src="https://github.com/user-attachments/assets/5fd22078-fff6-4c4e-b02e-d9443a53740e" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="651" height="294" alt="Screenshot 2025-09-08 200334" src="https://github.com/user-attachments/assets/9b0af902-43d2-405f-a826-0181fe9adf22" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="636" height="158" alt="image" src="https://github.com/user-attachments/assets/39b3ba29-246d-42ae-ab10-65c89d361d7e" />




### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="432" height="120" alt="Screenshot 2025-09-08 200354" src="https://github.com/user-attachments/assets/cc3e5e8a-57f1-4e72-83c3-a0ad4efea806" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="1608" height="187" alt="Screenshot 2025-09-08 200405" src="https://github.com/user-attachments/assets/84a99db0-b50e-4357-a416-fa9bc61521a3" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

 <img width="840" height="225" alt="Screenshot 2025-09-08 200415" src="https://github.com/user-attachments/assets/7e8155ed-e6f1-4998-ab7e-c50195ea9b67" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="1037" height="188" alt="Screenshot 2025-09-08 200425" src="https://github.com/user-attachments/assets/42dda223-09a4-45bb-8b82-cc80e42d487a" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="1793" height="279" alt="Screenshot 2025-09-08 200441" src="https://github.com/user-attachments/assets/c888ae3e-340c-4e0a-9f6d-eb189bc2751f" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="435" height="582" alt="Screenshot 2025-09-08 200452" src="https://github.com/user-attachments/assets/e7502be5-9795-4a81-9ee1-ee607daf2c61" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="595" height="430" alt="image" src="https://github.com/user-attachments/assets/e718b3e2-ded9-4eca-a677-876af3724f40" />



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="435" height="84" alt="Screenshot 2025-09-08 213124" src="https://github.com/user-attachments/assets/3d1de018-e7d0-45c7-8b61-939d96687eb9" />
<img width="489" height="258" alt="Screenshot 2025-09-08 213134" src="https://github.com/user-attachments/assets/da6b7ce0-9ff4-4954-ab31-d437e4a2b93f" />




### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="1071" height="73" alt="Screenshot 2025-09-08 213156" src="https://github.com/user-attachments/assets/61bb6e41-cce3-4676-bae3-c91926a0be1a" />


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="1302" height="423" alt="image" src="https://github.com/user-attachments/assets/5c44f779-d6ab-4564-b81e-1fbf8a4469c2" />



### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="416" height="98" alt="Screenshot 2025-09-08 200704" src="https://github.com/user-attachments/assets/f8bc55c8-1fcc-461c-964e-25d18b6e0607" />





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
