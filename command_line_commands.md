## Command Line Commands ##
~ - home directory
~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
. (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
.. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

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
man -k <search term> - Do a keyword search for all manual pages containing the given search term.
/<term> - Within a manual page, perform a search for 'term'
n - After performing a search within a manual page, select the next found item.
