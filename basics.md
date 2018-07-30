# Basics
Corresponding videos:
- [Absolute Basics](https://www.youtube.com/watch?v=id3DGvljhT4)
- [Basics 01](https://www.youtube.com/watch?v=Lbh8Bh_SEzU)
- [Basics 02](https://www.youtube.com/watch?v=fEGSA68uAR4)


```
# files and directories that start with a dot are hidden 
.file 
```

```
# tilde sign
# a shortcut to the home-directory of the user e.g. /   home/userxyz
~
```

```
# one dot
# means this directory, so if you are in /home/userxyz . means /home/userxyz
.   
```

```
# two dots
# means "up" a directory, so if you are in /home/userxyz .. means /home
..
```

```
# slash
# the root directory 
/
```
## man

```
# manual
# manual page for every command
man
# in the manual press q to leave
```

## pwd

```
# print working directory
# which folder am i in?
pwd
```

## ls 
```
# list directory content
# lists non hidden files / directories / objects in a directory
ls
# lists all files / directories / objects in a directory
ls -a
# lists it as list
ls -l
# lists it human readable
ls -alh
```

## cd

```
# change directory
# changes the directory you are in
# cd without anything brings you back to your homedirectory
cd
```
## clear

```
# scrolls to the line you are working in
clear
```

## touch

```
# create an empty file
touch
```

## cat

```
# print out an file
cat file 
# add a file to the end of the other file
cat file1 file2
```

## mkdir

```
# make directory
# creates a new directory
mkdir myfolder
# create whole path
mkdir -p myfolder/anotherfolder/testfolder
```

## mv
```
# move
# move file
mv
```

## rm

```
# remove
# remove file
rm file
# force remove
rm -f 
# remove recursively
rm -r folder
```

## rmdir

```
# remove
# remove folder, most people use rm -r
rmdir
```