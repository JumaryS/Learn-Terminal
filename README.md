
# Learn-Terminal
Joshua and Jumary terminal command lines


# Learn the term

![cool gif](https://sweetcode.io/wp-content/uploads/2018/01/ascii_dog.gif)



# Command line tutorial
![mkdir gif](https://www.cyberciti.biz/media/new/images/faq/2013/07/mkdir-demo.gif)

       1.lets start with making a directory in your terminal by using mkdir (make directory)

       2. Name the directory what ever you want 


       3. Make sure to verify by usuing ls or (list) to view whats in your directory.

#  Now lets access your newly made directory 
 
       1. We can use  cd or (change directory) followed by the (name of file) then press enter
        
     
 # Creating files within directory
![](https://miro.medium.com/max/2544/1*a0oGb11RDJDgaCvTcLy1jw.gif)

       1.once you are in your new directory we can start creating files within by using the word (touch) for example touch (name of file you want) and then press enter




## __TERMINAL COMMANDS__

##### __Change Directory__ `cd`
---
 
`cd`||| `cd [dir]` ||| `cd [folder]` ||| `cd ~` ||| `cd/`	||| `cd -` ||| `pwd` |||	`cd..` ||| `cd../..` 

```
cd	Home directory
cd dir	Change directory, e.g. cd Documents
cd ~	Home directory
cd/	Root of the drive
cd -	Previous directory or folder you last browsed
pwd	Show your working directory
cd..	Move up to the parent directory
cd../..	Move up two levels
```

##### __List Directory Contents__ `ls`
---
`ls` ||| `ls -C` ||| `ls -a` ||| `ls -1	` ||| `ls -F`	||| `ls -S` ||| `ls -l` |||	`ls -lt` ||| `ls -lh` ||| `ls-lo` ||| `ls-la` 

```
ls	Display the name of files and subdirectories in the directory
ls -C	Force multi-column output of the listing
ls -a	List all entries including those with .(period) and ..(double period)
ls -1	Output the list of files in one entry per line format
ls -F	Display a / (slash) immediately after each path that is a directory, * (asterisk) after executable programs or scripts, and @ after a symbolic link
ls -S	Sort files or entries by size
ls -l	List in a long format. Includes file mode, owner and group name, date and time file was modified, pathname, and more
ls -lt	List the files sorted by time modified (most recent first)
ls -lh	Long listing with human readable file sizes in KB, MB, or GB
ls -lo	List the file names with size, owner, and flags
ls -la	List detailed directory contents, including hidden files
```

##### __File and Directory Management__ `mkdir` `cp` `rm` `mv`
---
`mkdir <dir>` ||| `mkdir -p <dir>/<dir>` ||| `mkdir <dir1> <dir2> <dir3>` ||| `mkdir "<dir>"`
```
mkdir <dir>                 Create new folder named <dir>
mkdir -p <dir>/<dir>        Create nested folders
mkdir <dir1> <dir2> <dir3>  Create several folders at once
mkdir "<dir>"               Create a folder with a space in the filename
```

`touch <file>` ||| `rmdir <dir>`	 ||| `rm -R <dir>`
```
touch <file>                Create a new file without any extension
rm <file>                   Delete a file (This deletes the file permanently; use with caution.)
rm -i <file>                Delete a file only when you give confirmation
rm -f <file>                Force removal without confirmation
rm <file1> <file2> <file3>  Delete multiple files without any confirmation
rmdir <dir>                 Delete a folder (only works on empty folders)
rm -R <dir>                 Delete a folder and its contents
```

`cp <file>`	 ||| `cp <file> <newfile>	` ||| `cp <file>~/<dir>/<newfile>` ||| `cp -R <dir> <"new dir">` ||| `cp -i <file><dir>` ||| `cp <file1><file2><file3>/Users/<dir>`
```
cp <file> <dir>                         Copy a file to the folder
cp <file> <newfile>                     Copy a file to the current folder
cp <file>~/<dir>/<newfile>              Copy a file to the folder and rename the copied file
cp -R <dir> <"new dir">                 Copy a folder to a new folder with spaces in the filename
cp -i <file><dir>                       Prompts you before copying a file with a warning overwrite message
cp <file1> <file2> <file3>/Users/<dir>	Copy multiple files to a folder
```

`mv <file> <newfilename>` ||| `mv <file> <dir>` ||| `mv -i <file> <dir>` ||| `mv *.png ~/<dir>`
```
mv <file> <newfilename>	Move/rename
mv <file> <dir>	        Move a file to the folder, possibly by overwriting an existing file
mv -i <file> <dir>      Optional -i flag to warn you before overwriting the file
mv *.png ~/<dir>        Move all PNG files from current folder to a different folder
```
