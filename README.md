My devops readme

# Linux Shell Comands

## File System
Making a directory *A directoy is a folder*
> `$ mkdir dir_name`

Deleting an empty directory
> `$ rmdir dir_name`

Deleting a directory which has content
> `$ rm -r dir_name`

creating a file, *Mostly a text file with UTF-8 or ASCII  encoding*
> `$ touch file_name.ext`

*I use .ext to mean your prefered file extension like `.txt` for plain text files, `.py` for python files or `.js` for JavaScript files*

deleting a file 
> `$ unlink file_name`

listing the content of a directory
> $ ls

opening a directory or navigating into a prefered directory
> $ cd dir_name
> dir_name$

navigating to a parent directory
> dir_name$ cd ..
> $

navigating to a sibling directory
> $ ls
> dir_name another_dir info.txt
> $ cd dir_name
> dir_name$ cd ../another_dir
> another_dir$

creating multiple directories
> $ mkdir dir_1 dir_2 dir_3
> $ ls
> dir_1 dir_2 dir_3

creating multiple files
> $ mkdir web
> $ cd web
> web$ touch index.html script.js styles.css
> web$ ls
> index.html script.js styles.css

doing it in a single line
> $ mkdir web && cd web && touch index.html script.js styles.css && ls
> index.html script.js styles.css

*`&&` lets the early comand run the the later one*

deleting the content of a directory
> $ rm -r *

removing files with similar names using wild card
> $ ls
> dir_1 dir_2 dir_3 decscripton.txt files.txt 
> $ rm dir*
> $ ls
> decscripton.txt files.txt
> $ rm \*.txt
> $ ls
>

`rm dir*` will remove all files and directories that start with dir while `rm *.txt` will remove all files whose names ends with `.txt`

