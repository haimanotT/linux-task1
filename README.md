# Linux Task 1 Basics

## Student Information
Name: Haimanot Tadase
Department: Computer Science

## Introduction

This task helped me practice basic Linux commands and understand how to work with files and directories from the terminal I completed all the required steps in Kali Linux and documented the commands I used.

## Step 1 Create a Directory
I created a directory called linux_tests using the following command
mkdir linux_tests
This command creates a new folder where I can store files and perform my practice tasks.

## Step 2 Create Three Files
Inside the linux_tests directory, I created three files
touch one.txt two.txt three.txt
The touch command is used to create empty files inside newly created repository

## Step 3 List the Files
To verify that the files were created successfully, I used
ls command The "ls" command lists the contents of the current directory.
The output showed the following text or file
one.txt
two.txt
three.txt

## Step 4 Add Text to Each File
I added different text to each file
echo " Linux practice" > one.txt
echo " learning Cybersecurity" > two.txt
echo "training" > three.txt
The "echo" command prints text or display output, and the ">" symbol redirects or put that text into a file.

## Step 5 Rename a File
I renamed "three.txt" to "final.txt"
mv three.txt final.txt
The "mv" command can be used to rename files or move them to another location.

## Step 6 Copy a File
I created another directory and copied "one.txt" into it
mkdir notes
cp one.txt notes/
The "cp" command creates a copy of a file while keeping the original file unchanged.

## Step 7 Delete a File
I removed "two.txt" by using
rm two.txt
The "rm" command permanently deletes a file.

## Step 8 Show the Current Directory and Its Contents
Finally, I checked my current location and listed the remaining files
pwd
ls
The "pwd" command displays the current working directory, while "ls" lists its contents.

## Screenshots
The screenshots uploaded in this repository show proof that each task was completed successfully.

## basic command
mkdir
cd
ls
touch
echo
cat
cp
mv
rm
pwd
This task improved my understanding of basic Linux file management and these commands are important linux fundamentals for cybersecurity and ethical hacking
