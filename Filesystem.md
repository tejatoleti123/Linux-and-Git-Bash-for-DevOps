# Filesystem Commands

pwd  
Prints the current working directory to confirm execution context.

ls  
Lists files and directories in the current location.

ls -la  
Lists all files including hidden ones with permissions and ownership details.

cd /path/to/directory  
Changes the current working directory.

mkdir directory  
Creates a new directory.

mkdir -p parent/child  
Creates nested directories safely without errors if they exist.

rm file  
Deletes a file permanently.

rm -r directory  
Deletes a directory and its contents recursively.

cp source destination  
Copies a file from source to destination.

cp -r dir1 dir2  
Copies a directory recursively.

mv old new  
Renames or moves files and directories.

find . -name "*.log"  
Searches for files by name in the directory tree.

df -h  
Displays disk usage in human-readable format.

du -sh *  
Shows the size of files and directories.
