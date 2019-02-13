## Command Line Commands ##
~ -home directory
---
___
* ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
* . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
* .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.
___
ls – list of files in the current directory
ls -l – lists files with additional information
ls /etc - to list the directory’s contents
ls  /Users/nborders/ds - look at the contents of a specific directory  
/etc - Stores config files for the system.
/var/log - Stores log files for various system programs. (You may not have permission to look at everything in this directory. Don't let that stop you exploring though. A few error messages never hurt anyone.)
/bin - The location of several commonly used programs (some of which we will learn about in the rest of this tutorial.
/usr/bin - Another location for programs on the system. 
cd – changes the directory
after cd there is a path – relative or absolute (always start with a forward slash which represents the absolute root of your file system).
Tab – tries to match what you’ve typed so far.
pwd – print working directory
cd .. – go up one step in directory
cd ~ - go to the home directory
rmdir – delete a directory
mkdir – make a directory
atom FILENAME – makes an Atom file right in the directory
rm -rf – delete for fucking sure DO NOT USE EVER UNLESS 100% SURE!!!!!!!!!!
echo $SHELL - tells you what shell you’re using
If you have two words in name with space, you can either put them in quotes or put \ in between the words such as : 'Holiday Photos' or Holiday\ Photos
 ls -a - shows hidden files
 file - obtains information about what type of file it is

    man <command> - Look up the manual page for a particular command.
* man -k <search term> - Do a keyword search for all manual pages containing the given search term.
* /<term> - Within a manual page, perform a search for 'term'
* n - After performing a search within a manual page, select the next found item.

mkdir - Make Directory - ie. Create a directory.
rmdir - Remove Directory - ie. Delete a directory.

    touch - Create a blank file.
* cp - Copy - ie. Copy a file or directory.
* mv - Move - ie. Move a file or directory (can also be used to rename).
* rm - Remove - ie. Delete a file.
* vi - Edit a file.
* cat - View a file.
* less - Convenient for viewing large files.
* 
pwd - shows current working directory path
mkdir -	create a directory
rmdir - remove a directory
touch -	creates	a blank	file
rm - delete a file
mv - rename a file
ls -a -	lists hidden files
cp - copies a file from	one directory to the other

# print present working directory
pwd
/Users/reshamashaikh/ds/metis/metisgh
# create new directory
mkdir prework
# list files
ls
# change directory, go into prework directory
cd prework
# clone the repo
git clone https://github.com/reshama/dsp.git
ls
# change directory, go into dsp
cd dsp
ls
# see what the remotes are
git remote -v
# use editor to view and edit file
emacs 00-fork_repo.md

# check if any changes have been made to local repo; changed files will be in red
git status
# add a file, also means 'staging file'
git add 00-fork_repo.md
# check that file is staged, staged file will be in green
git status
# commit a file; adding message to commit to track changes made
git commit -m 'added emoji'
# check that file has been committed
git status
# push file to forked repo
git push

# clear screen
clear
ls

# open up file and see if any changes have been made to file
emacs 00-fork_repo.md

# check remotes
git remote -v
# pull updates from forked repo on broswer
git pull
ls
# check file and see that the updated changes from browser file are now in local file
emacs 00-fork_repo.md

# clear screen
clear
# print history of commands used
history
  
* ls - lists files in your directory
* ls -a	lists files in your directory including	*hidden ones*
* ls -l	lists in long format, total sum	of file	sizes
* ls -lh uses unit suffixes in the list of the total sum of file sizes, to redu\
ce the number of digits	to three or less.
* ls -t	sort by	time modified (most recently first) before sorting by name.
* ls -Glp lists long format directories with "/" appended to the end and withou\
t user group names

chmod - Change permissions on a file or directory.
ls -ld - View the permissions for a specific directory.

head - View the first n lines of data.
tail - View the last n lines of data.
sort - Organise the data into order.
nl - Print line numbers before data.
wc - Print a count of lines, words and characters.
cut - Cut the data into fields and only display the specified fields.
sed - Do a search and replace on the data.
uniq - Remove duplicate lines.
tac - Print the data in reverse order.
