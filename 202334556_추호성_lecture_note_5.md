# CLI comands 2

- ## cat, >, >>
```
//make list.txt
ls > list.txt
 //append to list.txt
ls >> list.txt
//print text
$cat list.txt
```

- ## sort, <
```
$sort < list.txt //sort 
```

- ## |
```
//view first value
$ls | less 
//print file count
$ls | wc -l
```

- ## echo
```
$echo *
$echo ~
```

- ## \
```
$ls -l \
> --reverse \
> --human_readable
```
```
//see previous command history
$history
```
---
# Permission
\- | - - - | - - - | - - - |
filetype|Owner|Group|Others|

\- - -
r - - : can read
\- w - : can write
\- - x : can run

File Type:
\- : Regular file
d : Directory


- ## chmod
rwxr-x--x => 111 101 001 => 7 5 1
```
//chmode [Permission] [filename]
$chmod 751 myfile.cpp
```

- ## superuser
superuser has all authority
```
$sudo [command]
$sudo -i
```

---
# Shell Script
```
//run shellscript
$sh script.sh
```