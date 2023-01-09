# Overview of Common Linux Shell Commands

- O Shell padrão é normalmente o `bash`;
- verificar o shell da máquina:
- 
```shell
printenv SHELL
```

## Getting information:

- `whoami`: username;
- `id`: user ID and group ID;
- `uname`: operating system name;
- `ps`: running processes;
- `top`: Resource usage;
- `df`: mounted file systems;
- `man`: reference manual;
- `date`: today's date

## Working With Files

- `cp`: copyy file;
- `mv`: change file name or path;
- `rm`: remove file;
- `touch`: create empty file, update file timestamp;
- `chmod`: change/modify file permissions;
- `wc`: get count of lines, words, characters in file;
- `grep`: return lines in file matching pattern

## Navigating & working with directories

- `ls`: list files and directiores;
- `find`: find files in directory tree
- `pwd`: get present working directory;
- `mkdir`: make directory;
- `cd`: change directory;
- `rmdir`: remove directory;

## Printing file and string contents
- `cat`: print file contents;
- `more`: print file contents page-bu-page;
- `head`: print first N lines of file
- `tail`: print last N lines of file;
- `echo`: print string or variable value

## Compression and archiving
- `tar`: archive a set of files;
- `zip`: compress a set of files;
- `unzip`: extract files from compressed zip archive;


## Networking

`hostname`: print hostname;
`ping`: send package to URL and print response;
`ifconfig`: display or configure system network interfaces;
`curl`: display contents of file at URL;
`wget`: download file from URL
