 # PROJECT-1-LINUX
 # File manipulation
## 1. Sudo command
sudo : superuser do performs tasks requiring administartive or root permissions

**`sudo apt update`**

<img width="687" alt="sudo apt upgrade" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/3ed99691-711c-4da6-bcb1-8f66f9e8e416">

## 2. pwd command
this commands finds the path of current working directory

**`pwd`**

<img width="675" alt="pwd" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/75df6f7a-f451-49d3-bf53-3ddb67f17104"

## 3. cd command
navigates through the linus files and directories
requies directory name 
**` cd downloads**`
<img width="441" alt="cd" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/ca776624-ecd2-4ecb-be1d-71eae53de6e8">

## 4. ls command
this command lists files and directories within a system

**`ls `**

lists all files in a subdirectory
**`ls -R`**

<img width="725" alt="ls a" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/98ca6e0e-4600-4c8f-9eba-f00d596690ad">

shows hidden files

**`ls -a`**
**`ls -1h`**
<img width="696" alt="ls b" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/1f9c748a-245e-4151-a8c4-e1f7bc2028ca">

## 5. cat command
this command lists, combines and writes file content to the standard output
Concatenate.

**`cat Project`**

<img width="577" alt="cat 1" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/150cb50b-c8a2-4355-8a49-0ac4a71b2dcd">

display files in reverse order

**`tac project`**

<img width="671" alt="cat 2" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/8e683ab0-f922-45f4-8ea4-7b0df9f31133">

merges two files into a third file

**`cat`**

## 6. cp command
this command copies files, directories and the content of directories
```
cp project
```
<img width="670" alt="cp" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/852c26db-d393-468c-ab81-88fc31ff1dd8">

 ## 7. mv command
this command moves and renames files and directories
 ```
mv test_file Documents
```
<img width="699" alt="7a mv" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/dd924742-2b08-480b-8e0d-a3fd96af482c">

renames a files

<img width="669" alt="7b mv" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/830cdb62-fea0-4d87-82a1-d3249c1814e2">

## 8. mkdir command
this command creates one of more directories
```
mkdir Doctors
```
<img width="764" alt="mkdir 1" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/cf0bcc61-3e3d-4dcb-ab49-5d65128ea0e0"

creates subdirectory

mkdir Doctors/ nurses

 <img width="679" alt="mkdir 2" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/00aab3f0-0d15-4981-9196-03f3b580d756">
create directory in between two directories

## 9. rmdir command
this command deletes an empty directory
```
rmdir DEVOPS
```
<img width="695" alt="rmdir" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/4b6de1b9-fd26-4bdc-8334-536211eb6dea">

## 10. rm command
>this command will delete files within a directory
```
rm DevOps
```
<img width="720" alt="rm" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/17b19c09-a329-4cde-9617-2bb5d4fe13ba">

## 11. touch command
this command creates an empty file
```
touch sqlite_comands.sh
```
<img width="683" alt="touch" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/5555a676-6b54-4a22-8c45-c45cabb2a11b">


## 12. locate command
>this command finds a file in the datbase system
```
locate
```
<img width="689" alt="locate" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/05c2217e-1024-42ea-8f61-1a4dc9ed1b99">


## 13. find command
>this command will search for files within a specific directory
```
find home/ name- project
```
<img width="712" alt="find" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/1481dbf1-044a-47ea-be87-10c779ce810b">

## 14. grep command
>this command finds a word by searching through all the text in a particuar file
```
grep blue DevOps.txt
```

<img width="754" alt="grep" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/7badf75b-5cb4-4170-a55b-37da2840025c">

## 15. df command
>this command will report the system disk space usage in percentage and kilobyte
```
df
```
```
df -m
```
![df](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/882b89e2-ffaa-41d3-bf7c-1970398c976f)
```
df -k
```
```
df -T
```
```
df -h
```
<img width="530" alt="df" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/f20418a4-87ad-4418-98e5-ae447af800a1">

## 16. du command
>this command will check how much disk space a file of directory will takes up
>it can also identify which part of the system uses the storage excessively.
```
du home/bukola/Music
```
<img width="694" alt="du" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/8d53729a-9899-43f6-9158-c43485ecb703">

## 17. head command
>this command allows you to view the first ten lines in a text
```
head DevOps.text
```
<img width="675" alt="head" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/b4a0eba3-aa53-427a-a323-f62ad2ecf413">

>specify the number of lines to display
```
## 18. tail command
>this command displays the last ten lines of a text

<img width="657" alt="tail" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/3dcad3e7-d3f5-4536-a8d0-1208b5bf6a70">

## 19. diff command
>this command is used to compare two contents of a text line by line, and then display the parts that do not match

<img width="490" alt="diff" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/37d88c36-abe5-449a-977b-4b70e3c0597a">

## 20. tar command
```
tar -cvf cloud.tar /home/ubuntu
```
>this command achives multiple files into a Tar file
<img width="729" alt="tar 1" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/4ada92ec-aa83-442b-9673-7e823cb52d6e">

## 21. chmod command
>this command changes a file of directory's read, write or execute permissions.
```
chmod 777 DevOps.txt
```
<img width="655" alt="chmod" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/38a5c85d-ed6c-4000-832a-4fa60c40453f">

## 22. chown command
>this command will allow you to change the ownership of a file or directory
```
chown Bukola DevOps.txt
```
<img width="636" alt="chown" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/4f33b773-d767-4155-a250-faf41018bc6b">


## 23. job command
>this command displays all the running processes along with their statuses.
```
job Documenets
```
<img width="579" alt="job" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/508135ea-f86c-41bd-9530-41e1205c8d3a">

## 24. kill command
>this command will terminate an unresponsive program manually.
>first identify the PID (program identification number)
```
ps ux
```
<img width="696" alt="kill" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/8f14681d-a03d-45bf-a147-cf930a4b27d8">


## 25. ping command
>this command will check whether a network or server is reachable.
```
ping google.com
```

<img width="717" alt="ping" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/2b80dfa9-7937-444b-8852-a7101bb57f22">


## 26. wget command
>this command lets you download things from the internet using the wget command
```
wget wordpress.org/latest.zip
```
<img width="690" alt="wget latest zip" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/802ecd36-b292-4a77-9e1f-c6025c1c1714">


## 28. top
>this command will display all the running processes and a dynamic real time view of the current system
```
top
```
<img width="718" alt="top" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/4b350996-6809-4284-8b0b-4bc40be69a8a">

## 29. history command
>this command will list 500 of previously executed commands allowing you to reuse them without retyping
```
history
```
<img width="657" alt="history" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/b264e8b6-3ff8-4ef8-adad-8e0a005e3aeb">

## 30. man command
>this command will provide the user manual of any command or utilities you can run in the terminal including name, description and options.
```
man ls
```
<img width="751" alt="man" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/ac915828-2776-4899-9743-64e213a49e8e">

## 31. echo command
>this command is a built in utility that displays a line of text or string using the standard output.
```
<img width="534" alt="echo" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/1555268b-f4e1-47c2-a072-9a0940b4d989">


## 32. zip, unzip command
>this command will compress files and directories into a zip file, to archive or reduce disk space usage.
```
zip first.zip test.txt devops
```
<img width="522" alt="zip" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/491065e7-22cf-48ea-b251-4c619de10ff8">

```
unzip first.zip
```
<img width="676" alt="zip and unzip" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/7763f6ea-a845-4cf9-b35e-757383828566">

## 33. hostname command
>this command will show the system's hostname or ip address
```
hostname
```
```
hostname -i
```
```
hostname -A
```
```
hostname -alias
```
<img width="498" alt="hostname" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/b9e0ddb5-cf41-456c-8ce9-1ea5eb136d63">

## 34. useradd, userdel commands
>the useradd command will create a new account
>the passwd command allows you to add a password
```
useradd liwox
```
<img width="510" alt="useradd" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/6052d992-e695-43e9-84a2-9f63a495154a">

## 35. apt-get command
>this command handles advanced package tools (APT) in Linux.
>it lets you retrive information and bundles from authenticated sources.
```
apt-get update
```
<img width="479" alt="apt- get update" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/dd5aa992-c8b6-4f38-bed8-939df96a093e">

## 36. nano, vi, jed commands
>the nano command denotes keywords
```
nano liwox.html
```
<img width="496" alt="nano 1" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/e22f1421-955a-4565-b18b-33edee4d5c4e">

>the vi command works in two modes
 >insert and command: this can edit and create a text file
 >perform operations such as copying, saving, openig and pasting a file.
```
vi 
```
<img width="578" alt="nano2" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/dd7970da-89e6-4dda-85c5-a07ed9e9dc00">

<img width="599" alt="nano 3" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/9b45a9a8-3e0d-4d90-b4a7-fc49f54fc623">

## 37. alias, unalias command
> this command allows you to create a shortcut with the same functionality as a command, file name or text.
```
alias dv='devops.text'
```
> the unalias command deletes an existing alias
<img width="674" alt="alias unalias" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/95f0831a-a57d-4e93-9d59-5dfa69b13dca">

```
unalias dv
```

## 38. su command
>the su command allows you to run a program as a different user. it is beneficial for accessing the system through SSH or GUI display when root user is unavailable.
```
su
```
<img width="738" alt="su" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/4f2aa340-928a-4055-b3d1-facd961c27a3">


## 39. htop command
>this command monitors system resources and server processes
>htop command has additional features and improvements than the top command
```
htop -d
```
```
htop -C
```
```
htop -h

<img width="546" alt="htop" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/1fab462a-b24d-4b4a-8fe6-0537d996feb0">

## 40. ps command
>this command produces a snapshot of all the processes on your system.
```
ps -T
```
```
ps -u
```
```
ps -A
```
```
ps -e
```
<img width="452" alt="ps" src="https://github.com/Bukolaogunwale1/PROJECT-1-LINUX/assets/122865359/26ec02a7-1a1c-414e-b087-e37143011b7c">




```



```
jed liwox.html
```
![jed](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/825bb395-42e2-42d4-bf8a-7b83af09f84d)
















