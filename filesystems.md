# Filesystems

The Linux filesystem is structured as a hierarchical tree with the root directory (/) at the top. All other directories and files branch from this root, organized into standard directories like:

• `/home`: User home directories, where personal files and settings are stored.  
• `/etc`: Configuration files for the system and software.  
• `/bin` and `/usr/bin`: Essential system and user program binaries.  
• `/var`: Logs and other variable data files.  

Basic Commands for Navigating and Managing Files:

## 1.	Viewing the current directory:
```
pwd
```
Shows the path of the current working directory.


## 2.	Listing files and directories:
```
ls
```
Displays the contents of the current directory. Add -l for detailed info or -a to show hidden files.


## 3.	Changing directories:
```
cd <directory_name>
```
Moves to the specified directory (e.g., cd /home).

## 4.	Creating a file:
```
touch <file_name>
```
Creates an empty file (e.g., touch myfile.txt).

## 5.	Creating a directory:
```
mkdir <directory_name>
```

## 6.	Viewing file contents:
```
cat <file_name>
```
Displays the content of a file (e.g., cat myfile.txt).

## 7. Deleting a file or directory:
```
rm <file_name>
```
Deletes a file. To delete a directory and its contents, use:



```
rm -r <directory_name>
```



