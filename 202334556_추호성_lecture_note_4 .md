# Lab4 : lecture note

---

- **CLI** - Command Line Interface
- **GUI** - Graphical User Interface

---
## Shell commands
### - **check recent directory** : $ pwd
```
$ pwd
/c/Users/CHC04
```
### - **change directory** : $ cd [arguemant]
#### arguemant types:
- [directoryname]  
- / root
- . currentdirectory  
- .\. upper-leveldirectory 
- ~ homeofcurrentuser 
- /[directoryname] : absolutepath 
- ./[directoryname] : relativepath  
- .\./[directoryname] : relativepath
```
$ cd [dirextory name] //nomal
$ cd /
$ cd .
$ cd ..
$ cd ~
$ cd /[]
$ cd ./[]
$ cd ../[]
```
### - **check files list** : $ ls [option]
#### options:  
- -l : show detailed information(longformat) 
=> [file premission] [owner] [group] [size] [modification date] [file name]
- -lh : same as above,but size in units
```
$ ls
file1   file2   file3   ...
$ ls -l
-rw------- 1 chc04 chc04 3424 8월 19 16:33 file1.txt
-rw-rw-r-- 1 chc04 chc04 2403 8월 19 19:15 file2.md
-rw-rw-r-- 1 chc04 chc04 5032 8월 23 11:56 file3.cpp 
...
$ ls -lh
-rw------- 1 chc04 chc04 3.4K 8월 19 16:33 file1.txt
-rw-rw-r-- 1 chc04 chc04 2.4K 8월 19 19:15 file2.md
-rw-rw-r-- 1 chc04 chc04 5.0K 8월 23 11:56 file3.cpp 
...
```
### - **copy file or directory** : $ cd [option] [file or directory name] [file or directory name]
#### 

```
$ cp file1 file2
$ cp file1 directory1
$ cp -r directory1 directory2
```

### - **move file or directory, and rename** : mv [option] [file or directory name] [file or directory name]
```
//rename file1 to 'new_name'.
$ mv file1 new_name
//rename dir1 to 'dir2',  if dir2 dose not exist.
$ mv dir1 dir2
//move file1 into 'directory1'
$ move file1 directory1
```
### - **remove file or directory** : rm [option] [name]
```
$ rm file1
$ rm dir1
```
### - **make new directory** : mkdir [new directory name]
```
$ madir my_new_dir
```
### - **others**
```
$ help [command]
$ man [command]
//example
$ help cd
$ man cp

//clear commands
$ clear
//close shell
$ exit
```
---
## Wildcard
- \* : all filenames
- g* : all filenames that begin with the character "g"
- b*.txt : all filenames that begin with the character "b" and end with th characters ".txt"
- Data??? : any filename that begins with the characters "Data" followed by exactly 3 more characters